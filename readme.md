# Prosper Loan dataset analysis and visualization
## by Soliman Seif


## Dataset
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest ate), current loan status, borrower income, and many others.


## Summary of Findings
1) The Term parameter have 3 possible values (12, 36 , 60) Months
2) The 3 Quantile values are equal 36 Month
3) Most of the loans length is 36 Months 
4) Most of the loans are in current state.
5) The borrowers which are classified as a home owners are a little more than the borrowes classified as no home owners
6) The ListingCategory values you can find that most of browers selected Debt Consolidation option 
7) Loans with status ChargedOff/Completed having a higher Estimated Effective Yield
8) Loans with Listing Category Home Improvement , Debit Consolidation, Other, Auto, Business, students Use have higher estimated return and estimated loss

## Key Insights for Presentation
Below are the insights for the presentation:
1) removing the data with LoanOriginationDate < 2009-08-01 00:00:00 because some of the interesting fields are not available before that date. 
2) ListingCategory value is analyzed with Term, IsBorrowerHomeowner, LoanStatus
3) Term field value is analyzed with LoanStatus and ListingCategory 

