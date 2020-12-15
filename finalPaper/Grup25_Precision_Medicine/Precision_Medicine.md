
# The Process of Precision Medicine
### by Soyeon Kim, Hwayeon Lee, Meixian Wu

1. [What is Precision Medicine?](#1)<br>
    1.1. [Definition](#11)<br>
    1.2. [Framework of Precision Medicine Process](#12)<br>
2. [Deep Phenotyping](#2)<br>
    2.1. [Importance of Phenotype](#21)<br>
    2.2. [Why "Deep" Phenotyping?](#22)<br>
    2.3. [Processing Deep Phenotyping Data](#23)<br>
3. [Data Analysis](#3)<br>
    3.1. [Preprocessing and Data Mining](#31)<br>
    3.2. [Diagnostic and Prognostic Models](#32)<br>
    3.3. [Predicting Treatment Response](#33)<br>
4. [Evolving Precision Medicine](#4)
5. [Conclusion](#5)
6. [References](#6)


## 1. What is Precision Medicine?<a name="1"></a>

### 1) Definition<a name="11"></a>

Precision medicine is personalized treatment strategies on the basis of genetic, biomarker, phenotypic or psychosocial characteristics to stratify patients into novel subpopulations that differ in their susceptibility to a particular disease or their response to a specific treatment. It is also commonly referred to as 'stratified medicine', 'targeted therapy' and 'deep phenotyping.'

The focus is to move away from classical 'signs-and-symptoms’ approach or 'population’ approach into 'N of 1’ approach in which each patient is an entire trial or a single case study from N number of individuals within a population. Figure 1 shows the difference between classical approach and precision medicine approach. Ultimately, comprehensive study of such subclasses depends on computational resources to capture, store and exchange phenotypic data and upon sophisticated algorithms to integrate it with genomic variation, omics profiles, and other clinical information.

![f1](https://www.abpischools.org.uk/thumbnails/0/1151.20.jpg)

##### Figure 1: The left diagram shows treatment based on 'signs-and-symptoms' research. Patients with colon cancer are clustered into one group and given the same therapy, which thereby varies in treatment responses. Treatment has worked for some individuals while it had no or adverse effect for other. This is because this approach does not take patients' phenoytpic information into account. On the right, the same group of patients have been divided into subgroups based on individual phenotypic recognition, resulting in better understanding of the causal pathways and better treatment responses. 

### 2) Framework of Precision Medicine Process<a name="12"></a>

At the highest level, precision medicine process is a framework made up of feedback loops, with no steady-end point. Each cycle is an attempt to sort out and validate the process and stratify the subgroups further. The data assessed in the patients are used to try to develop clinically relevant models, and analyses inform need for further assessment of patients as an evolving result.  

![f2](https://erj.ersjournals.com/content/erj/50/4/1700391/F1.large.jpg?width=800&height=600&carousel=1)

###### Figure 2: This diagram shows the process of precision medicine. In the deep phenotyping stage, data are gathered and forwarded to tracks 1-3. In track 1, data are preprocessed and explored for previously unknown structure with data mining techniques, such as clustering analysis to derive subgroup of samples. This step also composes of denoise and baseline correction and variable selection. Track 2 forecasts clinically relevant outcome as the model after number of feedback loops. Track 3 predicts treatment response and generates further knowledge about the treatment. This step also utilizes feedback to patient phenotyping results. Results from track 1-3 are fed back to deep phenotyping stage for subsequent assessments. 

## 2. Deep Phenotyping<a name="2"></a>

### 1) Importance of Phenotype<a name="21"></a>

The word phenotype can be used differently in biology versus medicine. In biology, ‘phenotype’ is collection of observable physical properties of an organism, including the organism's appearance, development, behavior, and even characteristics such as gene expression profiles in response to environmental cues. In medical context, however, ‘phenotype’ is deviation from normal morphology, physiology, or behavior. When physician makes note of patient’s phenotype, the physician is doing so by taking medical history, performing physical examination, diagnostic imaging, blood tests, and other psychological tests.

This is where precise phenotype information comes into play. As physician makes note of patient’s phenotypes, the physician is making a diagnosis for the patient’s disease – making a hypothesis of what it may or may not be and provides treatment which may or may not work. Making a diagnosis, therefore, is perhaps the most important task in treating a disease, but it is the most challenging task especially for the cases of rare diseases of which 8000 diseases are yet to be classified. Today, major clinical problems arise from delayed or inaccurate diagnosis, treatment and unnecessary procedures that result in patients’ psychological burdens and unnecessary expenses. To prevent complications and set forth effective treatments from making correct prognosis, full spectrum of phenotypic abnormalities is absolutely critical for improving care quality while reducing the need for unnecessary diagnostic testing and therapies. Figure 3 shows importance of phenotype and its molecular network underpinning. Even with the same endophenotype, risk varies between individuals, because their phenotype ultimately varies in the molecular level. 

![f3](https://www.ahajournals.org/cms/asset/7d41d41d-df72-4af2-ae28-a3d97454ab16/1302fig05.gif)

##### Figure 3: Individuals with the same endophenotype, such as hypertension, can have different molecular phenotypes – resulting in different risk levels. Molecular phenotyping determines patients have different treatment responses as well.

### 2) Why "Deep" Phenotyping?<a name="22"></a>

The major problem with current phenotyping regime is sloppy or imprecise descriptions of phenotypic descriptions in medical publications. For instance, “still walking after 25 years of onset” is definitely a phenotypic description, yet it is unclear what the physician observed in the patient as such descriptions are likely to evoke different ideas for different readers depending on personal experience and imagination. Furthermore, the current gene mutation database has very little to no phenotypic information. Other than the fact that the patient has that mutagen. While this information is indeed important for determining pathogenicity, it is devoid of natural history of the disease – which is very important clinically in understanding the spectrum of complications with the disease, or genotype-phenotype correlations. Deep phenotyping offers solutions for current challenges, including semantics and technical standards for phenotype and disease data. Deep phenotyping is defined as precise and comprehensive analysis of phenotypic abnormalities in which individual components of individual components of the phenotype are observed and described. Figure 4 shows precision medicine approach to phenotyping; even the individuals with same endophenotype may are biologically distinct and encompass different disease profiles. 

![f4](https://www.ahajournals.org/cms/asset/2e0cefe8-d12c-4959-bc13-b509a92e2a34/1302fig01.gif)

##### Figure 4: Individuals undergo deep phenotyping process with data analysis performed using network analysis. This is deep phenotyping, because individuals are classified beyond their endophenotypes. Such methodology optimizes identification of biomarkers, clinical trials, and prognostication of disease.

### 3) Processing Deep Phenotyping Data<a name="23"></a>

Conversion of deep phenotyping data into tangible therapeutic utility poses number of challenges yet to be solved. First, computational environments for analysis of high dimensional data is required. Second, there must be data from large populations of patients as a knowledge network. The most important, however, is the integration of the two. For example, next-Generation sequencing enables genome-wide investigation of rare genetic variants, but associating these with diseases requires tailored statical tools that summarize the information of neighbored variants. Indeed, the integration of two types of different information are critical in generating the data in clinically relevant way. To clarify this, the structure of the precision medicine process offers tracks 1-3, which are handling of the data for better prediction of drug sensitivity. 

## 3. Data Analysis<a name="3"></a>
### 1)
### 2)
### 3) Predicting Treatment Response<a name="33"></a>

After developing diagnostic and prognostic models from the previous step, there is a need for assessing variables that define a novel taxonomy with their relevance in predicting treatment response. There are two strategies to develop models that predict treatment response.

- Prediction models can be built on the diagnostic and prognostic models from the previous stage as prognostic factors may act as the natural variables to consider when developing prediction models. For instance, epidermal growth factor receptor tyrosine kinase status acts as a prognostic factor for survival in patients with non-small cell lung cancer and a predictive factor for response to the tyrosine kinase inhibitor gefitinib as first-line treatment at the same time [Riley RD(will change later after sorting&numbering sources].

- The data can be directly utilized to extract significant information relevant to the prediction of the disease. For instance, in the first clinical trials that used the monoclonal anti-IL-5 antibody mepolizumab for asthma treatment, the use of mepolizumab was associated with a significant reduction blood and sputum eosinophils but did not have significant clinical benefit in asthma patients [Flood-Page]. Consequently, in the following trials, patients with refractory eosinophilic asthma were selected and in this subgroup, mepolizumab therapy added significant clinical benefit in patients by reducing exacerbations and improving asthma quality of life scores [Haldar P].

![groups](https://mh1042yko1f3sh26m19pxzy1-wpengine.netdna-ssl.com/wp-content/uploads/2018/02/Precision-medicine.jpg)
##### Figure 5: The figure above is an illustration of applying different treatments, also known as "tailored medicine", to categorized groups to increase the effectiveness of treatment based on a prediction model.

This process of building prediction models involves generating further knowledge about the disease and treatment from the diagnotics and prognostics models or the data itself. The findings from this process, in the form of data, would be fed back to the phenotyping of patients to further adjust the clinical trial that could more precisely show the effectiveness of the treatment. 

In addition to the feedback, dissemination and communication of the taxonomy and models with the clinical and scientific communities, for instance, to provide utilizable algorithms for clinical practices.

## 4. Evolving Precision Medicine<a name="4"></a>

##### Figure 6: The figure below shows repeated cycles of precision medicine and its subsequent outcome.
![evol](https://erj.ersjournals.com/content/erj/50/4/1700391/F2.large.jpg)

As seen in the figure, the cycle of patients assessment(deep phenotyping), data processing(preprocessing and data mining), and model building(diagnotic, prognostic, and prediction model building) is repeated at least several times to further increase the preciseness of the medicine by categorizing patient groups at a higher resolution. 

The detailed steps are as follows:

1. In the first cycles, patients are categorized into diagnostic/prognostic groups based on obvious characteristics.
2. In later cycles, more specific groups of patients are defined using more in-depth data that was obtained from the previous cycle as the data from each cycle is fed back to the next cycle of patient assessment. 
3. Eventually, these feedback loops may allow the final cycles to target individual patients with specific data profiles.

## 5. Conclusion<a name="5"></a>

In this paper, the process of precision medicine, starting from the deep phenotyping stage to data analysis part, which comprised preprocessing, data mining, developing diagnostic, prognostic, and prediction models, were discussed against the background of airway diseases. As seen in the previous section on the continual evolution of precision medicine with repeated cycle of the above steps, precision medicine should be viewed as the continuous process of feedback loops rather than a steady-state with an end-point or a specific output from the research. In this context, tailored or stratified medicine resulting from new stratifications can be considered as a makeshift product of the process that will generate new data for the next cycle, thus further increasing the precision. 

Once again, the ultimate goal of precision medicine is the most effective treatment for the individual patient. To step closer to this goal, ongoing endeavors to be even more precise and individualistic, newly-gained scientific and clinical knowledge, and new data sources would be necessary.

## 6. References<a name="6"></a>
Inke R. König, Oliver Fuchs, Gesine Hansen, Erika von Mutius, Matthias V. Kopp
European Respiratory Journal Oct 2017, 50 (4) 1700391; DOI: 10.1183/13993003.00391-2017 

Ginsburg GS, Phillips KA. Precision Medicine: From Science To Value. Health Aff (Millwood). 2018 May;37(5):694-701. doi: 10.1377/hlthaff.2017.1624. PMID: 29733705; PMCID: PMC5989714.

Robinson PN. Deep phenotyping for precision medicine. Hum Mutat. 2012 May;33(5):777-80. doi: 10.1002/humu.22080. PMID: 22504886.

National Research Council, Committee on A Framework for Developing a New Taxonomy of Disease. Toward Precision Medicine: Building a Knowledge Network for Biomedical Research and a New Taxonomy of Disease. National Academies Press; Washington DC: 2011.

Leopold JA, Loscalzo J. Emerging Role of Precision Medicine in Cardiovascular Disease. Circ Res. 2018;122(9):1302-1315. doi:10.1161/CIRCRESAHA.117.310782

Riley RD, Hayden JA, Steyerberg EW, et al. Prognosis Research Strategy (PROGRESS) 2: prognostic factor research. PLoS Med 2013; 10: e1001380.

Flood-Page P, Swenson C, Faiferman I, et al. A study to evaluate safety and efficacy of mepolizumab in patients with moderate persistent asthma. Am J Respir Crit Care Med 2007; 176: 1062–1071.

Haldar P, Brightling CE, Hargadon B, et al. Mepolizumab and exacerbations of refractory eosinophilic asthma. N Engl J Med 2009; 360: 973–984.

the image- might not use-- “What Is Precision Medicine and How Can It Help Fix Healthcare.” ReferralMD, ReferralMD, 11 Dec. 2018, getreferralmd.com/2018/02/precision-medicine-can-help-fix-healthcare/. 
https://getreferralmd.com/2018/02/precision-medicine-can-help-fix-healthcare/
