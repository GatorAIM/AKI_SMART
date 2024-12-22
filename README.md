# SMART: A New Patient Similarity Estimation Framework for Enhanced Predictive Modeling in Acute Kidney Injury
## Abstract:
Measuring patient similarity is crucial for precision medicine, facilitating predictive modeling, disease subtyping, and personalized treatments by stratifying patients into clinically meaningful subgroups based on high-dimensional data. This study aims to develop an electronic health record (EHR)-based patient similarity estimation framework to enhance predictive modeling.  

The proposed framework, SMART (Similarity Measurement and Analysis for Risk Tracking), introduces three key enhancements: (1) adjusting patient similarity by overlap rate weighting (OW); (2) distance measure optimization (DO); and (3) feature type weight optimization (FO). These enhancements were evaluated across varying cohort sizes through internal and external validations using data from two tertiary academic hospitals to predict acute kidney injury (AKI).  

## Notebook Description:
01_Data_Preprocessing: Processing of the patient pool and internal test set data.  
02_Overlap_Rates: Computing SCr and lab overlap rates.  
03_Main_Experiments: Three key enhancements were performed: OW, DO, and FO. We analyzed the impact of each enhancement separately. The missing data imputation methods were linear interpolation (for SCr) and MICE (for lab data).  
04_Subgroup_Analysis: We analyzed the final model performance in each sub-population.  
05_Sensitivity_Analysis: We varied two key hyperparameters for computing overlap rates and analyzed the impact on model performance for a single feature.  
06_External_Validation: Processing of the external test set and evaluation of model performance on it.  
07_Other_Imputation_1: Median imputation was used as the missing data imputation method.  
08_Other_Imputation_2: Mean imputation was used as the missing data imputation method.  
09_Other_Imputation_3: KNN imputation was used as the missing data imputation method.  
10_Supplementary_Info: Supplementary information was visualized through plots.
