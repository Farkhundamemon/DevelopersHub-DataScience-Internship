# Task 3 - Customer Churn Prediction

## 📌 Overview
This project focuses on predicting whether a bank customer is likely 
to leave the bank using Machine Learning. The goal is to analyze 
customer behavior and build a classification model to identify 
potential churners.

## 🎯 Objective
- Clean and prepare the dataset
- Encode categorical features
- Train a classification model
- Analyze feature importance to understand churn factors

## 🛠 Tools Used
- Python 3.14
- VS Code
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset
Churn Modelling Dataset containing 10,000 bank customers with the 
following features:
- CreditScore
- Geography (France, Germany, Spain)
- Gender
- Age
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (Target Variable — 1 = Left, 0 = Stayed)

## 🔍 Analysis Performed
- Data inspection using .shape, .info() and .describe()
- Churn distribution visualization
- Geography vs Churn analysis
- Gender vs Churn analysis
- Age vs Churn analysis using Box Plot
- Label Encoding for Gender and Geography
- Random Forest Classifier model training
- Accuracy score and Confusion Matrix evaluation
- Feature Importance analysis

## 🧠 Key Insights
- Female customers have a higher churn rate than male customers
- Germany has the highest churn rate among all countries
- Older customers are more likely to leave the bank
- Age and Balance are the most important factors influencing churn

## ✅ Conclusion
The Random Forest model achieved around 86% accuracy in predicting 
customer churn. Age and Balance are the most significant features. 
Banks should focus on retaining older customers and those with 
higher balances to reduce churn rate.