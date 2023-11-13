# Module 20 Report

## Overview of the Analysis

This analysis has the purpose of identifying the loaning risks of different clients based on a historical lending activity database. The database includes variables such as loan size, interest rates, borrowing income, and more. The variable 'loan_status' indicates if the risk of each loan, being '0' the representation of healthy loan, and '1' the representation of a high risk. 
For this analysis, it was created a Logistic Regression model, in order to predict loan status and assessing creditworthiness. Initially, the original data was used to create the first model.
In order to prevent biased models, a second model was created using RandomOverSampler. 

## Results

* Machine Learning Model 1:
  * The first model had its accuracy at 94%. The healthy loan had its precision and recall score at 100%, while the high-risk loan had its precision at 87% and its recall score at 89%. 

* Machine Learning Model 2:
  *  The second model had its accuracy at 99%. The healthy loan had its precision and recall score at 99%, having the same results for high-risk loans. 

## Summary

Although the first model had better performance on healthy loans, the second model performed better overall. Considering it is more important to predict the high-risk loans, it is recommended to use the second model, due to its high balanced accuracy score. 
