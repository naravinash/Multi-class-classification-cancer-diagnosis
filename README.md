# Multi-Class Classification - Cancer Diagnosis

### Presentation link
https://prezi.com/view/hRPEuB0rihHZDwCUreDU/

### Introduction:
This dataset is provided by Memorial Sloan Kettering Cancer Center (MSKCC). This dataset was a part of Neural Information Processing System (NIPS) 2017. We are given sequence of thousands of genetic mutation (Mutations are small changes in the gene that can corrupt the genetic code). Considering this information we have to classify the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). Currently this interpretation of gene is done MANUALLY. This is very time consuming task where a PATHOLOGIST has to manually review and classify every single genetic mutation based on evidence from text based clinical literature.

### Data Overview:
We have two data sets :

Training_variants : This dataset has 4 columns, & 3321 rows. It contains ID,Gene code,type of variation and class labels [1-9].
Training_text : This dataset has 2 columns & 3321 rows. It contains ID,clinical evidence(text) , that pathologists use to classify mutations.
PLEASE NOTE: We are not given which class labels has Cancer or not. (https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198543)

### Objective:
Our objective is to AUTOMATE the classifications of mutations based on evidence from text based clinical literature.

