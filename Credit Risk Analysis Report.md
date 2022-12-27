# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to identify the creditworthiness of borrowers through buidling supervised machine learning model.
* Dataset of historical lending activity from a peer-to-peer lending services company will be used for buidling the model.
* Dataset hs 2500 (or 3%) is classified as risky loan out of total 77,526 loan.
* Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans.
* Techniques of data resampling and ensemble will be used to handle this class imbalance. 

## Results

* Machine Learning Model 1:
  * Logistic regression model with original data:
  * balanced accuracy of 95.2%, predicting healthy loan with 100% precisiona and 99% recall. 
  * Prediction for high risk loan is moderately precise (85%) with reasonably high recall of 91%



* Machine Learning Model 2:
  * Logistic regression model with original data:
  * balanced accuracy of 99.3% (+4.1pp v Model 1), predicting healthy loan with 100% precisiona and 99% recall. 
  * Prediction for high risk loan is moderately precise (84%) with improved recall rate of 99% (+8pp v Model 1).

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* In the context of lending services, conservative approach as to minimised the exposure to high-risk loan is preferred. Therefore, a model that minimised false healthy loan is preferred.
* Given that model 2 has higher overall accuracy score, and higher recall rate when predicting risky loan, compared to model 1.
* Thus, model 2 is the preferred model.

