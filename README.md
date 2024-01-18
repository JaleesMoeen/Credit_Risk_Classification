# Credit_Risk_Classification
 About Credit risk poses a classification problem that’s inherently imbalanced. Using a dataset of historical lending activity from a peer-to-peer lending services company, build a model that can identify the creditworthiness of borrowers.

## Overview of the Analysis

The purpose of this analysis is to build a predictive model for assessing the credit risk associated with loan applications. The objective is to enhance the accuracy of identifying high-risk loans (Class 1) while maintaining a high precision for healthy loans (Class 0). By achieving a well-balanced model, financial institutions can make more informed lending decisions, minimizing the risk of default and optimizing their loan approval process.


![Alt text](images/1_creditrisk.jpg)


### Financial Information 

The dataset contains financial information related to loan applicants, including features such as credit score, income, debt-to-income ratio, and other relevant factors. The target variable is a binary label indicating whether a loan is considered high-risk (1) or healthy (0).


### Target Variable

The provided value_counts indicates the distribution of the target variable 'loan_status' in the dataset:
0    75036
1     2500


### Stages of Machine Learning Process 

Split the data into features(X) and labels(y).

Split the Data into Training and Testing Sets

Create a logistic regression model with the original data amd resampled data.

Predict a logistic regression model  with orignal and resampled training Data.

Evaluate the model’s performance by accuracy score, confusion matrix and classification report for both the orignal and resampled data.

Observation analysis from the evaluation reports.


### Method Used

These methods collectively address the challenge of imbalanced data by employing resampling techniques and leveraging logistic regression models. 

Resampling ensures a more equitable representation of both classes during model training, leading to more balanced predictions and potentially improving the model's ability to identify high-risk loans. 

The choice of logistic regression as the modeling algorithm provides a balance between interpretability and predictive power.




