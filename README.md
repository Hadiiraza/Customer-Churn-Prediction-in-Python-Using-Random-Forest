# Customer Churn Prediction in Python Using Random Forest


## Overview
This repository contains a Python implementation for predicting customer churn using the Random Forest classification algorithm. Customer churn is a critical business metric, and predicting it can help businesses identify and retain customers more effectively.

## Dataset
The project uses a dataset with various customer attributes such as gender, tenure, internet service, contract type, and more. The goal is to predict whether a customer will churn or not based on these features.

### Dataset Information
- **File:** `telco_customer_churn.csv`
- **Columns:**
  - `customerID`: Customer ID
  - `gender`: Gender of the customer
  - `SeniorCitizen`: Whether the customer is a senior citizen (1) or not (0)
  - `Partner`: Whether the customer has a partner (Yes/No)
  - `Dependents`: Whether the customer has dependents (Yes/No)
  - ... (and other relevant columns)

## Steps Involved
The notebook includes the following:
1. Data exploration and preprocessing.
2. Visualizations for better understanding of the dataset.
3. Encoding categorical variables and handling missing values.
4. Implementation of Random Forest for customer churn prediction.
5. Smote technique for Imbalance data.
6. Model evaluation using accuracy score.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Required Python libraries: pandas, numpy, seaborn, scikit-learn
  
