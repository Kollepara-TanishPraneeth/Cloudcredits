# 📉 Customer Churn Predictor

A machine learning project to predict customer churn in a telecom company using structured customer usage and demographic data. This project involves data preprocessing, feature encoding, model training, and evaluation, all in Python.

---

## 🔍 Overview

Customer churn is a major concern for subscription-based businesses. This project analyzes customer behavior to build a predictive model that classifies whether a customer will churn (i.e., discontinue service).

---

## 🧰 Tools & Technologies

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---


## 📊 Dataset

The dataset contains customer information such as:
- Demographics (gender, senior citizen, partner, etc.)
- Service details (phone, internet, contract type, etc.)
- Financials (monthly charges, total charges)
- Churn status (`Yes` or `No`)

---

## 🧹 Data Preprocessing

- Removed missing values
- Converted `TotalCharges` to numeric
- Binary encoding for `Churn`, `gender`, and other yes/no fields
- One-hot encoding for multi-class categorical variables (e.g., `InternetService`, `PaymentMethod`)
- Created custom `tenure_group` feature

---

## 📈 Visualization

- Correlation heatmap of numeric features
- Distribution plots for both numeric and object variables

---

## 🧠 Model Building

- Split data into train/test sets using `train_test_split`
- Trained classification model using Random Forest
- Evaluated using:
  - Accuracy, F-1 Score

---

## 🎯 Model Improvement

- Perform hyperparameter tuning using GridSearchCV to optimize model performance

