# PROSPER LOAN DATA 
## by Estitxu Larralde Erasun


## Dataset

The dataset includes 113 937 loans with 81 variables on each loan, including loan amount, borrower APR (annual interest rate), loan status and many more. 

Dataset is too heavy for git-hub hosting. You can download it here if interested: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv 

There is a dictionnary of variables available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing).

## Summary of Findings

I focused on two variables: loan status and borrower APR. I found out that there is in fact a strong correlation between these two features. Indeed, loans classed as unsuccesful (or not paid back to the lenders by the borrowers) had in average a higher interest rate that succesful loans. 

Regarding loan status, it has some correlation with the loan original amount even though the average loan original amount for either unsuccesful or succesful loans is quite similar. It has also a positive correlation with stated monthly income of borrowers (payers of succesful loans earn in average 1000USD more than borrowers of loans that weren't paid back). Finally, regarding loan status, I found that employed and retired borrowers paid back the loans more often than the rest of borrowers (not employed or other).

As for Borrower APR, I was quite surprised to see that I couldn't find any correlation with any of the numerical figures selected (Term, IsBorrowerHOmeowner, Investors, LoanOriginalAmount, Revolving Credit Balance and StatedMonthlyIncome). I only found correlation between the borrower APR and the employment status of the borrowers : employed and retired borrowers got in average a lower interest rate than the rest of borrowers. I visualized these two features together with the loan status to deepen the analysis. I saw that not only a higher borrower apr in average was connected to unsuccesful loans, but also that even succesful loans paid back by unemployed and borrowers from 'other' group, got a higher average interest rate than unsuccesful loans granted to employed and retired borrowers.


## Key Insights for Presentation


For the presentation, I'm going to focus in the correlation between loan status and borrower APR and the correlation of both with employment status. 

I will first introduce the distribution of loan status and borrower APR. Then I will plot Employment Status after grouping some of the values into 'employed' status (self-employed, employed). 

I will continue with bivariate plots for our two variables of interest (loan status and borrower APR), then borrower APR and employment status. 

I will end the presentation by deepening into the relationship between loan status, borrower APR and employment status by visualizing the three of them together in an adaptation of bivariate barplot

