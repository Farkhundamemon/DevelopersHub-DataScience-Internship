
# Task 2 - Credit Risk Prediction

## 📌 Overview
This project focuses on predicting whether a loan applicant is likely 
to default on a loan using Machine Learning. The goal is to clean the 
data, analyze key features, and build a classification model.

## 🎯 Objective
- Handle missing data appropriately
- Visualize key features like loan amount, education, and income
- Train a Logistic Regression classification model
- Evaluate model performance using accuracy and confusion matrix

## 🛠 Tools Used
- Python 3.14
- VS Code
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset
Loan Prediction Dataset from Kaggle containing 614 loan applications 
with the following features:
- Gender
- Married
- Education
- Applicant Income
- Loan Amount
- Credit History
- Loan Status (Target Variable)

## 🔍 Analysis Performed
- Data inspection using .shape, .info() and .describe()
- Missing values handled using mode and mean
- Label Encoding for categorical features
- Count plots for Loan Status and Education
- Histogram for Loan Amount Distribution
- Scatter plot for Income vs Loan Amount
- Logistic Regression model training
- Accuracy score and Confusion Matrix evaluation

## 🧠 Key Insights
- Credit History is the most important factor for loan approval
- Graduates are more likely to get loans than non-graduates
- Most applicants apply for loan amounts between 100 and 200 (thousands)
- Higher income does not always guarantee loan approval

## ✅ Conclusion
The Logistic Regression model achieved around 80% accuracy in 
predicting loan approval. Credit history and education level are 
the most significant factors that influence loan approval decisions.


