# Machine Learning - Dimension Reduction
By Chen Li
## Introduction
After we obtain an expression matrix RNA-seq, in which every row is a gene, and every column is a sample, how can we get a general sense of the distribution of the data and extract important features (genes) from the data matrix? Note that the expression matrix is usually in a high dimensional space because every gene is a dimension, so directly visualizing the data is impossible for human beings. Dimension reduction techniques such as PCA and t-SNE can map the original data in high dimension to lower dimension while retaining some spatial information (similarity and difference between samples). In this way, we can easily visualize the data in 2D space. In addition, PCA can return the *importances* of the features (genes), which are the ability of these features in grouping and separating the data points. By extracting the most important genes from the raw data matrix, we are able to explore the data such as clustering more easily. 

1. [PCA](#pca)
2. [t-SNE](#t-sne)
3. [PCA vs t-SNE](#pca-vs-t-sne)

### PCA
PCA (Principle Component Analysis) is widely used upstream of calculations that handle high dimensional data badly. PCA is a linear transformation method. It preserves the correlation between point x and y after transformation. PCA can reduce 4 or higher dimension graph to 2D or 3D. Let’s take a expression matrix for 6 mouse samples as an example. We will only use two genes for illustration. Youtube Reference: [StatQuest](https://www.youtube.com/watch?v=FgakZw6K1QQ)

![](https://github.com/danielee0707/BENG183/raw/master/images/1.png)

Now let's go through the steps in PCA calculation:
1. The data set is first moved so that its center is at origin. Then PCA calculates the top components with the highest variations in the data. What it does is to fit a line to the data set. For an arbitrary line in the plane through the origin, the (sum of squared) distances to the projections of all the points are calculated and maximized. This has the same effect as minimizing all the distances between the points and the line. (In real world, calculation is done by linear algebra.)

![](https://github.com/danielee0707/BENG183/raw/master/images/2.png)
![](https://github.com/danielee0707/BENG183/raw/master/images/3.png)

2. This line is called PC1, or **Principal Component** 1, and it captures the largest variation in the data. From the resulting line, we also know what its compositions based on the slope: it contains 4 parts Gene1 plus 1 part Gene2.

3. PC2 is simply the line perpendicular to PC1. If the data is in 3D, PC2 will be residing in a plane perpendicular to PC1, and the previous steps will be repeated. All dotted lines are perpendicular to each other.

![](https://github.com/danielee0707/BENG183/raw/master/images/4.png)
![](https://github.com/danielee0707/BENG183/raw/master/images/6.png)

4. In the final step, we rotate the coordinates so that PC1 becomes x-axis and PC2 becomes y-axis. The top two PCs are able to explain 94% of all variations in the data.

![](https://github.com/danielee0707/BENG183/raw/master/images/5.png)

**Note:**
When performing PCA transformation, only the top several PCs are used, and other PCs (dimensions) are discarded. Information is *lost* in this process.

### t-SNE
By projecting data points to a plane of high variability, PCA tries to place dissimilar data points far apart and only preserves the global structure of data points (which means it may not be powerful enough to distinguish subgroups). So we will need t-SNE to see more detailed neighboring structures.

![](https://github.com/danielee0707/BENG183/raw/master/images/7.png)
![](https://github.com/danielee0707/BENG183/raw/master/images/8.png)

[Image Source](https://www.kaggle.com/puyokw/clustering-in-2-dimension-using-tsne/code)

1. So how does t-SNE work? The name stands for t-distributed stochastic neighbor embedding. The underlining mathematics of t-SNE is very advance and will not be covered here. But basiclly, it applies neighborhood preserving mapping so that distances between neighboring points are truthfully preserved after transformation.

2. But how do we determine neighbors? *Perplexity* represents roughly the number of potential neighbors considered for a cluster, so we can determine neighbors of each point and thus clusters by trying different perplexity parameters until a reasonable and clear clustering is visualized by t-SNE. This is usually determined arbitrarily. Youtube Reference: [Applied AI Course](https://www.youtube.com/watch?v=FQmCzpKWD48&list=PLupD_xFct8mHqCkuaXmeXhe0ajNDu0mhZ&index=1)

![](https://github.com/danielee0707/BENG183/raw/master/images/9.png)

3. Meanwhile, since there is always some randomality in t-SNE’s embedding, we need to run multiple *iterations* to improve the 2D embedding to best represent the original structure. Such number of iterations is another hyperparameter to choose, and generally, the more iterations t-SNE runs, the more credible the resulting embedding will be.

![](https://github.com/danielee0707/BENG183/raw/master/images/10.gif)

**Note:**
* The size of each cluster in a t-SNE plot means nothing because it tends to expand dense clusters and shrink sparse ones.
* Since t-SNE only represents distances within a potential cluster, distances between clusters do not provide any information.

### PCA vs t-SNE
Like many other machine learning techniques, PCA and t-SNE have their own advantages and disadvantages. When to use them depends on what you want to achieve. Please note that they are only two of the vast number of dimension reduction methods, and there are also ones that serve very similar purposes such as *ICA* and *UMAP*. [Reference](https://www.datacamp.com/community/tutorials/introduction-t-sne)
1. t-SNE is much more computationally expensive than PCA.
2. PCA is deterministic while t-SNE is not. Hyperparameters for t-SNE are somewhat arbitrary.
3. Information is lost during PCA calculation while t-SNE attempts to capture information from all dimensions.
