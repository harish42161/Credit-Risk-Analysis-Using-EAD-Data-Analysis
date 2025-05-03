# Credit Risk Analysis Using Python & EDA
📌 Project Overview
This project presents an in-depth Exploratory Data Analysis (EDA) on a credit risk dataset to identify key factors that influence loan repayment behavior. By analyzing borrower demographics, income profiles, loan details, and repayment status, the goal is to extract actionable insights to support smarter lending decisions for financial institutions.

🚀 Key Features
Data Cleaning & Preprocessing:

Handled missing values, standardized column formats, removed duplicates

Converted data types for accurate analysis

Univariate & Bivariate Analysis:

Explored distributions of features like gender, income type, family status, credit amount

Investigated relationships between features and the target variable (loan default)

Data Binning & Grouping:

Categorized age, income, and credit amount into bins for trend comparison

Grouped borrower profiles to detect risk-prone segments

Outlier Treatment:

Detected and capped extreme values in income and loan features

Data Visualization:

Generated bar plots, histograms, KDE plots, and pie charts using Seaborn and Matplotlib

Visualized correlations between features and repayment behavior

📊 Business Insights
Males, especially unmarried applicants, showed a higher risk of default

Borrowers with more children had a lower likelihood of defaulting

Government employees had higher repayment rates than commercial associates

Higher income and longer employment duration correlated with better repayment behavior

Anomalies like extremely high income or loan values were treated as outliers to reduce skewness

📁 Dataset
The analysis is based on anonymized data representing borrower demographics, loan applications, credit history, and repayment status.

🛠 Technologies Used
Python: Pandas, NumPy, Seaborn, Matplotlib

Jupyter Notebook

Git & GitHub for version control

📂 Project Structure
css
Copy
Edit
credit-risk-analysis-eda/
│── data/
│   └── credit_risk_data.xlsx
│── notebooks/
│   └── main.ipynb
│── README.md
│── requirements.txt
│── LICENSE
💻 Installation & Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/credit-risk-analysis-eda.git
Navigate to the project folder:

bash
Copy
Edit
cd credit-risk-analysis-eda
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook notebooks/main.ipynb
