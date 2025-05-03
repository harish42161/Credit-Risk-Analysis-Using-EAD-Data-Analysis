# 📊 Credit Risk Analysis – EDA Case Study

> **A complete exploratory analysis to uncover hidden risk patterns in borrower data using Python.**

---

## 🔍 Overview
This project performs an **Exploratory Data Analysis (EDA)** on a financial dataset related to loan applications and repayment status. The aim is to uncover the key demographic and financial variables that influence credit default, helping financial institutions **identify high-risk customers** and make better data-driven lending decisions.

---

## 🎯 Objectives
- Analyze customer attributes and loan history
- Identify patterns among defaulters vs. non-defaulters
- Visualize trends to support credit risk assessment
- Prepare insights for future predictive modeling

---

## 🧰 Tools & Technologies
| Language | Libraries | Platform |
|----------|-----------|----------|
| Python | Pandas, NumPy, Matplotlib, Seaborn | Jupyter Notebook |
| Version Control | Git, GitHub | — |

---

## 📂 Dataset Description
| File | Description |
|------|-------------|
| `credit_risk_data.xlsx` | Contains customer demographic and loan-related data |

**Target Column:** `Loan_Status` – Binary indicator of whether the customer defaulted or not.

---

## 📌 Key Features & Steps

### ✅ Data Cleaning & Preprocessing
- Handled nulls, corrected data types
- Removed duplicates and irrelevant columns
- Binned numerical variables for better comparison

### 📈 Exploratory Data Analysis (EDA)
- Univariate & bivariate analysis (e.g., income, employment, loan amount)
- Grouped variables by loan status for comparison
- Outlier treatment using capping

### 📊 Visualizations
- Distribution plots, bar graphs, pie charts
- Correlation heatmaps
- KDE plots comparing defaulters vs non-defaulters

> **Example Insight:**  
> 📉 *Males and unmarried individuals showed higher default rates, while government employees and borrowers with children tended to repay more reliably.*

---

## 🗂️ Project Structure
credit-risk-analysis-eda/
├── data/
│ └── credit_risk_data.xlsx
├── notebooks/
│ └── main.ipynb
├── README.md
├── requirements.txt
└── LICENSE

