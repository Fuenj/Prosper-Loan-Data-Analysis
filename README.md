# Prosper-Loan-Data-Analysis
## Dataset

The Prosper loan dataset comprises of 113937 loan entries with 81 attributes on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others, from the year 2009-2014. There are two main categories:

- Borrower information: Basic attributes of the borrowers such as annual income, condition of employment, interest rate, loan status, etc.
- Loan performance information: Metrics evaluating the risk associated with the loans such as Prosper score and bank card utilization, etc.
There were some elements that need to be fixed, in order to create interesting and trustworthy analyses and visualizations.


## Summary of Findings

The objective of this work is to investigate factors affecting borrower rate and loan amount:

In the exploration, I found that there was a moderate and negative correlation between interest rate and Loan amount.
Also, there is some negative and strong relationships between the categorical/ordinal variables selected and the interest rate. As an example, Unemployed people have more restrictive credit condition (higher rate) than the people who have jobs. The second factor is that borrowers who have collaterals(or homeowners) have lower rates than those who doesn't have any collateral(house).The third determinant is that borrowers with higher monthly salaries tend to get a lower lending interest rate. So it's a good determinant as well. Similarly, there is a strong indication that the Prosper score and rating is an excellent determinant factor of borrower's rate. We can conclude that the higher the score , the lower the rate. In other words, borrowers with AA prosper ratings could expect an APR that will likely fall into the 2-15% range, whereas borrowers with bad ratings (HR) could expect their interest rate to go as high as 40%!

Moreover, i extended my investigation of loan and interest rate against the most explanatory determinants.

- The multivariate exploration here showed that for people who are delinquent (defaulted,past due, charged-off payments), banks applies more restricted credit conditions (higher interest rates). Also these people have lower credit scores than people with good status.
- An other point, there is a difference between the rates applied according to the maturities. In other words, the rates applied on 5-year loans are generally higher than the rates applied on other maturities, regardless of the prosper rating (with the exception of the E rating (same rates for 3 and 5 years loans ) and the HR rating). This is obvious, when the duration is longer it increases the risk of this operation involving a rise in rates. Of course, as it is always mentioned, the rates are the lowest, for individuals with a good rating. Interestingly, for HR rating, only 3 years loans are observed in this dataset.
- In parallel, for all Prosper Ratings except for "A",and "AA", Defaulted and charged off loans usually have a higher Borrower APR compared to completed or current loans(good records).
- Finally, having a collateral and a higher wage help getting higher loan amount. It is clearly visible that being a home owner is a very important element to get a higher loan amount.


## Key Insights for Presentation

For the presentation, I focus on just the influence of some variables on interest rate and loan. I started by introducing the loan status 
and loan amount variable, by plotting their distribution.

Afterwards, i have used violin plots, box plots and line plots to dig deeper on the relationship between my variables of interest (interest rate and loan) and the explicative variables. 
