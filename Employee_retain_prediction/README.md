# Employee Turnover Prediction using Logistic Regression

## Overview

This mini project predicts employee turnover using Logistic Regression and compares the performance of L1 and L2 regularization techniques.

The objective is to analyze employee attrition and study the effect of regularization on model performance.

---

## Problem Statement

Employee turnover (attrition) is an important problem for organizations as frequent employee exits can affect productivity and increase hiring costs.

This project predicts whether an employee will leave the organization based on employee-related features.

---

## Workflow

1. Load employee turnover dataset
2. Data preprocessing
3. Feature encoding and scaling
4. Train-test split
5. Train Logistic Regression model
6. Apply regularization techniques
7. Compare model performance

---

## Models Used

### Logistic Regression with L1 Regularization (Lasso)

- Performs feature selection
- Can shrink some coefficients to zero

### Logistic Regression with L2 Regularization (Ridge)

- Reduces overfitting
- Penalizes large coefficients

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Evaluation Metrics

Models evaluated using:

- Accuracy Score

---

## Comparison

Performance comparison was carried out between:

- Logistic Regression with L1 Regularization
- Logistic Regression with L2 Regularization

to analyze their effect on employee turnover prediction accuracy.

---

## Result

The project compares classification performance and regularization impact on Logistic Regression.

---

## Project Structure

Employee_Turnover_Prediction/

├── employee_turnover.ipynb

└── README.md