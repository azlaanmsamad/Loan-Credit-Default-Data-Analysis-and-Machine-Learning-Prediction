# Loan-Credit-Default-Data-Analysis-and-Machine-Learning-Prediction
This repository contains exploratory Data analysis to a bank loan default dataset. This is done in order to clean the data and make it usable for machine learning prediction.

Observation on Data Analysis: 
- Highly correlated variables are (Applicant's Income & Loan Amount) and (Credit History & Loan Status)
![alt text](https://github.com/azlaanmsamad/Loan-Credit-Default-Data-Analysis-and-Machine-Learning-Prediction/blob/master/Tutorials/coursera/exploratory%20data%20analysis/plots/corr.png)


Feature Engineering:
- Total Income: Combined the Applicant Income and Co-applicant Income. If the total income is high, chances of loan approvalmight also be high.
- EMI: EMI is the monthly amount to be paid by the applicant to repay the loan. Idea behind making this variable is that people who have high EMI’s might find it difficult to pay back the loan. We can calculate the EMI by taking the ratio of loan amount with respect to loan amount term.
- Balance Income: This is the income left after the EMI has been paid. Idea behind creating this variable is that if this value is high, the chances are high that a person will repay the loan and hence increasing the chances of loan approval.




