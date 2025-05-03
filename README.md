# 📊 Credit Risk Analysis - EDA Case Study

> **A comprehensive exploratory analysis to identify risk patterns in loan applicants using Python.**

---

## 🔍 Overview
This project conducts **Exploratory Data Analysis (EDA)** on a financial dataset to uncover hidden patterns in loan defaults. The analysis helps financial institutions **minimize lending risks** by identifying high-risk borrower profiles and optimizing approval strategies. Insights are derived from demographic, employment, and financial attributes.

---

## 🎯 Objectives
- Analyze factors influencing loan repayment behavior
- Compare defaulters vs. non-defaulters across key metrics
- Visualize correlations between variables (e.g., income, credit amount)
- Provide actionable insights for risk-based decision-making

---

## 🧰 Tools & Technologies
| Language | Libraries | Platform |
|----------|-----------|----------|
| Python   | Pandas, NumPy, Matplotlib, Seaborn | Jupyter Notebook |

---

## 📂 Dataset Description
| File | Description |
|------|-------------|
| `application_data.csv` | Contains 307,511 rows of applicant data with 122 features |
| `previous_application.csv` | Historical loan application data (not included in current analysis) |

**Target Column:** `TARGET`  
- **0**: No payment difficulties  
- **1**: Client with payment difficulties  

---

## 📌 Key Steps & Features

### ✅ Data Cleaning & Preprocessing
- Dropped columns with >40% missing values
- Filled missing values (e.g., `OCCUPATION_TYPE` → "Unknown")
- Converted negative days (e.g., `DAYS_EMPLOYED`) to positive values
- Binned numerical features:  
  - `INCOME_RANGE`, `CREDIT_RANGE`, `AMT_ANNUITY_RANGE`

### 📊 Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Distributions of income, credit amount, annuity  
- **Bivariate Analysis**:  
  - Income vs. employment duration  
  - Credit amount vs. gender/education  
- **Outlier Treatment**: Capped extreme values using IQR

### 📈 Visualizations
- Count plots for categorical variables (`CODE_GENDER`, `NAME_INCOME_TYPE`)
- Comparative histograms for defaulters vs. non-defaulters
- Heatmaps for feature correlations

---

## 🔑 Key Findings
- **Demographics**:  
  - Clients aged **30-50** and **married** applicants showed lower default rates.  
  - **Male clients with academic degrees** were more likely to repay loans.  
- **Financial Factors**:  
  - Higher credit amounts (**>750k**) correlated with on-time payments.  
  - Long-term employed clients (**>19 years**) had minimal defaults.  
- **Risk Groups**:  
  - Laborers, drivers, and unmarried applicants exhibited higher default risks.  

---

## 📁 Project Structure
Credit-Risk-Analysis/
├── data/
│ ├── application_data.csv # Raw dataset
├── notebooks/
│ ├── main.ipynb # Full analysis code
├── README.md
└── .gitignore


---

## 🛠 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/harish42161/Credit-Risk-Analysis-Using-EDA
   
