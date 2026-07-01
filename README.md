# 💳 Credit Scoring Prediction

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-Classification-orange?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)

A **Credit Scoring Prediction System** that evaluates an individual's creditworthiness based on their financial history, classifying clients as likely to default on their next payment or not.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Dataset](#-dataset)
- [Project Structure](#-project-structure)
- [Models Compared](#-models-compared)
- [Visualizations](#-visualizations)
- [Requirements](#-requirements)
- [Installation & Usage](#️-installation--usage)
- [Results](#-results)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 📌 Overview

Credit scoring is a core problem in the financial industry: predicting whether a client is likely to default on a payment based on their financial history. This project builds and compares three classification models to tackle that problem, and provides interpretability tools (feature importance, decision tree visualization) to understand *why* the model makes each prediction — not just *what* it predicts.

---

## 📂 Dataset

**File:** `data/credit_data.csv`

| Field | Description |
|---|---|
| Target column | `default.payment.next.month` |
| Features | Financial metrics such as income, debts, payment history, and other credit-related attributes |

---

## 📁 Project Structure

```
Credit-Scoring-Prediction/
│
├── data/
│   └── credit_data.csv
│
├── Credit Scoring Prediction.ipynb   # Main notebook (EDA + modeling + evaluation)
│
└── README.md
```

---

## 🤖 Models Compared

- **Logistic Regression**
- **Random Forest**
- **Decision Tree**

Each model is trained and evaluated on the same train/test split for a fair comparison.

---

## 📊 Visualizations

The notebook includes:

- **Confusion Matrix** — to inspect true/false positives and negatives for each model
- **ROC Curve** — to compare models by their ROC-AUC score
- **Feature Importance** — to identify which financial factors drive default risk the most
- **Decision Tree structure** — visualized for interpretability

---

## ✅ Requirements

```
pandas
numpy
matplotlib
scikit-learn
```

Install with:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## ⚙️ Installation & Usage

**1. Clone the repository**

```bash
git clone https://github.com/fares-ahmed7/Credit-Scoring-Prediction.git
cd Credit-Scoring-Prediction
```

**2. Install dependencies**

```bash
pip install pandas numpy matplotlib scikit-learn
```

**3. Run the notebook**

```bash
jupyter notebook "Credit Scoring Prediction.ipynb"
```

---

## 📈 Results

> Add your models' final metrics and a short takeaway here once you have them, e.g.:
>
> | Model | Accuracy | Precision | Recall | ROC-AUC |
> |---|---|---|---|---|
> | Logistic Regression | ... | ... | ... | ... |
> | Random Forest | ... | ... | ... | ... |
> | Decision Tree | ... | ... | ... | ... |
>
> **Best model:** ... — chosen based on ...

---

## 👨‍💻 Author

**Fares Ahmed**
GitHub: [@fares-ahmed7](https://github.com/fares-ahmed7)

---

⭐ If you found this project useful, consider giving it a star!
