# LoanTap_LogisticRegression
Business Case: LoanTap_LogisticRegression

# LoanTap_LogisticRegression 📊

Welcome to the Jamboree Linear Regression project! 🎉 

## About LoanTap

LoanTap is an online platform committed to delivering customized loan products to millennials. They innovate in an otherwise dull loan segment, to deliver instant, flexible loans on consumer friendly terms to salaried professionals and businessmen.
The data science team at LoanTap is building an underwriting layer to determine the creditworthiness of MSMEs as well as individuals.

## Business Problem 📈
LoanTap deploys formal credit to salaried individuals and businesses 4 main financial instruments:
- Personal Loan
- EMI Free Loan
- Personal Overdraft
- Advance Salary Loan
This case study will focus on the underwriting process behind Personal Loan only

## Problem Statement:
Given a set of attributes for an Individual, determine if a credit line should be extended to them. If so, what should the repayment terms be in business recommendations?

## Dataset/ Column Profiling:📋

The dataset at the heart of this exploration. Here are some of the key features:

## Data Dictionary

- **loan_amnt**: The amount of the loan applied for by the borrower. If the credit department reduces the loan amount, it is reflected in this value.
- **term**: Number of payments on the loan in months (either 36 or 60).
- **int_rate**: Interest rate on the loan.
- **installment**: The monthly payment the borrower owes if the loan is originated.
- **grade**: Loan grade assigned by LoanTap.
- **sub_grade**: Loan subgrade assigned by LoanTap.
- **emp_title**: Job title provided by the borrower when applying for the loan.
- **emp_length**: Employment length in years, ranging from 0 (less than one year) to 10 (ten or more years).
- **home_ownership**: Home ownership status provided by the borrower during registration or from the credit report.
- **annual_inc**: Self-reported annual income provided by the borrower during registration.
- **verification_status**: Indicates if income was verified by LoanTap, not verified, or if the income source was verified.
- **issue_d**: The month the loan was funded.
- **loan_status**: Current status of the loan (Target Variable).
- **purpose**: Category of the loan request provided by the borrower.
- **title**: Loan title provided by the borrower.
- **dti**: Debt-to-income ratio, calculated using the borrower’s total monthly debt payments (excluding mortgage and the requested LoanTap loan), divided by the borrower’s self-reported monthly income.
- **earliest_cr_line**: Month the borrower's earliest reported credit line was opened.
- **open_acc**: Number of open credit lines in the borrower's credit file.
- **pub_rec**: Number of derogatory public records.
- **revol_bal**: Total revolving credit balance.
- **revol_util**: Revolving line utilization rate, or the amount of credit the borrower is using relative to available revolving credit.
- **total_acc**: Total number of credit lines currently in the borrower's credit file.
- **initial_list_status**: Initial listing status of the loan (values: W, F).
- **application_type**: Indicates whether the loan is an individual or joint application.
- **mort_acc**: Number of mortgage accounts.
- **pub_rec_bankruptcies**: Number of public record bankruptcies.
- **address**: Address of the individual.


## 🚀 Mission 🚀

To get you started, here are some questions you might consider:

## Project Summary
## Analysis Questions and Insights

1. **Percentage of Customers with Fully Paid Loans**: 
   - What percentage of customers have fully paid their loan amount?

2. **Correlation Analysis**:
   - Comment on the correlation between `Loan Amount` and `Installment` features.

3. **Home Ownership**:
   - The majority of people have home ownership as **[insert most common category here]**.

4. **Loan Grade and Payment Likelihood**:
   - People with grades ‘A’ are more likely to fully pay their loan. **(True/False)**

5. **Top Job Titles**:
   - Name the top 2 afforded job titles: **[insert top job title 1]** and **[insert top job title 2]**.

6. **Primary Focus Metric for Banks**:
   - Thinking from a bank's perspective, which metric should our primary focus be on?
     - ROC AUC
     - Precision
     - Recall
     - F1 Score

7. **Precision-Recall Tradeoff**:
   - How does the gap in precision and recall affect the bank?

8. **Influential Features**:
   - Which features heavily affected the outcome?

9. **Geographical Impact**:
   - Will the results be affected by geographical location? **(Yes/No)**

Feel free to replace the placeholders with specific insights or values as needed!


## Concepts Used 
- Exploratory Data Analysis
- Feature Engineering
- Logistic Regression
- Precision Vs Recall Tradeoff

## 📈 Let's Get Exploring 📊

Now that you're armed with questions and a powerful dataset, it's time to embark on your journey. Feel free to fork this repository, clone it to your local machine, and start diving into the code and data. Don't forget to share your findings and insights with the community.

Remember, the more we learn from this data, the better we can help companies like Jamboree around the world! 🌎🍿

Happy learning! 🚀👨‍💻🎬
