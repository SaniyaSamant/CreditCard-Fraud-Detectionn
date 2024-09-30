# 🎯 Credit Card Fraud Detection Model

Welcome to the **Credit Card Fraud Detection** project! This is a machine learning project using **Logistic Regression** to detect fraudulent credit card transactions. We’ve built a simple web interface using **Streamlit**, where users can input transaction data and receive real-time predictions on whether the transaction is legitimate or fraudulent. 🚨💳

---

## 🔍 Project Overview

In this project, we tackle the problem of credit card fraud detection using a **Logistic Regression** model. The dataset is highly imbalanced, with most transactions being legitimate. To address this, we undersample legitimate transactions to create a balanced dataset before training our model.

The web app built with **Streamlit** allows users to enter transaction features and instantly get a prediction about whether the transaction is **Legitimate** ✅ or **Fraudulent** ❌.

---

## 🗂️ Dataset

The dataset used for this project is the **Credit Card Fraud Detection Dataset** from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains the following characteristics:

- **Legitimate Transactions**: 99.83% of the dataset
- **Fraudulent Transactions**: 0.17% of the dataset

📊 **Features**:
- **Time**: Seconds since the first transaction.
- **V1 - V28**: Features derived using Principal Component Analysis (PCA).
- **Amount**: Transaction amount.
- **Class**: 0 for legitimate transactions, 1 for fraudulent transactions.

---

## 🛠️ Technologies Used

- **Python 3.7+** 🐍
- **Pandas** 🐼: For data loading and manipulation.
- **NumPy** 🔢: For numerical computations.
- **Scikit-Learn** 📚: For machine learning and model evaluation.
- **Streamlit** 🌐: For creating the web interface.
- **Logistic Regression** 🧠: The core ML model.

---

## 🎮 Usage

1. Open the Streamlit app.
2. Enter the transaction feature values (Time, V1-V28, Amount) in the input box as a comma-separated list.
3. Click the **Submit** button.
4. The app will predict whether the transaction is **Legitimate** or **Fraudulent**.

---

## 📈 Model Evaluation

The **Logistic Regression** model's performance was evaluated as follows:

- **Training Accuracy**: 99.4% 🏆
- **Testing Accuracy**: 99.3% 🎯

This indicates the model can effectively detect fraudulent transactions. However, further tuning or more advanced techniques can improve its robustness.

---
