# Task 5 - Personal Loan Acceptance Prediction

## 📌 Overview
This project focuses on predicting which customers are likely to 
accept a personal loan offer using Machine Learning. The goal is 
to analyze customer data and identify patterns in loan acceptance.

## 🎯 Objective
- Perform basic data exploration on features like age, job, marital status
- Train a Logistic Regression classifier
- Analyze results to identify which customer groups accept loans more

## 🛠 Tools Used
- Python 3.14
- VS Code
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset
Bank Marketing Dataset containing 45,211 records with the 
following features:
- Age
- Job
- Marital Status
- Education
- Balance
- Housing
- Loan
- Contact
- Month
- Duration
- Campaign
- y (Target Variable — yes/no)

## 🔍 Analysis Performed
- Data inspection using .shape, .info() and .describe()
- Missing values check
- Loan Acceptance Distribution
- Job vs Loan Acceptance analysis
- Age vs Loan Acceptance Box Plot
- Label Encoding for categorical features
- Logistic Regression model training
- Accuracy score and Confusion Matrix evaluation

## 🧠 Key Insights
- Management and technician jobs have higher loan acceptance rate
- Age does not significantly impact loan acceptance
- Most customers do not accept the loan offer
- Customers with management jobs are more likely to accept loans

## ✅ Conclusion
The Logistic Regression model achieved around 89% accuracy in 
predicting personal loan acceptance. Job type is the most 
significant factor influencing loan acceptance decisions.