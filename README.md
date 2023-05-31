# credit-risk-classification

## Overview of the Analysis

 This Analysis of a dataset which is a historical lending activity from a peer-to-peer lending services company
 utilizes Supervised learning machine models for predicting the creditworthiness of borrowers.

* The model evaluates customer data for loan status describing as healthy or at risk of default basd on the loan size, interest rate, borrower income,debt_to_income, number of accounts,total debt as well as derogatory marks .

* Y value - dependent variable was defining the loan status which describes if the loan was healthy or at risk.
& X values- Independent Variables was defining the interest rate, loan size,  borrower income, debt to income ratio, number of accounts and derogatory marks.

* The Data was split into two models - Training and testing
* A logistical regression model was created and the data was fit with original data as well as another logistical regression model was created using random oversampled data and then the model's performance was evaluated. The trained model was used to make the predictions about the data. 
*
## Results
* Machine Learning Model 1:

1. Balanced Accuracy was 95%
2. Precision for predicting healthy loans was 100% and Recall for predicting healthy loans was 99%.
3. Precision for predicting healthy loans was 85% and Recall for predicting healthy loans was 91%.

 * Machine Learning Model 2:

1. Balanced Accuracy was 99%.
2. Precision for predicting healthy loans was 100% and Recall for predicting healthy loans was 99%.
3. Precision for predicting healthy loans was 84% and Recall for predicting healthy loans was 99%.

## Summary

The Machine learning models predict a healthy lending trends and oversampling the data randomly enhanced the scope of getting higher balanced accuracy and recall scores. Having higher recall values models  can more accurately predict the risky loans . The models  have proven to be providing with precise healthy loans prediction but has a caviar with having both false positive and false negatives can contribute to inefficient prediction of high risk loans.
