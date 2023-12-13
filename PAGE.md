# PAGE (Polyacrylamide Gel Electrophoresis)

1. [Introduction](#231)
2. [Native PAGE vs SDS PAGE](#232) `<br>`
   2.1. [Native PAGE](#2321) `<br>`
   2.2. [SDS PAGE](#2322)
3. [Procedure of SDS](#235)
4. [Interpretation](#233)
5. [Applications](#234)

## 1. Introduction `<a name="231"></a>`

Polyacrylamide Gel Electrophoresis(PAGE) is a technique that separates macromolecules based on their electrophoretic mobility which is the ability of analytes to move towards an electrode of the opposite charge. Compared to agarose gel which can also be used for electrophoresis, acrylamide gel is used for smaller molecules like proteins and nucleic acids because it has smaller pores. The separation of proteins in PAGE depends on the charge, size, and shape of the molecule.

To capture the interaction (crosslink between strings), there are few steps in general:

- Take a snapshot of the flowing cells - **Crosslink** with fixative agent (formaldehyde)
- Zoom in on crosslinked part and exclude untangled parts - **Digested** with a restriction enzyme
- Analyze the components come from the same chromatin - **Reverse crosslink** and **sequence**
- Finish the jigsaw puzzle and get the results - **Align** the reads and **summarize** the contacts

> Based on these general ideas, then we'll dive deeper by walking through two of the most popular  techniques and then briefly introduce some other methods.

## 2. Native PAGE vs SDS PAGE `<a name="232"></a>`

![](/assets/1-s2.0-S1360138518300827-gr1b2_lrg.jpg)
[Figure1](https://doi.org/10.1016/j.tplants.2018.03.014). Schematic Representation of Chromosome Conformation Capture (3C) and 3C-Derived Methods. These methods help to elucidate nuclear organization by detecting physical interactions between genetic elements located throughout the genome. Abbreviations: IP, immunoprecipitation; RE, restriction enzyme. **Figure by Sotelo-Silveira, Mariana, et al. Trends in Plant Science (2018).**

To better understand the difference between these methods, I'd like to distingush them between the following couple of aspects:

#### 1) Native PAGE `<a name="2321"></a>`

‘1’, ‘Many’ and ‘All’ indicate how many loci are interrogated in a given experiment. For example, ‘1 versus All’ indicates that the experiment probes the interaction profile between 1 locus and all other potential loci in the genome. ‘All versus All’ means that one can detect the interaction profiles of all loci, genome-wide, and their interactions with all other genomic loci [1].

These kind of specificity is determined by the primer when people use **specific primers** before PCR.

#### 2) SDS PAGE `<a name="2322"></a>`

![1702354442303](image/PAGE/1702354442303.png)

The figure above shows that the protein is composed of two subunits. When the protein is treated with SDS molecule, its intact structure would get disrupted by attachment to negative chage of SDS. This leads to the protein denaturation and the mask of the original charges of amino acid by the coating. Now, having approximately same charge, density, shape, 'size' or 'molecular weight' would be the only paramter. [2].

## 3. Procedure of SDS `<a name="233"></a>`

![1702368233069](image/PAGE/1702368233069.png)

<table>
 <tbody>
    <tr>
        <th>Steps</td>
        <th>Description</td>
    </tr>
    <tr>
        <td>Sample Preparation <a href="http://refhub.elsevier.com/S2001-0370(17)30093-4/rf0535">[3]</a></td>
        <td><ul><li>Treat the protein for denaturation with SDS and beta-mercaptoethonol with heat</li><li>Coating of the original charge yields the similar charge, density, shape of the polypeptide chains</li><li>This helps the gel electrophoresis strictly based on the 'molecule weight' and 'size'</li></ul></td>
    </tr>
    <tr>
    <td>Gel Preparation <a href="http://refhub.elsevier.com/S2001-0370(17)30093-4/rf0545">[4]</a></td>
    <td><ul><li>Requires BIS, acrylamide, and a buffer for the mixture of gel</li><li>This mixture prevent forming the bubble during the Gel electrophoresis process</li><li>Allows the separation of the proteins at the end by creating the gel matrix</li></ul></td>
    </tr>
    <tr>
    <td>Gel Electrophoresis <a href="http://refhub.elsevier.com/S2001-0370(17)30093-4/rf0550">[5]</a></td>
    <td><ul><li>Protein migration occurs towards negative electrode by the electric current</li><li>Different rate of each molecule's migration indicates the molecule weight</li><li>Leads to the separation of protein molecule based on their size</li><li>The voltage strength controls the migration speed
</li></ul></td>
    </tr>
    <tr>
    <td>Staining and Visualization <a href="http://refhub.elsevier.com/S2001-0370(17)30093-4/rf0300">[6]</a></td>
    <td><ul><li>The result of the gel electrophoresis can be detected by using the colored dye</li><li>Separated protein molecule stained in distinct color by tracking dye</li><li>Coomassie Brilliant or Blue or ehtidium bromide , major colored dye used, will be washed out if unbound</li></ul></td>
    </tr>
    <tr>
    <td>Analysis <a href="http://refhub.elsevier.com/S0168-9525(15)00063-3/sbref1405">[7]</a></td>
    <td><ul><li>Analysis of the protein band's color intensity will proceed by using autoradiography</li><li>Amout of the protein molecule is directly proportional to the color intensity, meaning the amount of the bound dye</li></ul></td>
    </tr>
 </tbody>
</table>

# 4. Interpretation `<a name="234"> </a>`

# 5. Applicaton `<a name="235"> </a>`

Referrence

[1] Schmitt, Anthony D., Ming Hu, and Bing Ren. "Genome-wide mapping and analysis of chromosome architecture." Nature reviews Molecular cell biology 17.12 (2016): 743.`<br>`

[2] Risca, Viviana I., and William J. Greenleaf. "Unraveling the 3D genome: genomics tools for multiscale exploration." Trends in Genetics 31.7 (2015): 357-372.`<br>`

[3] Dekker J, Rippe K, Dekker M, Kleckner N. Capturing chromosome conformation. Science 2002;295(5558):1306–11.`<br>`

[4] Simonis M, Klous P, Homminga I, Galjaard RJ, Rijkers EJ, Grosveld F, et al. High-res- olution identification of balanced and complex chromosomal rearrangements by 4C technology. Nature Methods 2009;6(11):837–42.`<br>`

[5] Dostie J, Richmond TA, Arnaout RA, Selzer RR, Lee WL, Honan TA, et al. Chromo- some Conformation Capture Carbon Copy (5C): a massively parallel solution for mapping interactions between genomic elements. Genome Res 2006;16(10): 1299–309.`<br>`

[6] Lieberman-Aiden E, van Berkum NL, Williams L, Imakaev M, Ragoczy T, Telling A, et al. Comprehensive mapping of long-range interactions reveals folding principles of the human genome. Science 2009;326(5950):289–93.`<br>`

[7] Fullwood, M.J. et al. (2009) An oestrogen-receptor-alpha-bound human chromatin interactome. Nature 462, 58–64.`<br>`

[8] https://github.com/hms-dbmi/hic-data-analysis-bootcamp/blob/master/HiC-Protocol.pptx.
