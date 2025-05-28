# 💰 Bank Loan Analysis Project

## 📊 Overview

This project focuses on analyzing loan application data from a financial institution to uncover key trends and insights that can assist in better decision-making related to loan approvals, risk assessment, and customer segmentation.

With over **38,000+ rows and 24 features**, the dataset includes customer demographic details, loan details, and payment history. The project uses SQL for querying and Python for deeper exploratory data analysis (EDA).

---

## 🧰 Tools & Technologies

- **MySQL** – Data import, cleaning, and querying
- **Python** – Pandas, NumPy, Matplotlib, Seaborn (for EDA)
- **Tableau** – For data visualization dashboards
- **Excel** – For initial inspection and formatting (optional)

---

## 🔍 Objectives

- Analyze borrower details such as employment, income, purpose, and loan grade.
- Identify patterns among defaulters to assist in risk profiling.
- Understand how factors like loan amount, interest rate, and term affect payment behavior.
- Extract insights using SQL queries to answer business-related questions.

---

## 🗃️ Dataset

- **Format**: CSV (`financial_loan1.csv`)
- **Rows**: 38,000+
- **Columns**: 24
- **Key Fields**: `loan_status`, `annual_income`, `grade`, `int_rate`, `term`, `purpose`, `issue_date`, etc.

---

## ⚙️ Key SQL Queries

- Count of loans by status and purpose
- Loans with the highest and lowest interest rates
- States with highest default rates
- Analysis of income vs default
- Term-wise breakdown of loan performance

---

## 📈 Sample Insights

- Most defaults are observed among borrowers with lower income and longer-term loans.
- `Grade C` and `60 months` term loans show higher risk of charge-offs.
- Car loans and debt consolidation were the most common purposes.
- Georgia (GA) had one of the highest default concentrations in the dataset.

---

## ✅ Outcomes

- Cleaned and loaded large CSV file into MySQL database successfully.
- Handled data formatting challenges like non-standard dates and inconsistent text fields.
- Performed data wrangling and pattern analysis to identify business risks.
- Created summary visualizations (if applicable) to present insights clearly.


