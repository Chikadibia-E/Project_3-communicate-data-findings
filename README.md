# Exploration of Loan Data from Prosper
## by Chikadibia F. Ezeh


## Loan Data from Prosper
> [Prosper System](https://www.lawinsider.com/dictionary/prosper-system) means the proprietary, internet-based peer-to-peer lending platform developed by the Member and transferred to the Company, through which Borrowers may obtain Borrower Loans and qualified investors may purchase Securities.

>[Loan Listing](https://www.lawinsider.com/dictionary/loan-listing) means a request by a Borrower to borrow money on the terms of a Loan through the Prosper System.

>This is a Loan Listing dataset which contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The exploration here will only be focused on select variables of the dataset, for the purpose of this project, focus shall be restricted to about 15 selected dataset columns/variables out of the 81 count. Brief description of these variables are given as thus;

>**ListingNumber**: The number that uniquely identifies the listing to the public as displayed on the website.

>**CreditScoreRangeLower**: The lower value representing the range of the borrower's credit score as provided by a consumer credit rating agency.

>**ListingCategory**: The category of the listing that the borrower selected when posting their listing: 0 - Not Available, 1 - Debt Consolidation, 2 - Home Improvement, 3 - Business, 4 - Personal Loan, 5 - Student Use, 6 - Auto, 7- Other, 8 - Baby&Adoption, 9 - Boat, 10 - Cosmetic Procedure, 11 - Engagement Ring, 12 - Green Loans, 13 - Household Expenses, 14 - Large Purchases, 15 - Medical/Dental, 16 - Motorcycle, 17 - RV, 18 - Taxes, 19 - Vacation, 20 - Wedding Loans

>**CreditScoreRangeUpper**: The upper value representing the range of the borrower's credit score as provided by a consumer credit rating agency.

>**BorrowerAPR**: The Borrower's Annual Percentage Rate (APR) for the loan.

>**EmploymentStatus**: The employment status of the borrower at the time they posted the listing.

>**AmountDelinquent**: Dollars delinquent at the time the credit profile was pulled.

>**DebtToIncomeRatio**: The debt to income ratio of the borrower at the time the credit profile was pulled. This value is Null if the debt to income ratio is not available. This value is capped at 10.01 (any debt to income ratio larger than 1000% will be returned as 1001%).

>**IncomeRange**: The income range of the borrower at the time the listing was created.

>**RevolvingCreditBalance**: Dollars of revolving credit at the time the credit profile was pulled.

>**AvailableBankcardCredit**: The total available credit via bank card at the time the credit profile was pulled.

>**OpenRevolvingMonthlyPayment**: Monthly payment on revolving accounts at the time the credit profile was pulled.

>**LoanStatus**: The current status of the loan: Cancelled,  Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue. The PastDue status will be accompanied by a delinquency bucket.

>**CurrentCreditLines**: Number of current credit lines at the time the credit profile was pulled.

>**BankcardUtilization**: The percentage of available revolving credit that is utilized at the time the credit profile was pulled.


## Summary of Findings

> In all these analytical visual explorations, attempts were made to investigate the the performance of the listed credits. In all the explorations, the following were found:

>> 1. The performance of the listed credit were generally good.

>> 2. Majority of borrowers in previous debts borrowed for loan consolidation.

>> 3. Improper or incomplete documentation, especially in the borrowers income ranges did not allow for exhaustive analysis

>> 4. The correlation between numeric variables and amounts amount delinquent variables are generally weakly negative except for BorrowerAPR which positively influenced delinquency.

## Key Insights for Presentation

> Most of the prevous debts of borrowers in the listing were consolidated. i.e credits listed to settle prevous debts, as such, the general credit performance picture was a good one.