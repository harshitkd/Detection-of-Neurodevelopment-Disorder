# Detection-of-Neuroatypical-Disorder


## Feature Exploration

| Features  | Adolescent Dataset | Adult Dataset | Child Dataset |
| ------------- | ------------- | ------------- | ------------- |
| Total number of records  | 104 | 704 | 292 |
| Patients diagnoised with disorder | 63 | 189 | 141 |
| Patients not diagnoised with disorder | 41 | 515 | 151 |
| Percentage of patients diagnoised with disorder | 60.58 % | 26.85 % | 48.29 % |

## Data Preprocessing

* Handle the missing values
* Split the data into features and target label
* Normalize the numerical variables using MinMax Scaler
* One-hot encoding for categorical variables
* Encoded the asd_classes column

## Encoded ASD class dataset visualization

### Child dataset: 
![child asd classes](https://user-images.githubusercontent.com/56076028/167248574-f0bf8c93-2770-4ad7-9ccf-1afae6e74345.jpg)
### Adult Dataset:
![adult asd classes](https://user-images.githubusercontent.com/56076028/167248587-b953d8c8-f43a-4a96-9891-d49d68d85809.jpg)
### Adolescent Dataset:
![adolescent asd classes](https://user-images.githubusercontent.com/56076028/167248603-fd8eb39f-d8ae-4ad4-aa9b-2cdf5c2780e1.jpg)

## Machine Learning Techniques

* Logistic Regression
* Decision Tree
* K-Nearest Neighbor
* Naive Bayes
* Sequential Model (CNN)

## Accuracy, AUC score, cross validation and F-beta score comparison

### Child Dataset:

| Techniques  | Accuracy | Precision | Sensitivity | F-beta score | F1 score | 
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 0.98783 | 0.966 | 0.95 | 0.95 | 0.95 |
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


## Confusion Matrix and Learning curves

### Child Dataset:

![Screenshot 2022-05-09 214718](https://user-images.githubusercontent.com/56076028/167481393-38c5f154-7226-426d-add8-128d20e85340.png)
![Screenshot 2022-05-09 214810](https://user-images.githubusercontent.com/56076028/167481383-d45d95a9-49a9-4ce0-9c50-8dba06cf099d.png)


### Adult Dataset:

![Screenshot 2022-05-09 215255](https://user-images.githubusercontent.com/56076028/167481470-546330f0-0413-40c6-8d59-f1779a5e50fb.png)
![Screenshot 2022-05-09 215349](https://user-images.githubusercontent.com/56076028/167481547-d3705884-7920-42ca-b45f-92ab8c6ee420.png)

### Adolescent Dataset:

![Screenshot 2022-05-09 215528](https://user-images.githubusercontent.com/56076028/167481596-0f130ca3-0703-41cf-9193-f71fb6a1e2b5.png)
![Screenshot 2022-05-09 215602](https://user-images.githubusercontent.com/56076028/167481589-15b0b106-0a28-43f3-8178-b40cb975bddc.png)

## License
The detection project is free and open-source software licensed under the Apache-2.0 license.
