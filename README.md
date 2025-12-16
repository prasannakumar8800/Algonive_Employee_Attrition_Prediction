# Algonive_Employee_Attrition_Prediction
**Project Overview**

Employee attrition is a major concern for organizations, as losing skilled employees affects productivity and increases hiring costs.
This project focuses on building a machine learning model that predicts whether an employee is likely to leave the company based on various HR-related factors.

This project was developed as part of my Data Science Internship at Algonive, with an emphasis on practical implementation, data analysis, and model evaluation.

**Objective**

To analyze employee data and predict employee attrition (Yes/No) using machine learning techniques, helping organizations identify potential attrition risks in advance.

**Dataset Information**

Dataset Name: IBM HR Analytics – Employee Attrition Dataset

Source: Kaggle

Records: 1470 employees

Target Variable: Attrition (Yes / No)

The dataset contains employee details such as age, job satisfaction, income, work experience, work-life balance, and other demographic and professional attributes.

**Technologies Used**

Programming Language: Python

IDE: Google Colab

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

**Project Workflow**

**1.Data Loading & Understanding**

Loaded the HR analytics dataset

Checked data structure and target variable distribution

**2.Data Preprocessing**

Converted target variable (Attrition) into numeric format

Removed irrelevant columns

Encoded categorical variables using one-hot encoding

Verified that there were no missing values

**3.Feature Selection & Data Splitting**

Separated features and target variable

Split the dataset into training and testing sets (80% / 20%)

**4.Model Building**

Implemented Logistic Regression

Applied feature scaling using StandardScaler to improve convergence

**5.Model Evaluation**

Evaluated model using accuracy, precision, recall, and F1-score

Generated confusion matrix for performance analysis

**6.Data Visualization**

Attrition distribution

Monthly income vs attrition

Job satisfaction vs attrition

Correlation heatmap

**Results**

**Model Accuracy: ~87.7%**

The model performs very well in predicting employees who stay with the company.

Attrition cases are fewer in the dataset, leading to slightly lower recall for employees who leave.

The results are consistent with real-world HR data behavior.

**Key Insights**

Employee attrition data is **imbalanced**, with significantly more employees staying than leaving.

Factors such as monthly income, job satisfaction, and work-life balance have noticeable influence on attrition.

Feature scaling improves Logistic Regression model performance and stability.

**Repository Contents**

Algonive_Employee_Attrition_Prediction.ipynb – Complete project notebook

HR-Employee-Attrition.csv

README.md – Project documentation

**Conclusion**

This project demonstrates how machine learning can be applied to real-world HR analytics problems. By analyzing employee data and building a predictive model, organizations can gain valuable insights into attrition trends and take proactive measures to improve employee retention.

**Contact**

Name: Pomba Prasanna Kumar

Email: prasannakumarpomba@gmail.com

Phone: +91 9959508800
