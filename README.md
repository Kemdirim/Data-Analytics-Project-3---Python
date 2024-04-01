# Prosper Loan Data Exploration
## by Kemdirim Njoku


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset can be found here https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv , with feature documentation available here https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0 .

## Summary of Findings

In the exploration, I found that there was a strong relationship between the
Monthly Loan Payment and the Loan Original Amount, then i checked for the effects of the Loan Term and the Income Range.

The relationship between the Monthly Loan Payment and Loan Original Amount is linear even when plotted on a standard scale.

I had expected to see a bit of correlation between the Monthly Loan Payment and the BorrowerAPR, but surprisingly they were negatively correlated. Also, I had some assumptions that the Monthly Loan Payment would be influenced by strongly by the Stated Monthly Income (i.e A higher Monthly Income would attract a higher Monthly Loan Payment - Positive correlation) but a weak correlation was seen. 

In the same way,I had expected a positive correlation between the Loan Original Amount and the BorrowerAPR but instead a negative correlation was observed. Only little interaction was observed between the categorical features (Term, Income Range, Employment Status).


## Key Insights for Presentation

For the presentation, I focus on the influence of a selected features namely, Loan Original Amount, Stated Monthly Income, Term and Income Range on Monthly Loan Payment. First, I introduce the Monthly Loan Payment variable, and then the pattern in distribution of Loan Original amount, after that plot the scatterplot.

Moving on, I introduce the categorical variables Term and Income range. To begin, I use the regplot of Monthly Loan Payment and Loan Original Amount across Term. I'm looking at the categorical variable Term as it gives us a clear picture of how the Monthly Loan Payment can be affected by the Loan Term.

Another categorical variable, Income range is covered afterwards still using a regplot of Monthly Loan Payment and Loan Original Amount. To better understand how the Monthly Loan Payment can be affected by different loan features. 