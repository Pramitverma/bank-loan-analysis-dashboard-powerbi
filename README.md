# 🏦 Bank Financial Loan Analysis – Credit Risk & Portfolio Performance

Analyzing bank loan data to evaluate credit risk, customer behavior, and portfolio performance using **SQL, Python, and Power BI**.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Key Insights & Findings](#key-insights--findings)
- [Dashboard](#dashboard)
- [How to Run This Project](#how-to-run-this-project)
- [Final Recommendations](#final-recommendations)
- [Author](#author)

---

## Overview
This project analyzes a bank’s financial loan portfolio to derive insights related to **loan performance, credit risk, borrower behavior, and funding trends**.  
The goal is to support **data-driven decision-making** in lending strategy and risk management.

---

## Business Problem
Banks must balance **growth and risk** while issuing loans. This project aims to:

- Identify high-risk borrower segments
- Compare good vs bad loan performance
- Analyze loan demand trends over time
- Evaluate the impact of interest rate and DTI on defaults
- Support credit policy and portfolio optimization

---

## Dataset
- Financial loan dataset containing borrower, loan, and repayment details
- Each row represents **one loan application**
- Includes loan status, grade, purpose, interest rate, DTI, and issue date

---

## Tools & Technologies
- **SQL** – Joins, CTEs, Window Functions, Aggregations
- **Python** – Pandas, NumPy, Matplotlib
- **Power BI** – Interactive dashboards & KPIs
- **GitHub** – Version control & project documentation

---

## Project Structure
```text
bank-financial-loan-analysis/
│
├── README.md
├── dataset/
│   └── financial-loan-dataset.csv
├── notebooks/
│   └── bank_loan_analysis.ipynb
├── sql/
│   └── loan_analysis_queries.sql
├── dashboard/
│   └── bank_loan_dashboard.pbix
└── images/
    └── dashboard.png
