# Fraud Detection

This project implements a binary classification pipeline for detecting fraudulent transactions using tabular data. The approach leverages real-world financial transaction and identity features, combined with feature engineering, preprocessing, and modeling.

## 🔍 Problem Overview

The goal is to predict whether a transaction is fraudulent based on user, transaction, and device-related attributes.

This project uses a real-world anonymized dataset of online transactions with device and identity metadata. You can download the dataset from this public competition page:
[https://www.kaggle.com/competitions/ieee-fraud-detection/data](https://www.kaggle.com/competitions/ieee-fraud-detection/data)

After downloading, place the following four CSV files into a new `data/` folder in the project root.


## 🧠 Key Features

- Merging transaction and identity datasets
- Handling missing values by type
- Feature engineering (e.g. UID creation, datetime derivation)
- Label encoding for categorical features
- LightGBM modeling with validation
- AUC scoring and classification report
- Feature importance visualization

## 📊 Model Performance

- Achieved ~80% AUC score on validation
- Balanced handling of class imbalance with LightGBM built-in weighting

