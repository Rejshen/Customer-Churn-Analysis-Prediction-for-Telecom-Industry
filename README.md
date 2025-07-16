# Telecom Customer Churn Prediction

This project analyzes a telecom dataset to identify key factors that influence customer churn, using the **QDAVI framework** (Question – Data – Analysis – Value – Insights). It combines **business analysis**, **data exploration**, and **machine learning** to build a predictive churn model and generate actionable insights.

---

## Project Objective

- Understand customer behavior and churn patterns
- Build a machine learning model to predict churn
- Identify key features that drive churn using feature importance
- Provide business insights to reduce churn and improve retention

---

## Dataset Features

| Column             | Description |
|--------------------|-------------|
| `CustomerID`       | Unique ID for each customer |
| `Gender`           | Male or Female |
| `Tenure`           | Number of months with the company |
| `MonthlyCharges`   | Monthly bill |
| `TotalCharges`     | Total money paid |
| `ContractType`     | Month-to-month, One year, Two year |
| `InternetService`  | DSL, Fiber optic, None |
| `TechSupport`      | Yes or No |
| `Churn`            | Target variable (Yes/No) |

---

## Tools & Technologies

- **Python** (Pandas, NumPy, Seaborn, Scikit-learn, Matplotlib)
- **Jupyter Notebook**
- **Random Forest Classifier** for churn prediction
- **Correlation heatmaps**, **boxplots**, and **feature importance plots**

---

## Key Insights

- Customers with **short tenures**, **month-to-month contracts**, and **high monthly charges** are more likely to churn.
- **Long-term contracts** and **tech support** are associated with better customer retention.
- `Tenure`, `ContractType`, and `MonthlyCharges` were the top predictors of churn.

---

## How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/churn-prediction.git
   cd churn-prediction
