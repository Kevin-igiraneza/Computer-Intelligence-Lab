REG NO: 224005430
 # Computer Intelligence Lab 1

## Telco Customer Churn Analysis

### 1. Introduction

This project is part of the Computer Intelligence Lab 1 assignment. The objective is to analyze the Telco Customer Churn dataset using Python in Kaggle and identify factors associated with customers leaving a telecommunications company.

### 2. Dataset

The dataset used is the Telco Customer Churn dataset available on Kaggle.

**Dataset link:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The original dataset contains 7,043 customer records and 21 attributes. After data preprocessing, 7,032 records remained.

### 3. Tools and Libraries

- Python
- Kaggle Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GitHub

### 4. Tasks Performed

**Dataset Loading**

The dataset was loaded using Pandas, and the first and last five rows were displayed.

**Data Preprocessing**

- Converted Churn values from Yes/No to 1/0.
- Displayed the data types of all attributes.
- Converted TotalCharges into a numerical data type.
- Identified and removed 11 records containing missing values.

**Data Exploration**

Demographic Analysis:
- Gender vs Churn
- SeniorCitizen vs Churn
- Partner vs Churn
- Dependents vs Churn

Service Analysis:
- PhoneService vs Churn

Payments Analysis:
- Contract vs Churn
- PaperlessBilling vs Churn
- PaymentMethod vs Churn

### 5. Key Findings

The analysis revealed that:

- Senior citizens had a higher churn rate than non-senior citizens.
- Customers without partners or dependents had higher churn rates.
- Gender and phone service showed relatively small differences in churn rates.
- Month-to-month contracts had the highest churn rate among contract types.
- Customers using paperless billing had a higher churn rate.
- Electronic check users had the highest churn rate among payment methods.

### 6. Conclusion

The analysis showed that customer churn is associated with factors such as contract type, payment method, billing preferences, and customer demographics.

Python libraries were used to clean the dataset, create visualizations, and interpret the results.

The findings can help telecommunications companies identify customer groups with higher churn rates and develop strategies to improve customer retention.

### 7. How to Run the Notebook

1. Download the `.ipynb` notebook from this repository.
2. Open it in Kaggle.
3. Add the Telco Customer Churn dataset using the Kaggle link above.
4. Update the dataset path if necessary.
5. Run all code cells in order.
