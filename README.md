# Fraud Detection with LightGBM

This project implements a binary classification pipeline for detecting fraudulent transactions using tabular data. The approach leverages real-world financial transaction and identity features, combined with feature engineering, preprocessing, and LightGBM modeling.

## 🔍 Problem Overview

The goal is to predict whether a transaction is fraudulent based on user, transaction, and device-related attributes. The dataset includes rich structured data across hundreds of fields.

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

