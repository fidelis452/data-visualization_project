# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The dataset contains 106312 observation obtained from prosper loan and has 81 features which include LoanStatus, Term, CreationDate, LoanOriginalAmount among others. 

The features are decribed in the data dictionary [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing)

The dataset can be found via the link [Prosper Loan Dataset](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)

## Summary of Findings

There is a strong relationship in the exploration between variables such:

**Term and BorrowerAPR** The two varibles are directly proportional meaning, as the Term length increases, the Borrower rate also increases. 

**Loan Original Amount and Income Range**

I verified the relationship between Loan original amount and the income raange using a violin plot on which i was able to see that those with an IncomeRange of 100,000+ acquired a loan of between 0 and 30,000.

**Monthly stated income vs Loan Status**

Loans of borrowers with monthly income of 2,500 and below were cancelled which could be due to high amount of monthly loan payments. However,majority of borrowers with an income of above 5,000 had their loans at the final payment, some completed,some current and also some had their loans past due.

**Monthly stated income vs  monthly loan payment**

Borrowers with higher income had higher monthly loan payments.

**Employment Status vs the loan original amount**

It was observed that employed borrowers accessed higher loans sizes than the NotEmployed/part-time borrowers.

## Key Insights for Presentation

The focus of the presentation will be on the four relationships discussed above as they are the main focus of the exploration. 

I will start with finding the frequency of LoanStatus, Listing category to find out the reason for borrowers to take the loans. This will be followed by the blotting the distributions to verify the relationship between the variables below :-

- Loan Original Amount and Income Range
- Monthly stated income vs Loan Status
- Monthly stated income vs  monthly loan payment
- Eployment Status vs the loan original amount
"# data-visualization_project" 
