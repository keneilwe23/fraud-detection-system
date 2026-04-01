# Credit Card Fraud Detection System

A machine learning project that detects fraudulent credit card transactions using AWS SageMaker and XGBoost.

## Overview
- **Dataset**: Kaggle Credit Card Fraud Detection (284,807 transactions)
- **Algorithm**: XGBoost (binary classification)
- **Platform**: AWS SageMaker + Amazon S3

## Results
| Metric | Score |
|--------|-------|
| Precision | 83% |
| Recall | 86% |
| Accuracy | 99% |

## Tech Stack
- Python, XGBoost, scikit-learn
- AWS SageMaker, Amazon S3, boto3
- SMOTE (imbalanced-learn)

## Project Steps
1. Data preprocessing and cleaning
2. Train/test split and SMOTE oversampling
3. Model training on SageMaker
4. Real-time endpoint deployment
5. Model evaluation
