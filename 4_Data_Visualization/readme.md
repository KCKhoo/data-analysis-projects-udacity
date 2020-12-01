# (Effects of Loan Features on Loan's Status Outcome)

## by (Khoo Kian Chong)


## Dataset

>This document explores Prosper Loan dataset which contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The explanation for each variable can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

>LoanOriginalAmount and MonthlyLoanPayment are highly correlated with one another. There is a slight correlation between StatedMonthlyIncome and MonthlyLoanPayment and between LoanOriginalAmount and StatedMonthlyIncome. There was also an interesting relationship observed between loan status and three numeric variables of interest (LoanOriginalAmount, MonthlyLoanPayment and StatedMonthlyIncome). Defaulted and charged-off loans have lower original loan amount, monthly loan payment and stated monthly income than other loan's outcome status. Current loans have higher original loan amount, monthly loan payment and stated monthly income than other loan's outcome status. As original loan amount, monthly loan payment and stated monthly income have some correlation with one another, it is not suprising to find out that loan's outcome status have similar relationship with these features. Defaulted and charged-off loans have higher BorrowerAPR than other loan's outcome status. Whereas loans that are currently ongoing or in final payment process have lower BorrowerAPR. Loans with highest debt-to-income ratio are defaulted loan, followed by past due loans and charged-off loans.

>Defaulted, charged-off, past due and FinalPaymentInProgress loans are mostly loans with low original loan amount (<10000) but high annual percentage rate (APR). Completed loans are mostly loans with low original loan amount (<10000) and APR of any values (could be low or high). Current loans have loan amount less than 15000 and APR of any values. It is interesting to see that a lot of current loans have loan amount between 12500 and 15000, which is not really seen in other loan's outcome status. This may suggest that Prosper is increasing the loan amount recently. From the data displayed via heatmap, it seems like loans with small loan amount and small APR are likely to be repaid by the borrowers. For loans with small loan amount and high APR, it is difficult to deduce the loan's outcome status solely based on LoanOriginalAmount and BorrowerAPR.


## Key Insights for Presentation

>Relationships between two loan features - loan amount and annual percentage rate - and loan's status outcome were presented. The presentation started off by showing the distributions of loan amound and annual percentage rate. Subsequently, a boxplot was used to show the relationship between each loan feature and loan's status outcome. 