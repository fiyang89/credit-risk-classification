# Credit Risk Classification 
## Supervised Machine Learning

### Background
In this challenge, you'll use various techniques to train and evaluate a model based on loan risk. You'll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

### Instructions
1. Split the Data into Training and Testing Sets.
2. Create a Logistic Regression Model with the Original Data.
3. Predict a Logistic Regression Model with Resampled Training Data.
4. Write a Credit Risk Analysis Report.

### Analysis Report
- Overview: Explain the purpose of this analysis
  1. The purpose of this analysis is to build a model that can identify the creditworthiness of borrowers.
  2. The dependent variable (y-value) was the "loan_status": healthy or at risk.
  3. The independent variable (X-value) was the "loan_size", "interest_rate", "borrower_income", "debt_to_income", "num_of_accounts", "derogatory_marks", and "total_debt".

  ![image](https://github.com/fiyang89/credit-risk-classification/assets/120594187/7f003572-c5ea-437a-82da-d4f24a2af7f5)

- Results: Using a bulleted list, describe the accuracy score, the precision score, and the recall score of the machine learning model.
  1. Training and testing the original data using the Logistic Regression model provides an effective method for a Machine Learning Classification Model.
  2. Randomly Oversampling the original data will provide higher scores for balanced accuracy and recall allowing for the model to predict high risk loans more accurately.

- Summary: Summarize the results from the ML model. Include your justification for recommending the model for use by the company. If you don't recommend the model, justify your reasoning.
  1. It is recommended that the Logistic Regression Model is sufficient for use by the company.
  2. Based on the Classification Report, the accuracy score is 0.99, with the precision and recall scores for True Positive and False Negative as 1.00

  ![image](https://github.com/fiyang89/credit-risk-classification/assets/120594187/2487c287-c5a9-4ab8-8dca-7e5111de950c)

  4. The results are similar for the Randomly Oversampling model as well, with the precision and recall scores for True Positive and False Negative as 1.00. However, in this model, the recall score for True Negative is more accurate with 1.00.
  
  ![image](https://github.com/fiyang89/credit-risk-classification/assets/120594187/2b4f3cc2-1abb-42d0-a8a4-11e1e7418f90)




