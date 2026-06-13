# Predicting High-Risk Loan Applicants Using Machine Learning

## Project Overview

This project aims to classify loan applicants as either high-risk or low-risk using demographic, employment, and financial information.

The following models were implemented:

- Logistic Regression
- Random Forest

## Dataset

- 252,000 loan applicants
- 13 features
- Binary target variable:
  - 0 = Low Risk
  - 1 = High Risk

## Methods

- Data cleaning
- One-Hot Encoding
- Train/Test Split
- Logistic Regression
- Random Forest
- Hyperparameter Tuning

## Results

| Model | Accuracy | Precision | Recall | F1 |
|-------|----------|----------|-------|----|
| Logistic Regression | 0.65 | 0.12 | 0.31 | 0.18 |
| Random Forest | 0.89 | 0.55 | 0.76 | 0.64 |

## Conclusion

Random Forest significantly outperformed Logistic Regression, particularly in identifying high-risk applicants. The final model achieved a recall of 76% and an F1-score of 64%, demonstrating its effectiveness for loan risk classification.
