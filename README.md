# Bank Loan Analysis Report (EDA)

This repository contains a comprehensive **Exploratory Data Analysis (EDA)** of a bank loan dataset using Python. The analysis provides insights into loan applications, funded amounts, repayment trends, and borrower behavior, helping understand loan performance and key financial metrics.

---

## 📂 Project Overview

The project performs a detailed analysis of a financial loan dataset, covering:

- Summary-level statistics of loans and borrowers
- Monthly trends in funded amounts, amount received, and loan applications
- Metrics for good loans vs bad loans
- Average interest rates and debt-to-income ratios
- Visualizations using Matplotlib, Seaborn, and Plotly

---

## 🛠️ Technologies Used

- Python 3.x  
- Pandas & NumPy (data manipulation)  
- Matplotlib & Seaborn (data visualization)  
- Plotly Express (interactive plots)  
- Jupyter Notebook (analysis environment)  

---

## 🔍 Key Analysis Steps

### Data Import and Overview
- Loaded the dataset and explored basic metadata (`head`, `tail`, `info`, `describe`)

### Total Loan Applications & Funded Amounts
- Calculated overall and month-to-date (MTD) loan applications and funded amounts

### Loan Performance Metrics
- Identified **good loans** (`Fully Paid`, `Current`)  
- Identified **bad loans** (`Charged Off`)  
- Calculated percentages, funded amounts, and received amounts

### Monthly Trends
- Visualized trends of **total funded amount**, **amount received**, and **loan applications** by month  
- Added annotations for better readability

### Financial Ratios
- Computed average **interest rate** and **debt-to-income ratio**

---

## 📊 Visualizations

- **Total Funded Amount by Month**  
- **Total Amount Received by Month**  
- **Total Loan Applications by Month**  
- Filled line charts with annotations to display exact values

---

## ⚡ Key Insights

- December recorded the **highest funded amount**  
- **Mortgage loans** accounted for the largest share of funding  
- **Debt consolidation** is the most common loan purpose  
- **Good loans** constitute over 86% of all loans

---

## 📁 Dataset

The dataset (`financial_loan_data_excel.xlsx`) should be placed in the project folder. It contains:

- `id`: Loan application ID  
- `issue_date`: Date of loan issuance  
- `loan_amount`: Funded amount  
- `total_payment`: Total repayment received  
- `int_rate`: Interest rate  
- `dti`: Debt-to-income ratio  
- `loan_status`: Loan performance (`Fully Paid`, `Current`, `Charged Off`)  
- `loan_purpose`: Purpose of the loan
