# Telco-Customer-Churn-Analysis

Data preprocessing and customer churn analysis using Python and Pandas.

## 1. Introduction
Customer churn occurs when customers stop using a company's services. This project analyzes the Telco Customer Churn dataset to explore customer characteristics and service-related factors associated with churn.

## 2. Objectives
- Load and inspect the dataset.
- Identify and correct data types.
- Convert Churn values from Yes/No to 1/0.
- Identify and remove missing values.
- Explore relationships between customer attributes and churn.

## 3. Tools and Technologies
- Python
- Pandas
- Kaggle Notebooks

## 4. Data Preprocessing
The dataset was loaded using Pandas. The data types of the attributes were inspected, `TotalCharges` was converted to a numeric data type, rows containing missing values were removed, and the `Churn` attribute was converted from Yes/No to 1/0.

## 5. Exploratory Data Analysis
The following attributes were analyzed in relation to customer churn:

1. Gender
2. Senior citizen status
3. Partner status
4. Dependents
5. Phone service
6. Contract type
7. Paperless billing
8. Payment method

Churn rates were calculated for each category and interpreted to identify patterns in customer behavior.

## 6. Key Findings
- Senior citizens had a higher churn rate than non-senior citizens.
- Customers without partners or dependents had higher churn rates.
- Customers with month-to-month contracts had a much higher churn rate than customers with longer contracts.
- Electronic check users had the highest churn rate among the payment methods analyzed.
- Gender and phone service showed relatively small differences in churn rates.

## 7. Dataset
**Source:** [Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 8. Conclusion
The analysis identified several customer characteristics associated with churn, particularly contract type and payment method. These findings may help a company identify customer groups that could benefit from improved retention strategies. The observed associations do not prove that these factors directly cause churn.
