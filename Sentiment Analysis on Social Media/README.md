# 💬 Sentiment Analysis Classifier

A natural language processing (NLP) project to classify the sentiment of text data (e.g., reviews, tweets) into categories like positive, negative, or neutral. The project involves text cleaning, vectorization, model building, and evaluation using Python-based NLP libraries.

---

## 🔍 Overview

Sentiment analysis helps businesses understand public opinion by automatically classifying the emotional tone of text. This project uses labeled text data to train machine learning models that predict sentiment from raw input.

---

## 🧰 Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📊 Dataset

The dataset contains labeled text entries with their associated sentiments. 
- `text`: The user-generated text
- `sentiment`: Label such as `positive`, `negative`, or `neutral`
source:
- Twitter Airline Sentiment Dataset
  
---

## 🧹 Data Preprocessing

- Removed missing values
- Lowercased all text
- Removed stop words, stemwords, special characters
- Performed encoding of sentiment classes

---

## 📈 Visualization

- Word clouds for positive vs negative sentiment
- Class distribution bar chart

---

## 🧠 Model Building

- Vectorized text using TF-IDF
- Split data into train/test sets using `train_test_split`
- Trained classification model using Logistic Regression
- Evaluated using:
  - Accuracy, Precision, Recall, F1-score

---

## 🎯 Model Improvement

- Applied hyperparameter tuning using `GridSearchCV`

