# Customer Churn Prediction (PyTorch + Scikit-learn)

This project uses machine learning to predict whether a bank customer will churn based on behavioral and demographic data.

## 🔍 Project Overview

- Dataset: BankChurners.csv (from Kaggle or IBM sample)
- Binary classification: "Attrition_Flag"
- Two models used:
  - Deep Neural Network (PyTorch)
  - Logistic Regression (Scikit-learn)
- Evaluation: Accuracy, Confusion Matrix, Classification Report

## 🧠 Model Details

### PyTorch Neural Network
- 5-layer feedforward network
- Activation: Tanh
- Loss: BCEWithLogitsLoss
- Optimizer: Adam

### Logistic Regression
- Used as a baseline
- Achieved high performance due to simple but effective feature encoding

## 📊 Results

- Logistic Regression Accuracy: 100% (initially, due to data leakage)
- Fixed pipeline: accuracy dropped to more realistic levels
- PyTorch model tuned to match the corrected pipeline


