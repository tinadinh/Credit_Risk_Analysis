# Credit_Risk_Analysis

## Overview of the analysis: 
The world of machine learning offers a wide variety of models that make predictions on your dataset to varying degrees of accuracy, precision, and recall. To test which one is the best for assessing risk in the field of credit, this project uses different techniques to train and evaluate models with unbalanced classes using credit card dataset.

## Results of all six machine learning models:
The results highlights each model's performance when it comes to predicting high risk clients, as to avoid high risk loans which will save the business more money.

### Naive Random Oversampling
- Balanced Accuracy Score: 65%
- Precision: 1%
- Recall: 74%
![ba_ros](https://user-images.githubusercontent.com/33900637/159149628-aec6defb-7031-4b0a-a31c-6f6a6e7d8e36.png)

### SMOTE Oversampling
- Balanced Accuracy Score: 66%
- Precision: 1%
- Recall: 63%
![ba_sm](https://user-images.githubusercontent.com/33900637/159149647-6677e46f-539b-439b-9a94-d1c994aeb310.png)

### Cluster Centroids Undersampling
- Balanced Accuracy Score: 54%
- Precision: 1%
- Recall: 67%
![ba_us](https://user-images.githubusercontent.com/33900637/159149679-a8526217-a42c-4e9a-ba6d-3ebddbebf2fd.png)

### SMOTEENN Combination Over/Undersampling
- Balanced Accuracy Score: 64%
- Precision: 1%
- Recall: 70%
![ba_st](https://user-images.githubusercontent.com/33900637/159149692-0e7f7bc3-41e0-4515-8f9c-25a6140469c9.png)

## Balanced Random Forest Classifier
- Balanced Accuracy Score: 79%
- Precision: 3%
- Recall: 70%
![ba_rf](https://user-images.githubusercontent.com/33900637/159149706-0467146f-b101-4d4b-849b-a9acaeb465bb.png)

### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 93%
- Precision: 9%
- Recall: 92%
![ba_eec](https://user-images.githubusercontent.com/33900637/159149721-1a242975-3beb-4249-b3f7-1089505ff148.png)


## Summary
The results of the six machine learning models that performed the best out of this selection was the Easy Ensemble AdaBoost Classifier with 9% precision. Prioritizing precision in this decision is important because incorrectly identifying a client as high-risk results in a loss of potential business. It is recommended to use this model so that the business look for alternative machine learning models to help in the decision making process. In the best case scenario, the AdaBoost Classifier correctly guesses a high risk client approximately 9/100 times, the other 91 times would result in rejected clients that would have been likely to repay their loans.
