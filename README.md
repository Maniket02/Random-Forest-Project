# 🌲 Random Forest Project - Lending Club Loan Prediction

## 📘 Project Overview

This project explores **LendingClub.com** data to predict whether a borrower will fully repay a loan.  
Lending Club connects people who need loans (*borrowers*) with those who can invest (*lenders*).  
As an investor, it’s crucial to identify borrowers who have a **high probability of repaying** their loans in full.  

Using a **Random Forest Classifier**, we aim to create a predictive model that classifies borrowers based on their financial and credit-related attributes.

> 🔍 Dataset: Lending Club loan data (2007–2010)  
> 🧾 Goal: Predict whether a borrower **paid back their loan in full (`not.fully.paid = 0`)** or **defaulted (`not.fully.paid = 1`)**

---


---

## 🧩 Dataset Description

The dataset includes various borrower features related to credit history, income, and loan purpose.  

| Feature | Description |
|----------|--------------|
| `credit.policy` | 1 if the customer meets LendingClub’s underwriting criteria, 0 otherwise |
| `purpose` | Reason for the loan (e.g., credit_card, debt_consolidation, small_business, etc.) |
| `int.rate` | Interest rate as a proportion (0.11 for 11%) |
| `installment` | Monthly installment amount |
| `log.annual.inc` | Log of annual income |
| `dti` | Debt-to-income ratio |
| `fico` | FICO credit score |
| `days.with.cr.line` | Number of days borrower has had a credit line |
| `revol.bal` | Revolving balance (unpaid credit) |
| `revol.util` | Revolving line utilization rate |
| `inq.last.6mths` | Credit inquiries in the last 6 months |
| `delinq.2yrs` | Number of 30+ day delinquencies in past 2 years |
| `pub.rec` | Number of derogatory public records |
| `not.fully.paid` | Target variable: 1 = default, 0 = loan fully repaid |

📊 **Source:** [Lending Club Data Portal](https://www.lendingclub.com/info/download-data.action)  
📰 **Context:** [Lending Club (2016 Controversy)](https://en.wikipedia.org/wiki/Lending_Club#2016)

---

## 🧰 Technologies Used

| Category | Libraries / Tools |
|-----------|-------------------|
| **Language** | Python 🐍 |
| **Data Analysis** | pandas, NumPy |
| **Visualization** | matplotlib, seaborn |
| **Machine Learning** | scikit-learn |
| **Environment** | Jupyter Notebook / VS Code |

---

