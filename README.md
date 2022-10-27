# Prosper Loan Data Exploration

## Dataset

The dataset consist of information regarding 113,937 loans dispersed by the
prosper loan company, including features like loan term, duration, amount,
creditscore, borrower rate, etc. The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

## Summary of Findings

In the exploration I found that there's a strong relationship between
prosper rating and loan amount that is, the higher the borrower rating,
the higher the loan amount they have access to. Higher prosper rating
also means generally more favourable loan rate although this was not
necessarily the case before 2009. The borrower `rating` became a stronger
deciding factor for `BorrowerRate` after 2009. I've also found that borrowers
with homes are more eligible for higher loan amounts.


## Key Insights

In my presentation I focus on the influence of home ownership status and
prosper/credit rating on loan amount and borrower rate. I also evaluate how
the borrower rate and loan amount interact with each other.

I begin by showing the distribution of loan amount and borrower rate. Then I
show the relationship between home ownership status vs loan amount. Afterwards,
I plot the prosper rating vs loan amount in a barplot, faceting by home ownership
status. Next I plot prosper/credit rating vs loan original amount in a scatter
plot, then I do prosper/credit rating vs borrower rate in a violin plot. Fianlly I
plot loan amount by borrower rate and prosper/credit rating. Again I plot loan
amount by borrower rate and prosper/credit rating facetted by pre/post 2009.