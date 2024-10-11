# Credit Risk Analysis Report

## Overview of the Analysis

### Description

This analysis aims to leverage various machine learning techniques to train and evaluate the performance of Logistic Regression Models in identifying the creditworthiness of borrowers. The models were trained using  Logistic Regression model. The predictive variables in the model are the labels 0 (healthy loan) and 1 (high-risk loan).

In the process of constructing the model, the dataset was split into features and labels, and further divided into training and testing sets.

Machine Learning Model was built by instantiating a logistic regression model and training with the original training sets (X_train, y_train), fitting it to the training sets, and using it to generate predictions.

The performance of this model was evaluated based on the balance accuracy score, the confusion matrix, as well as the precision score, recall score, and f1-score in the classification report.

## Results

* Machine Learning Model trained on the original data, gives an accuracy of 99.4% in predicting the 2 labels.
* The model is very good at predicting the healthy loans, with both precision and recall scores of 1.00.
* However, the model's performance in predicting the high-risk loans can be improved. The precision score for high-risk loans is 0.87, indicating that only 87% of actual high-risk loans were correctly predicted.
* The recall score for high-risk loans is 0.95, indicating that the model identified 95% of all high-risk loans in the dataset.

## Summary

Based on the analysis, the logistic regression model trained on the original data gives an 99.4% accuracy of predicting the two labels. The model is very good at predicting the healthy loans, as the f1-score is 1.00. For high-risk loans, the recall of 0.95 is strong, meaning the model is very good at identifying most of the actual high-risk loans. However, the model's performance in predicting the high-risk loans can be improved, as it only correctly predicted 87% of all actual high-risk loans, meaning that 13% of the predicted high-risk loans are actually healthy. 
<br>
Yes, I can recommend this model if the goal is to prioritize correctly identifying high-risk loans (since it has a high recall for high-risk loans). However, the company should be aware of the trade-off that some healthy loans (13% of the predicted high-risk loans) are being incorrectly flagged as high-risk. If this level of false positives is tolerable, then the model is suitable.
