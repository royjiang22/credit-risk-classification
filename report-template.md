# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The goal is to predict credit risks. The dataset provided by the bank has "Size of the loan", "Interest rate on the loan", "Borrower's income",
"Debt_to_Income ratio", "The number of of accounts that the borrower uses regularly", "Derogatory marks on the borrower's credit report", "The borrower's total debt".

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
![Screenshot 2023-03-30 at 8 48 02 PM](https://user-images.githubusercontent.com/114886937/229018191-5a0d4bb6-df75-4cca-a671-2cb7b6ebdbff.png)



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
![Screenshot 2023-03-30 at 8 47 55 PM](https://user-images.githubusercontent.com/114886937/229018199-92862415-5ab0-45b5-82a9-3f378b471e57.png)


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Logistic Regression was used and Random Oversampling was done to do additional testing. 

The model is good for predicting healthy loans but not high risk loans so further refinement is needed to improve accuracy.
