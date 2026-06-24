# Task 4 - Predicting Insurance Claim Amounts

## 📌 Overview
This project focuses on predicting medical insurance claim amounts 
based on personal data using Linear Regression. The goal is to 
understand how different factors like age, BMI, and smoking status 
impact insurance charges.

## 🎯 Objective
- Train a Linear Regression model to predict insurance charges
- Visualize how BMI, age, and smoking status impact charges
- Evaluate model performance using MAE and RMSE

## 🛠 Tools Used
- Python 3.14
- VS Code
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Numpy
- Jupyter Notebook

## 📂 Dataset
Medical Cost Personal Dataset containing 1338 records with the 
following features:
- Age
- Sex
- BMI (Body Mass Index)
- Children
- Smoker (Yes/No)
- Region
- Charges (Target Variable)

## 🔍 Analysis Performed
- Data inspection using .shape, .info() and .describe()
- Missing values check
- BMI vs Charges scatter plot
- Age vs Charges scatter plot
- Smoker vs Charges box plot
- Label Encoding for categorical features
- Linear Regression model training
- Model evaluation using MAE and RMSE

## 🧠 Key Insights
- Smokers pay significantly higher insurance charges than non-smokers
- Insurance charges increase with age
- Higher BMI leads to higher insurance charges
- Smoking status is the most important factor affecting charges

## ✅ Conclusion
The Linear Regression model was trained to predict insurance charges. 
Smoking status, age, and BMI are the most significant factors 
influencing insurance claim amounts. Smokers pay almost 3-4 times 
more than non-smokers on average.