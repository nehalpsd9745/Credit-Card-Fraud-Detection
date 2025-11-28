# 💳 Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions using real anonymized data.

---

## 📌 Abstract
Credit card fraud leads to massive financial losses every year. Machine learning can detect unusual and fraudulent behavioral patterns within transaction data.  
This project evaluates multiple classification algorithms to identify fraudulent transactions and compares their performance.

**Keywords:** Credit Card Fraud Detection, Imbalanced Data, KNN, Logistic Regression, SVM, Decision Tree

---

## 📝 Overview
With the drastic rise in credit card usage globally, fraud detection has become essential for financial security.  
Fraud occurs mainly in two situations:

- 🆕 Fake accounts are created using stolen identity information  
- 💳 Unauthorized usage of an existing card takes place  

This project applies different supervised machine learning models to determine which technique performs best for detecting fraudulent transactions.

---

## 🎯 Project Goals
- Detect fraudulent credit card transactions
- Analyze real transactional data
- Study and compare multiple ML models
- Evaluate performance using relevant metrics

---

## 📂 Dataset Information
- Source: Kaggle (Open Dataset)
- Total Records: **284,808 transactions**
- Features: **31**
  - 28 anonymized PCA-transformed variables
  - `Time` → Seconds between first and current transaction
  - `Amount` → Transaction value
  - `Class` → Label (1 = Fraud, 0 = Not Fraud)

Dataset link:  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## 🤖 Models Implemented
This project includes 4 different classification techniques:

- 🟡 K-Nearest Neighbors (KNN)
- 🔵 Logistic Regression
- 🟣 Support Vector Machine (SVM)
- 🌳 Decision Tree (DT)

Each model is built and evaluated in a separate Jupyter Notebook.

---

## 📌 Project Structure
```bash
Credit-Card-Fraud-Detection-Using-Machine-Learning/
│
├── Credit Card Fraud Detection - Decision Tree.ipynb
├── Credit Card Fraud Detection - K-Nearest Neighbour.ipynb
├── Credit Card Fraud Detection - Logistic Regression.ipynb
├── Credit Card Fraud Detection - Support Vector Machine.ipynb
│
└── README.md

## 🏆 Results Summary

Fraud detection involves highly imbalanced data, so evaluating multiple metrics is important. For simplicity in this project, model performance is compared mainly using overall accuracy.

| Model | Accuracy | Performance Summary |
|-------|----------|-------------------|
| K-Nearest Neighbors (KNN) | ⭐ Excellent | Accurately detects fraudulent patterns |
| Decision Tree | ⭐ Excellent | High accuracy and fast learning capability |
| Logistic Regression | 👍 Good | Strong baseline model |
| Support Vector Machine (SVM) | 👍 Good | Works well on imbalanced data |

➡ **KNN and Decision Tree performed the best and achieved the highest accuracy among the implemented models.**

---

## ▶️ How to Run the Project

1️⃣ Clone this repository  
```bash
git clone https://github.com/nehalpsd9745/Credit-Card-Fraud-Detection.git

2️⃣ Download the dataset from Kaggle (linked above)

3️⃣ Open any .ipynb notebook using any of the following:

Jupyter Notebook

Google Colab

VS Code with Jupyter support

4️⃣ Update the dataset path inside the code

5️⃣ Run all cells to train and test the models
