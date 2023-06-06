# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The goal of this analysis is to provide a usable model to identify low and high risk lendees. 

* Explain what financial information the data was on, and what you needed to predict.
The financial information provided details about prospect lendees and wether they would be low or high risk borrowers. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The variables used to predict wether lendees would either be low or high risk are loan amount, interest, accounts, income, debt to income ratio, derogatory marks, and total debt.

* Describe the stages of the machine learning process you went through as part of this analysis.
Training stage, Testing stage, and Modeling.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
Logistic Regression modeling was used to detiermine probability of discrete outcome given an input variable. Resampling had to be conducted due to the biased nature of the data, skewing towards low risk over high risk loans. When resampling was conducted, the results were more reasonable. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * The first Machine Learning Model accurately depicted low risk loans but performed subpar on high risk ones
  * precision score of 100% vs 85%
  * recall of 99 vs 91%
  * f1-score of 100% vs 88%



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * The second Machine Learning Model performed the same on low risk loans but alot better on high risk loan category
  * precision score of 100% vs 84%, a slight decrease
  * recall of 99 vs 91%, a 6% increase on true positive rate
  * f1-score of 100% vs 91%, a slight increase in overall accuracy

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
The second model performed better because it is showing a higher Recall or True Positive Rate and f1 score or overall accuracy.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
For banking and finance, it would be more useful to identify high risk lendees as they are more than likely to default on their loans.

