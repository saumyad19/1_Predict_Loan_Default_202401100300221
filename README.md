# 1_Predict_Loan_Default_202401100300221
# Loan Default Prediction

## 📌 Problem Statement
The goal of this project is to predict whether a loan applicant will **default** or not using a machine learning model trained on a dataset of financial and demographic features. This is a classification problem, and solving it can help financial institutions minimize risks.

---

## 👤 Author Details
- **Name**: Saumya Dubey  
- **Roll No**: 202401100300221  
- **Institute**: KIET Group of Institutions  
- **Course**: B.Tech  
- **Branch**: Computer Science & Engineering (Artificial Intelligence)  
- **Date**: April 18, 2025  

---

## 📖 Introduction
Loan defaults are a significant concern for financial institutions. Being able to predict potential defaulters based on historical data helps minimize risks and make informed lending decisions. This project uses a supervised learning approach to analyze applicant data and build a model to classify loan default status.

---

## ⚙️ Methodology

1. **Data Loading**: The dataset is uploaded in Google Colab.
2. **Exploration**: Dataset shape, data types, and null values are inspected.
3. **Preprocessing**:
   - Null value handling
   - Categorical encoding via one-hot encoding
   - Train-test split
4. **Modeling**:
   - A `RandomForestClassifier` is used for training.
5. **Evaluation**:
   - Metrics like accuracy, precision, recall, and a confusion matrix are used.

---

## 🧠 Technologies Used

- **Python**
- **Google Colab**
- **Pandas** for data manipulation
- **Scikit-learn** for model building and evaluation
- **Matplotlib/Seaborn** for visualization

---

## 💻 Code Snippet

```python
from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier(random_state=42)
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
