# Exploring Prosper Ratings
## by Joel Hayhow


## Dataset

> The dataset chosen is ProsperLoanData. It contains nearly 114000 loans borrowed plus variables associated with each. There are 81 variables given for each loan.

A full description of each variable can be found here: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

This description was provided by Udacity.

The dataset was also sourced from Udacity.


## Summary of Findings

> The first variable to be explored was the yield for the lender on each loan. The yield is the interest rate minus the servicing fee. It is a measure of how the lender can profit from a loan. Since the project investigates how a chosen few variables impact yield, the lender yield distribution was investigated first and was found to be bimodal. Both a kernel denstiy estimate and a histogram showed the the bimodality of the distribution.

> Both credit score and Prosper Rating, two key indicators of loan reliability, follow a normal distribution.

> The fees paid by investors - the sum of the servicing fee and the collection fee - are very strongly skewed right. This means the vast majority of fees are in the bracket 0-100 dollars. The fees do not correlate at all with loan yield and follow a completely different distribution.

> Two key indicators of loan reliability, credit score and Prosper Rating, do not correlate well with effective yield. However, by dividing the effective yield data into subgroups corresponding to specific Prosper Ratings and credit scores, it was found that the standard deviation of these subgroups correlates strongly and negatively with both Prosper Rating and credit score. The standard deviation of the effective yield represents the range of likely effective yields for a given loan. This made sense as the higher the Prosper Rating, the lower the standard deviation of the effective yield. 

> Surprisingly, there is very little relationship between credit score, effective yield, total investor fee and Prosper Rating.

> The relationship between monthly loan repayment and original loan amount was investigated for different employment statuses. It was found that the strongest correlation was for borrowers who were either retired or part-time. This means that those groups likely only take a certain type of loan.

> There was also strong correlation for those in full-time employment, but several gradients were observed. This showed that full-time workers tended to take out loans under a range of conditions (e.g. interest rate).



## Key Insights for Presentation

> Key Insight 1: There is very little correlation between Prosper Loan Rating, credit score, total fee per loan paid by investors, and the effective yield per loan. This is surprising as Prosper Rating is the rating the company actually gives each loan.

> Key Insight 2: The standard deviation of effective yield correlates negatively and strongly with both Prosper Rating and credit score.

> Key Insight 3: There is a strong positive correlation between the original amount borrowed and the monthly loan repayment. This correlation was investigated for different employment statuses. It was strongest for borrowers who were part-time or retired. There was also a strong positive correlation, but a greater spread, for full-time borrowers. The conclusion is that part-time or retired borrowers accept loans under a smaller range of conditions than those in full-time work. 







