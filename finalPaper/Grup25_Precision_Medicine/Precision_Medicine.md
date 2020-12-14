
# The Process of Precision Medicine
### by Soyeon Kim, Hwayeon Lee, Meixian Wu

1. [Introduction](#1)
2. [Deep Phenotyping](#2)
3. [Data Analysis](#3)<br>
    3.1. [Preprocessing and Data Mining](#31)<br>
    3.2. [Diagnostic and Prognostic Models](#32)<br>
    3.3. [Predicting Treatment Response](#33)<br>
4. [Evolving Precision Medicine](#4)
5. [Conclusion](#5)
6. [References](#6)


## 1. Introduction<a name="1"></a>

(EDIT!) Most medical treatments are designed for the "average patient" as a one-size-fits-all-approach, which may be successful for some patients but not for others. 

#### 1) Definition of precision medicine<a name="11"></a>

![PM0](https://www.abpischools.org.uk/thumbnails/0/1151.20.jpg)

Precision medicine is personalized treatment strategies on the basis of genetic, biomarker, phenotypic or psychosocial characteristics to stratify patients into novel subpopulations that differ in their susceptibility to a particular disease or their response to a specific treatment. It is also commonly referred to as 'stratified medicine', 'targeted therapy' and 'deep phenotyping.' The focus of applied definitions is moving away from classical 'signs-and-symptoms' approach or 'population approach' into 'N of 1 approach' in which each patient is an entire trial as a single case study from N number of individuals within a population. 

## 2. Deep Phenotyping<a name="2"></a>
#### 1) Deep phenotyping as process
![dP](https://erj.ersjournals.com/content/erj/50/4/1700391/F1.large.jpg?width=800&height=600&carousel=1)
#### 2) Processing deep phenotyping data

## 3. Data Analysis<a name="3"></a>
#### 1)
#### 2)
#### 3) Predicting Treatment Response<a name="33"></a>

After developing diagnostic and prognostic models from the previous step, there is a need for assessing variables that define a novel taxonomy with their relevance in predicting treatment response. There are two strategies to develop models that predict treatment response.

- Prediction models can be built on the diagnostic and prognostic models from the previous stage as prognostic factors may act as the natural variables to consider when developing prediction models. For instance, epidermal growth factor receptor tyrosine kinase status acts as a prognostic factor for survival in patients with non-small cell lung cancer and a predictive factor for response to the tyrosine kinase inhibitor gefitinib as first-line treatment at the same time [Riley RD(will change later after sorting&numbering sources].

- The data can be directly utilized to extract significant information relevant to the prediction of the disease. For instance, in the first clinical trials that used the monoclonal anti-IL-5 antibody mepolizumab for asthma treatment, the use of mepolizumab was associated with a significant reduction blood and sputum eosinophils but did not have significant clinical benefit in asthma patients [Flood-Page]. Consequently, in the following trials, patients with refractory eosinophilic asthma were selected and in this subgroup, mepolizumab therapy added significant clinical benefit in patients by reducing exacerbations and improving asthma quality of life scores [Haldar P].

Below is an illustration of applying different treatments, also known as "tailored medicine", to categorized groups to increase the efficiency of treatment based on a prediction model.

![groups](https://mh1042yko1f3sh26m19pxzy1-wpengine.netdna-ssl.com/wp-content/uploads/2018/02/Precision-medicine.jpg)

This process of building prediction models involves generating further knowledge about the disease and treatment from the diagnotics and prognostics models or the data itself. The findings from this process, in the form of data, would be fed back to the phenotyping of patients to further adjusted for the clinical trial that could more precisely show the effectiveness of the treatment. 

In addition to the feedback, dissemination and communication of the taxonomy and models with the clinical and scientific communities, for instance, to provide utilizable algorithms for clinical practices.

## 4. Evolving Precision Medicine<a name="4"></a>

The figure below shows cycles of precision medicine and its subsequent outcome.

![evol](https://erj.ersjournals.com/content/erj/50/4/1700391/F2.large.jpg)

As seen in the figure, the cycle of patients assessment(deep phenotyping), data processing(preprocessing and data mining), and model building(diagnotic, prognostic, and prediction model building) is repeated at least several times to further increase the preciseness of the medicine by categorizing patient groups at a higher resolution. 

The detailed steps are as follows:

1. In the first cycles, patients are categorized into diagnostic/prognostic groups based on obvious characteristics.
2. In later cycles, more specific groups of patients are defined using more in-depth data that was obtained from the previous cycle as the data from each cycle is fed back to the next cycle of patient assessment. 
3. Eventually, these feedback loops may allow the final cycles to target individual patients with specific data profiles.

## 5. Conclusion<a name="5"></a>

In this paper, the process of precision medicine, starting from the deep phenotyping stage to data analysis part, which comprised preprocessing, data mining, developing diagnostic, prognostic, and prediction models, were discussed (against the background of airway diseases-remove this part if we don't discuss the asthma example). As seen in the previous section on the continual evolution of precision medicine with repeated cycle of the above steps, precision medicine should be viewed as the continuous process of feedback loops rather than a steady-state with an end-point or a specific output from the research. In this context, tailored or stratified medicine resulting from new stratifications can be considered as a makeshift product of the process that will generate new data for the next cycle, thus further increasing the precision. 

Once again, the ultimate goal of precision medicine is the most effective treatment for the individual patient. To step closer to this goal, ongoing efforts to be even more precise and individualistic, newly-gained scientific and clinical knowledge, and new data sources would be necessary.

## 6. References<a name="6"></a>

Riley RD, Hayden JA, Steyerberg EW, et al. Prognosis Research Strategy (PROGRESS) 2: prognostic factor research. PLoS Med 2013; 10: e1001380.

Flood-Page P, Swenson C, Faiferman I, et al. A study to evaluate safety and efficacy of mepolizumab in patients with moderate persistent asthma. Am J Respir Crit Care Med 2007; 176: 1062–1071.

Haldar P, Brightling CE, Hargadon B, et al. Mepolizumab and exacerbations of refractory eosinophilic asthma. N Engl J Med 2009; 360: 973–984.

Inke R. König, Oliver Fuchs, Gesine Hansen, Erika von Mutius, Matthias V. Kopp
European Respiratory Journal Oct 2017, 50 (4) 1700391; DOI: 10.1183/13993003.00391-2017

the image-- “What Is Precision Medicine and How Can It Help Fix Healthcare.” ReferralMD, ReferralMD, 11 Dec. 2018, getreferralmd.com/2018/02/precision-medicine-can-help-fix-healthcare/. 
https://getreferralmd.com/2018/02/precision-medicine-can-help-fix-healthcare/

National Research Council, Committee on A Framework for Developing a New Taxonomy of Disease. Toward Precision Medicine: Building a Knowledge Network for Biomedical Research and a New Taxonomy of Disease. National Academies Press; Washington DC: 2011.
