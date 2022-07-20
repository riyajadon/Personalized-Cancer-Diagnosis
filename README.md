# Personalized-Cancer-Diagnosis
## Business problem
The objective of this project is to classify given genetic variations/mutations data based on evidence from text based literature.

## Dataset
<br> Memorial Sloan Kettering Cancer Center (MSKCC) <br/>
<br>Download training_variants.zip and training_text.zip from Kaggle.<br/>
<br> Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/ <br/>

Following are the fields in the dataset:

<br>ID : the id of the row used to link the mutation to the clinical evidence <br/>
<br>Gene : the gene where this genetic mutation is located<br/>
<br>Variation : the aminoacid change for this mutations<br/>
<br>Class : 1-9 the class this genetic mutation has been classified on<br/>

## Type of Machine Learning Problem
There are nine different classes a genetic mutation can be classified into => Multi class classification problem.

## Performance Metric
<br>Multi class log-loss<br/>
<br>Confusion matrix<br/>

