Structure

1. Introduction
---------------
Cancer cases around the world and its cost.
Brief description of what is cancer and its effects on health.
What is breast cancer and how many cases/deaths around the world.
  FIGURE. World map of breast canrer incidence rates.
Detail on the heterogeneity of breast cancer.
Known causes of breast cancer, and importance of prompt detection.
Detection with mammography. What's this technique.
Current challenges in screening mammography.
Current approaches to solve these challenges and accomplishments.
  FIGURE. Diagram relating clinical to techniques
Highlight the opportunity to improve, and use high-tech approaches
Point towards the interest in imaging biomarkers. What are them.
What are imaging phenotypes and their potential applications.
Establish the principal hypothesis.
Establish the primary objective of the dissertation
Establish the secondary objectives
Brief mention of the research problems addressed.
Claim the impact of this research and its contributions to the SoA.


2. Relevant literature
----------------------
Anatomy of the breast
Breast cancer, aberrant breast tissue with different properties.
Types of breast cancer in clinic (Lobular, Ductal, others)
ICH types of breast cancer
Molecular subtypes of breast cancer

X ray imaging and its application to breast (mammography)
Characteristics of the normal breast in mammograms
Characteristics of the different types of breast cancer in mammo
State of the art in CADe and CADx for mammograms
Examples that highlight the challenges in current approaches.
Other modalities (MR) and their approach for BC research.
Highlight the coverage of mammo, and its potential benefit

What is image processing
Image enhancement and techniques
Image segmentation and techniques
Image transforms and relevant techniques
Image characterization and types of features

What is machine learning
Feature selection
Classification methods
Assessment of classification performance
Regression methods
Assessment of regression methods
Implications and corrections for n>>p and multiple comparisons


3. Results
------------
Mammogram database
SPIE
Minkowksi
Subtypes radiology

4. Discussion
--------------

THE RESULTS SHOW A PLAUSIBLE RELATION BREAST CANCER - IMAGES
In the previous chapters, the author presented three experiments to demonstrate the association between mammogrphic features and clinical endpoints of breast cancer. The first experiment showed that images are correlated with the actionable levels of the BIRADS lexicon: to recomend no action or to recomend additional examinations, which in turn are associated with the risk of breast cancer. The second experiment contributes with the design of a set of novel image features that capture texture information, and are shown to be associated with the presence of breast cancer in mammograms. The third experiment is more ambitious and establishes a correlation between image features obtaines from manually-segmented tumors and knwon cancer-related genes, and the molecular subtype of the tumor. With these three arguements as supporting evidence, it can be confirmed that it exists a measurable correlation between quantitative features of mammograms and multiple clinical endpoints of cancer. 



tHE RESULTS ARE CONSISTENT WITH OTHER EXPERIMENTS WITH MAMMOGRAMS AND OTHER IMAGING MODALITIES
In general, the results obtained are consistent with the conclusions from other experiments. The most important consistent factor observed with others' works is the importance of feature-based features in the characterization of breast cancer in mammograms. In the three experiments, texture features played a role in the classification and assessment of the clinical endpoints. The features are not the same than those in other studies, and that can be explained by differences in the implementation, but most importantly by the conceptual similarity among multiple texture features that can cause confusion in feature selection algorithms. It is of special interest the fact that the spatial resolution of the texture features play a role in the relevance of the feature, but don't seem to be strongly correlated with visual characteristics of the affected breast mammograms. This finding, which has also been observed in other studies, suggest that computational analysis of images can yield increased information beyond what the semi-trained eye can conceptualize from a mammogram, and opens the possibility to use a computer-based approach to develop products that act beyond a lesion detection aid.



tHERE IS SIGNIFICANT CHALLENGE IN OBTAINING PAIRED SAMPLES OF IMAGE + BIO SAMPLES
Machine learning algorithms require large amounts of training data in order to provide robust results in real life applications. The problem addressed in this dissertation has been historically considered as difficult in this matter given the variablity in breast appearance in mammograms, requiring very big samples in order to take into consideration and reduce some anatomic confounding effects. The recollection of a large sample of patients was a challenge for the developoment of this dissertation. Even with institutional collaboration, multiple factors had a negative impact in the ability to collect samples. The most important was the organizational structure of the Breast Imaging center, which is owned by the University, but only provides the imaging services sometimes even without having any additional information about the treating physician, which is the one in power of the required clinical information of the patient. To overcome this barrier, we had to associate with a physisican with interest in the project, and then limit our recruitment to those patients that were referred by him and also had their mammogram acquisition performed in the Breast Imaging center. The result of this workflow was a reduced volume of patients for the experiment that required paired image, clinical and biological information.

In order to aminorate this challenge, the author would suggest the following recommendations towards the creation of an institutional policy for aquisition of clinical data in intitutional healthcare facilities.
1) Publication of an updated directory of physicians affiliated to the School of Medicine, with their contact information and field of interest.
2) Enable access to electronic medical records of patients recruited for clinical research, enforcing the utlization of credentials and keys for patient names.
3) Establishment of general standardized guidelines for the publication of research works using data obtained from the institution.
4) Train clinical personel in their role in the research workflow 
5) Promote the involvement of external physicians with institutional research projects



nOVEL METHODS TO CHARACTERIZE PARENCHYMAL TEXTURE SEEM TO HAVE THE GREATEST POTENTIAL ABOVE SHAPE AND SIGNAL DISTRIBUTION FEATURES.
During the last five years, there has been great advance in the fields of distributed computing and cluster processing. Image processing has been soon benefited from such developments given that several algorithms can be parallelized reducing the time required to process an image. The processig pipeline used in the experiments shown in this dissertation took from 30 seconds to near 10 minutes per image to complete. Similar algorithms optimized to run in parallel instances have achieved reductions of at least on aorder of magnitude [REF], suggesting that in the near future real-time image processing could be achieved in a research and probably clinical environment. As the processing time is reduced, the possibility to perform a deeper exploration of texture features at multpliple spatial resolution levels would become plausible, and would likely provide valuable information about the intrincate textures present as tumorigenesis starts.



Triaging methods based on quantitative analysis can be one key to reduce breast cancer mortality in developing countries with access to technology and infrastructure.
There's the challenge to characterize response to treatment with quantitative image analysis, or the combination of other risk models with images, the evolution of features with time in the same patient

Threats to this approach include heterogeneity of devices, modification of clinical guidelines, selection of operation point, heterogeneity of method implementations. 

This method has some advantages such as
 - no manual segmentation (for first two)

And some disadvantages
 - no breast registration, thus not easy to track
 - no in depth adjustment for other confounding factors
 - doesnt incorporate features found by others



5. Conclusions
--------------
In the previous chapters, the author presented three experiments in which the association between quantitative features of mammograms, and clinical endpoints of breast cancer. In all of them, a significant degree of association was established for certain combinations of features. 
These results are consistent with other reports of similar experiments with large number of image features, which further support the findings of this work
This method has some advantages such as
 - no manual segmentation (for first two)






