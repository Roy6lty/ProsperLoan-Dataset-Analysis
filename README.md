# ProsperLoan-Dataset-Analysis
Data Analysis


# (Loan Prosper Dataset)
## by (Ayobami Olowoleru)
 
 
## Dataset
 
- The data consists of information regarding 113864 Loans, including LoanYeild, LoanStatus, BorrowAPR, and other loan Variables. The dataset can be found on the Udacity website
repository for Data Analysis Final Project  [here]( https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv).
With feature documentation available
[here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).
 
## Summary of Findings
-In the exploration, I found a significant impact on the Lenderyeild and LP_GrossPriciplalLoss.
The relations, LenderYeild, had surprisingly increased significantly with the change of the Grading system and is good correlation with BorrowAPR, LP_GrossPrincipalLoss also showed significant reduction when plotted across the rating system.
 
-Interestingly, higher Prosperscore gets Lower APR rates, which produces lower yield for the lender.
Expected relationships were found in the association between the LoanOrignalAmount, and LoanMonthlyPayment. A Positive small correlation was observed between LoanOrignalAmount and LoanMonthlyPayment, but both variables show a negative correlation with LenderYield There was also a small interaction in the categorical Grading System. Borrowers with a high ProsperScore show a negative correlation with LenderYeild, and the reverse is observed for Borrowers with Low ProsperSore.
 
 
 
## Key Insights for Presentation
 
- For the Presentation, I focus on the impact of the PropserRating System on the LenderYeild and
LP_GrossPricipalLoss variables leave out all the other variables. I start by Introducing the LenderYeild,
followed by the pattern Distribution histogram.
Next, I will introduce each of the Grading systems plotting them against the LenderYeild and LP_GrossPricipalLoss
using a Boxplot, I am only looking for differences in quartile range between each Grading System.

- Afterward, I would show the magnitude of the difference between each system using a clustered bar chart,
where I will be highlighting the difference between the two systems.
 
- Next, I introduce the Prosperscore and its impact on the Loan Default and Chargeoff rate with  loan status as
a categorical variable
