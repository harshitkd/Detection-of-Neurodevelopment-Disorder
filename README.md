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

| Techniques  | Accuracy | Precision | Sensitivity | F-beta score | F1 score | 
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 1 | 1 | 1 | 1 | 1 |
| Decision Tree | 1 | 1 | 1 | 1 | 1 |
| K-Nearest Neighbor | 0.96 | 0.933 | 1 | 0.94594 | 0.966551 |
| Naive Bayes | 0.86 | 0.838 | 0.928 | 0.85526 | 0.8813 |
| Sequential Model (CNN) | 0.959 | 0.964 | 0.964 | 0.964 | 0.964 |


### Adult Dataset:

| Techniques  | Accuracy | Precision | Sensitivity | F-beta score | F1 score | 
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 0.9836 | 0.956 | 1 | 0.9641 | 0.97727 |
| Decision Tree | 1 | 1 | 1 | 1 | 1 |
| K-Nearest Neighbor | 0.959 | 0.9318 | 0.9534 | 0.9360 | 0.94252 |
| Naive Bayes | 0.8934 | 0.8260 | 0.8837 | 0.837 | 0.8539 |
| Sequential Model (CNN) | 0.97540 | 0.95454 | 0.9767 | 0.9589 | 0.9655 |


### Adolescent Dataset:


| Techniques  | Accuracy | Precision | Sensitivity | F-beta score | F1 score | 
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 0.9 | 0.92307 | 0.92307 | 0.92307 | 0.92307 |
| Decision Tree | 1 | 1 | 1 | 1 | 1 |
| K-Nearest Neighbor | 0.75 | 0.7222 | 1 | 0.7647 | 0.8387 |
| Naive Bayes | 0.75 | 0.7222 | 1 | 0.76470 | 0.8387 |
| Sequential Model (CNN) | 0.699 | 0.8181 | 0.6923 | 0.78947 | 0.75001 |
