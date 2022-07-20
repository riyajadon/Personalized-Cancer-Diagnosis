# Personalized-Cancer-Diagnosis
## Business problem
The objective of this project is to classify given genetic variations/mutations data based on evidence from text based literature.

## Dataset
Memorial Sloan Kettering Cancer Center (MSKCC)
Download training_variants.zip and training_text.zip from Kaggle.
Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/

Fields are

ID : the id of the row used to link the mutation to the clinical evidence
Gene : the gene where this genetic mutation is located
Variation : the aminoacid change for this mutations
Class : 1-9 the class this genetic mutation has been classified on

## Type of Machine Learning Problem
There are nine different classes a genetic mutation can be classified into => Multi class classification problem.

## Performance Metric
Multi class log-loss
Confusion matrix

