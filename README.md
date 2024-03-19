# Liver Cirrhosis Survival Prediction 
 
## About Dataset 
This dataset consists of 17 clinical features used to predict the survival state of patients with liver cirrhosis. The survival states are categorized as follows:  
- 0 = D (death) 
- 1 = C (censored) 
- 2 = CL (censored due to liver transplantation) 
 
## Dataset Creation Purpose 
The dataset was created to predict survival outcomes in patients with cirrhosis, a condition resulting from prolonged liver damage leading to extensive scarring, often caused by factors such as hepatitis or chronic alcohol consumption. The data originates from a Mayo Clinic study on primary biliary cirrhosis (PBC) conducted between 1974 and 1984. 
 
## Dataset Funding 
The creation of this dataset was funded by the Mayo Clinic. 
 
## Dataset Information 
- **Instances**: People 
- **Sensitive Data**: Gender, Age 
- **Data Preprocessing**: 
  - Rows with missing values (NA) in the Drug column were dropped. 
  - Missing values were imputed with mean results. 
  - One-hot encoding was applied to all categorical attributes. 
 
## Additional Details 
Between 1974 and 1984, 424 PBC patients referred to the Mayo Clinic were eligible for a randomized placebo-controlled trial testing the drug D-penicillamine. Out of these, 312 patients participated in the trial, providing comprehensive data. The remaining 112 patients did not partake in the clinical trial but agreed to record basic metrics and undergo survival tracking. Six of these patients were lost to follow-up post-diagnosis, leaving data for 106 individuals in addition to the 312 trial participants.
