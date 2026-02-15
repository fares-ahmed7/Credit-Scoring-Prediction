# Credit Scoring Prediction

## Description
This project is a **Credit Scoring Prediction System** that evaluates an individual's creditworthiness based on their financial history. It uses machine learning models to classify clients as likely to default or not. 

The project implements and compares three models:
1. Logistic Regression
2. Random Forest
3. Decision Tree

The system also visualizes:
- Confusion Matrix
- ROC Curve
- Feature Importance
- Decision Tree structure (for interpretability)

---

## Dataset
- The dataset used is `credit_data.csv`.
- Target column: `default.payment.next.month`
- Features include financial metrics such as income, debts, payment history, and other relevant financial data.

---

## Requirements
Python libraries used:
- pandas
- numpy
- matplotlib
- scikit-learn

You can install the required packages with:
```bash
pip install pandas numpy matplotlib scikit-learn
