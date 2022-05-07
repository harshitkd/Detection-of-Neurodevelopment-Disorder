# Detection-of-Neuroatypical-Disorder

Links

Autism Spectrum

1) https://www.irjet.net/archives/V8/i8/IRJET-V8I8174.pdf
2) https://github.com/saadhaxxan/Autism-spectrum-disorder-Detection-using-Deep-Learning
3) https://www.researchgate.net/publication/331315353_A_Machine_Learning_Approach_to_Predict_Autism_Spectrum_Disorder
4) https://link.springer.com/article/10.1007/s40489-019-00158-x
5) https://github.com/martinfrasch/ASD_project
6) https://www.sciencedirect.com/science/article/pii/S1877050920308656
7) https://github.com/kbasu2016/Autism-Detection-in-Adults/blob/master/capstone.ipynb
8) https://github.com/deeptiGarg/Classification-on-Autism-Dataset
9) Dataset: https://archive.ics.uci.edu/ml/datasets.php
10) Alternative Dataset: https://www.kaggle.com/faizunnabi/autism-screening



## Feature Exploration

| Features  | Adolescent Dataset | Adult Dataset | Child Dataset |
| ------------- | ------------- | ------------- | ------------- |
| Total number of records  | 104 | 704 | 292 |
| Patients diagnoised with disorder | 63 | 189 | 141 |
| Patients not diagnoised with disorder | 41 | 515 | 151 |
| Percentage of patients diagnoised with disorder | 60.58 % | 26.85 % | 48.29 % |


## ASD class dataset visualization

### Child dataset: 
![child asd classes](https://user-images.githubusercontent.com/56076028/167248574-f0bf8c93-2770-4ad7-9ccf-1afae6e74345.jpg)
### Adult Dataset:
![adult asd classes](https://user-images.githubusercontent.com/56076028/167248587-b953d8c8-f43a-4a96-9891-d49d68d85809.jpg)
### Adolescent Dataset:
![adolescent asd classes](https://user-images.githubusercontent.com/56076028/167248603-fd8eb39f-d8ae-4ad4-aa9b-2cdf5c2780e1.jpg)


## Accuracy, AUC score, cross validation and F-beta score comparison

### Child Dataset:

| Techniques  | Accuracy | Cross Validation | AUC score | F-beta score |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 1 | 0.98783 | 0.99935 | 0.94594 |
| Decision Tree | 1 | 1 | 1 | 1 |
| K-Nearest Neighbor | 0.96 | 0.875 | 0.96188 | 0.94594 |
| Naive Bayes | 0.86 | 0.7986 | 0.88082 | 0.85526 |

Accuracy in Sequential Model (CNN) is 95.99 %.


### Adult Dataset:

| Techniques  | Accuracy | Cross Validation | AUC score | F-beta score |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 0.9836 | 0.99344 | 1.0 | 0.96412 |
| Decision Tree | 1 | 1 | 1 | 1 |
| K-Nearest Neighbor | 0.95901 | 0.94745 | 0.99307 | 0.93607 |
| Naive Bayes | 0.89344 | 0.885 | 0.9445 | 0.837 |


Accuracy in Sequential Model (CNN) is 97.54 %



### Adolescent Dataset:

| Techniques  | Accuracy | Cross Validation | AUC score | F-beta score |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 0.9 | 0.9255 | 0.98412 | 0.92307 |
| Decision Tree | 0.9 | 1 | 1 | 1 |
| K-Nearest Neighbor | 0.75 | 0.80555 | 0.89265 | 0.764705 |
| Naive Bayes | 0.75 | 0.7222 | 0.77777 | 0.764705 |


Accuracy in Sequential Model (CNN) is 75 %
