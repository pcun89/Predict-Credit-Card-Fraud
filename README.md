# Predict-Credit-Card-Fraud
# 💳 Credit Card Fraud Detection

This project is a machine learning pipeline for detecting fraudulent credit card transactions. Built as part of the Codecademy "Predict Credit Card Fraud" project, it demonstrates how to handle imbalanced datasets, train classification models, and evaluate their performance using precision-critical metrics.

---

## 🚀 Project Overview

- **Goal**: Accurately classify transactions as either `fraud` or `not fraud`.
- **Dataset**: A real-world anonymized dataset with PCA-transformed features for privacy. Includes transaction time, amount, and class labels.
- **Challenge**: Highly imbalanced dataset (fraud is rare), requiring specialized techniques like SMOTE.

---

## 🧠 Features

- Preprocessing with standard scaling
- Class balancing using SMOTE
- Model training with:
  - Logistic Regression
  - Random Forest
- Hyperparameter tuning using `GridSearchCV`
- Evaluation using:
  - Confusion Matrix
  - Precision, Recall, F1-Score
- Test suite using `pytest`

---

## 📁 Project Structure

