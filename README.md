# ML-binary-classification

Radiomics analysis of PET/CT findings with fludeoxyglucose (18F) as a biomarker in the differentiation of spondylodiscitis and bone metastasis in patients with focal lesions in the spine

Introduction:
Early initiation of targeted treatment can prevent possible irreversible neurological complications of spondylodiscitis (SD) and/or spinal metastases (MET), but differentiation may be a diagnostic problem, especially in the early stages.

The aim:
Identify the radiometric characteristics of PET with FDG helping to distinguish SD and MET.

Method:
Retrospective analysis of 31 second- and higher-order radiometric features in 60 patients with confirmed SD (n = 30) and MET of various malignancies (n = 30). A total of 40 SD findings and 40 MET findings were analyzed using LIFEx freeware, which allows the calculation of conventional, textural and shape elements of diagnostic images.
The clinical characteristics of the patients (non-parametric Wilcoxon rank sum test) were compared using the statistical software RStudio and their acceptable diagnostic accuracy was tested using the ROC curve. Furthermore, the predictive ability to distinguish SD and MET was tested using machine learning, where three methods were tested (multiple logistic regression, random forest and support vector machines), with three different ways of selecting training and test data (K-fold cross-validation, Leave- One-Out Cross-Validation, Train test split).

The results:
When SD and MET were distinguished, 24/31 radiometric elements were confirmed as statistically significant (p <.05) and in 9/24 the AUC was> 80% for diagnostic accuracy. The highest values were reached by the parameters GLZLM_ZP (cut-off = 0.38, AUC = 83.25%), NGLDM_Contrast (cut-off = 0.17, AUC = 84.7%) and GLRLM_GLNU (cut-off = 46.1, AUC = 88.8%). In machine learning, the most effective method was Random Forest (cut-off = 0.28, AUC = 98.61%) with the method of data selection Train test split.

Conclusion:
The results confirm radiomatic analysis and machine learning as a possible direction in distinguishing SD and MET in PET / CT with FDG and support their further validation. 
