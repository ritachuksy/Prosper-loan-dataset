# (Prosper Loan Dataset)
## by (Rita Chukwuma)


## Dataset

> The Prosper loan dataset comprises of 113937 loan entries with 81 attributes on each loan, including loan amount, borrower rate, borrower income, current loan status etc.

> The dataset is subdivided into two main categories:

> The Loan performance information: Metrics evaluating the risk associated with the loans such as Prosper Rating and Estimated Returns, Prosper Score etc.

>The borrower information: Basic attributes of the borrowers such as stated monthly income, income range, employment status, interest rate, loan status, Bank card Utilization etc. 

## Summary of Findings

> In this dataset investigation, we are trying to find out the:

> 1.	The key factors that influence the borrowers APR and investor return.
> 2.	Also, we want to find out the loan performance.

> While exploring the data, I discovered that to measure the loan performance that some feature engineering has to be done on the data in other to calculate the Actual Returns using Prosper's Net Annualized formula. However, we discovered that the actual returns isn’t accurate  due to missing information, so we couldn’t get an accurate calculation.

>The bivariate exploration revealed first, the borrower APR is negatively correlated with the loan original amount, which means, the more the loan amount, the lower the APR. It also shows that at different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount. The stated monthly income also has a strong effect on the borrower APR, which causes a decreases in BorrowerAPR with an increase in income. 
From our box plots, I discovered a trend of median estimated returns decrease as the borrowers employment status increased. This makes sense as borrowers with a higher income can demand the most competitive rates from creditors. The trend between credit rating and estimated returns shows that the higher the credit rating the higher the investors estimated returns while on the other variable, it shows that borrowers without source of income tends to give better returns than the rest, which is ridiculous. However I noticed that borrowers with higher monthly incomes often received better credit ratings and score.
The multivariate exploration revealed again that the credit score and BorowersAPR happens to be stronger predictors for predicting estimated returns. 
Also, we can say that increase in both loan amount and monthly income decreases the borrower APR.


## Key Insights for Presentation

> During this investigation, I focus mainly on finding out the variables that influences borrowers APR and investors Estimated return. I started by introducing the estimated return by plotting its distribution and I tried calculating the actual return by using Prosper's Net Annualized formula but couldn’t get accurate result due to some other factors that are far-fetched. 
However, I used various plots, to explore extensively on the relationship among all my variables of interest.
