# Credit_Risk_Analysis

## Overview of the analysis:
The data of credit risk is unbalanaced classification problem, with using different models, I will
train and evaluate different models. The results will be compared and contrasted to show which model 
is the best fit for evaluating credit risk.

## Results: 

Below is a list of all the results of each the 6 different models used.

Oversampling
	Accuracy score: 0.72
	Precision: 0.99
	Recall: 0.72
SMOTE Oversampling
	Accuracy score: 0.73
	Precision: 0.99
	Recall: 0.73
Undersampling
	Accuracy score: 0.70
	Precision: 0.99
	Recall: 0.66
SMOTEENN 
	Accuracy score: 0.73
	Precision: 0.99
	Recall: 0.73
Balanced Random Forest
	Accuracy score: 0.73
	Precision: 0.99
	Recall: 0.84
Easy Ensemble Adaboost
	Accuracy score: 0.93
	Precision: 0.99
	Recall: 0.94

## Summary: 

In the resampling notebook, the results remain about the same with little difference. Undersampling has the lowest accuracy score of .70. 
With the balanced random forest, there is improvement in the recall score meaning more samples have the correct predicitions. 
Using Easy Ensemble has the best results out of all six models with a accuracy score of 0.93 and a recall of 0.94. The easy ensemble classificer 
as the highest rate to correctly predicit credit risk levels.
