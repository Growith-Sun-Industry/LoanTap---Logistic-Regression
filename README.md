# LoanTap Credit Underwriting – Personal Loan Case Study

## Context

LoanTap is an online platform committed to delivering **customized loan products to millennials**. They innovate in an otherwise dull loan segment by offering **instant, flexible loans** on consumer-friendly terms to salaried professionals and businessmen.

The **Data Science team at LoanTap** is building an **underwriting layer** to determine the creditworthiness of **MSMEs as well as individuals**.

LoanTap deploys formal credit to salaried individuals and businesses through the following financial instruments:

- Personal Loan  
- EMI Free Loan  
- Personal Overdraft  
- Advance Salary Loan  

📌 **This case study focuses only on the underwriting process for _Personal Loans_.**

---

## Problem Statement

Given a set of attributes for an individual:

- Determine **whether a credit line should be extended**
- If approved, recommend **appropriate repayment terms** from a business perspective

---

## Dataset

- **Dataset Name:** `LoanTapData.csv`

---

## Data Dictionary

| Column Name | Description |
|------------|------------|
| `loan_amnt` | Loan amount applied for by the borrower |
| `term` | Number of payments (36 or 60 months) |
| `int_rate` | Interest rate on the loan |
| `installment` | Monthly payment owed by the borrower |
| `grade` | LoanTap assigned loan grade |
| `sub_grade` | LoanTap assigned loan sub-grade |
| `emp_title` | Job title provided by the borrower |
| `emp_length` | Employment length in years (0–10) |
| `home_ownership` | Home ownership status |
| `annual_inc` | Self-reported annual income |
| `verification_status` | Income verification status |
| `issue_d` | Month in which loan was funded |
| `loan_status` | Current loan status (**Target Variable**) |
| `purpose` | Purpose of loan |
| `title` | Loan title provided by borrower |
| `dti` | Debt-to-income ratio |
| `earliest_cr_line` | Month of borrower’s earliest credit line |
| `open_acc` | Number of open credit lines |
| `pub_rec` | Number of derogatory public records |
| `revol_bal` | Total revolving credit balance |
| `revol_util` | Revolving credit utilization rate |
| `total_acc` | Total number of credit lines |
| `initial_list_status` | Initial listing status (W, F) |
| `application_type` | Individual or joint application |
| `mort_acc` | Number of mortgage accounts |
| `pub_rec_bankruptcies` | Number of public record bankruptcies |
| `address` | Address of the individual |

---

## Concepts Used

- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Logistic Regression  
- Precision vs Recall Trade-off  

---

## Questionnaire  
**(Answers should be written in the text editor along with insights)**

1. What percentage of customers have **fully paid** their loan amount?  
2. Comment on the **correlation between Loan Amount and Installment** features.  
3. The majority of people have home ownership as _______.  
4. People with grades **‘A’** are more likely to fully pay their loan. (**True / False**)  
5. Name the **top 2 most common job titles**.  
6. From a bank’s perspective, which metric should be the **primary focus**?
   - ROC AUC  
   - Precision  
   - Recall  
   - F1 Score  
7. How does the **gap between precision and recall** affect the bank?  
8. Which features **heavily influenced** the model’s outcome?  
9. Will the results be affected by **geographical location**? (**Yes / No**)

---

## Expected Outcome

- Clear understanding of **loan default patterns**
- Identification of **key risk drivers**
- A well-evaluated **logistic regression model**
- Business-oriented **credit approval recommendations**
