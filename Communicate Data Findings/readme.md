# Communicate Data Findings - Exploration of Loan Data from Prosper

## Project Overview
This analysis explores a data set containing 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The **goal** of teh analysis was *assess factors that affect borrower's APR for the loans*.

## Dataset
The [Loan Dataset](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000contained) contain data for **113,947 **
loans with **[81 variables](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)**
on each loan. The variables include loan amount, borrower APR (or interest rate), term, occupation, current loan status,
borrower income, and many others.
A preliminary wrangling was done to clean the dataset and it includes:
- renamed variables
- changed variable type
- dropped rows without Prosper Score
- dropped inconsistent data (eg. prosper score of 11 as Prosper score range from 1-10). 
- dropped columns not relevant to the analysis.
At the end of the preliminary wrangling, a dataset consisting of **83,397** loans and 28 variables was born. 



## Summary of Findings
The following were the findings from this investigation.
1. Prosper Score, Credit Score, and Loan amount are negatively correlated to Borrower's APR
2. Loan amount and prosper score, credit score and  monthly income are  positively correlated to loan amount.
3. Borrowers that are home owners have lower borrower APR compared to non-home owners. Furthermore, home owners have higher credit score and access to higher loan amount. 
4. Although loan amount and term has a positive relationship, on further exploration with a multivariate plot, it came out that when Borrower's APR is included it neutralises the effect of term on loan amount.


## Key Insights for Presentation
For the presentation, I focused on the effect of prosper score, credit score and loan amount on borrower's APR. I started by introducing and describing borrower APR - including a histogram.
Afterwards, I introduce each of the numerical variables showing the correlation with borrower's APR using a correlation plot. I also show the effect of home ownership on the variable of interest.


## Some References
[Present your data science project with jupyter slides](https://medium.com/learning-machine-learning/present-your-data-science-projects-with-jupyter-slides-75f20735eb0f)