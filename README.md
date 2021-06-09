# DebtCollecting_Project
Question 1:Debt RepaymentAt the end of every month interest is added to a debt (initially 100) and then repayments are taken off.  The interest is a fixed percentage of the current debt.  The repayment is also a fixed percentage of the debt (after the interest has been added) or 50, whichever is larger.  If the repayment is greater than the debt it is reduced to match the debt.  The cycle of interest and repayment is continued until the debt has been reduced to 0 and paid off.
For example, suppose the interest is 10% and repayments are 50%:
•At the end of the first month the interest is 10, increasing the debt to 110;
•The repayment is 55 (50% of 110) leaving the debt at 55;•At the end of the second month the interest is 5.5, increasing the debt to 60.5;
•The repayment is 50 (as 50% of 60.5 is less than the minimum amount), leaving the debt at 10.5;
•At the end of the third month the interest is 1.05, increasing the debt to 11.55;•The repayment is 11.55 (the minimum payment of 50 is reduced to match the debt) and the debt is paid off.
•The total amount repaid on the debt is 116.55When calculating percentages the amount is rounded up to 2 decimal places.  
E.g. 10.201 and 10.207 would both be rounded up to 10.21.1
(a) [ 26 marks ]Write a program that reads in the interest percentage followed by the repayment percentage.  Percentages will be integers between 0 and 100 (inclusive).You should output the total amount repaid.You will always be given input that allows the debt to be paid off.Sample run 110 50116.551
(b) [ 2 marks ]Given an interest percentage of 43% and a repayment percentage of 46%, how many payments will be made to pay off the debt?1
(c) [ 3 marks ]Which interest and repayment percentages (integers between 0 and 100) lead to the largest amount repaid on a debt that is paid off?
