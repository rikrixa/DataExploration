## Programming assignment for Computational Omics | Huang lab at ISMMS ##

* Contact: Kuan-lin Huang @ Icahn School of Medicine at Mount Sinai
* kuan-lin.huang@mssm.edu

## Background ##
Immune checkpoint inhibitors (ICIs) have dramatically transformed the treatment landscape of advanced cancers. For some patients, these agents extend life and provide durable benefits. However, the majority of patients do not benefit from ICIs; response rates in clinical trials range from 10-50%, and a significant fraction of patients suffer from immune-related adverse events. There is an urgent need for reliable predictors to better select patients for ICI therapy.

In this coding assignment, we will identify genes whose mutations may be associated with better or worse outcomes in cancer patients treated with immunotherapy. 

## About the data ## 
0. The data table contains genetic, clinical, and survival information of a cohort of 1.6K patients treated with ICI. Reference publication where the cleaned dataset is derived from is here: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6365097/
1. Each row is a patient with a unique ID and tumour sequencing barcode, each column is a variable, the data table begins with each sequenced gene where 0 stands for no-mutation and 1 stands for mutation carrier 
2. OS: overall survival
3. Stratefy the analyses/modelling by CANCER_TYPE 
4. Make sure you correct for/consider the other relevant clinical variables TMB_SCORE	SEX	AGE_GROUP	DRUG_TYPE SAMPLE_TYPE

## Key questions for you to answer ##
# Please note some questions may be a bit open-ended and you may run out of time to address them fully. Please feel free to fit solving the assignment into your week, but do not spend over 2 working days in hours on it. # 
#We'd like to access how you think about these problems, break them down into pieces, tackle them with reasonable approaches, and interpret the results putting them into biomedical contexts. If you do not have complete answers to all of them it is okay. Feel free to leverage existing tool/algorithms or develop your own as you see suitable. If you find fit, you can choose and attack questions that you are most interested in. #
0. Quick exploratory analyses of data quality. 

1. Which genes' mutation statuses are significantly associated with/predictive of patient survival outcomes? Note: Adverse or benefitial survival outcomes. How do the genes' function possibly relate to immunotherapy response. 

2. Please build a machine learning model thaet predicts patient survival outcomes based on their relevant clinical variables (TMB_SCORE	SEX	AGE_GROUP	DRUG_TYPE SAMPLE_TYPE) and gene mutation status. Note: Model performance. Feature importance. And how the model predicts outcome. etc. 

3. [Bonus; if you have time] How do the predictors/models compare across cancer types? Are there interactions between the predictors? Anything else you explored? 

4. Technical question: 1) How and why do you choose the specific statistical model or ML algorithm in your analyses? 2) How and why did you define the function or class the way you coded them? 

5. Presentation: imagine you are working on for a conference submission due in two days for a 1-2 page summary of result and figure. Please highlight your key methods and findings in this two-page document, with additional methods and figures in Supplement (if applicable). 

