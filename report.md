# Credit Risk Analysis Report

## Overview of the Analysis

Based of the lending_data.csv dataset, it is a synthetic csv of historical lending activity from a peer-to-peer lending services company, the dataset was used to determine the creditworthiness of borrowers. The performance of the machine learning model used in this analysis to determine credit worthiness of borrowers and predict credit risk, is a Logistic Regression Model that evaluates the model's performancce by confusion matrix and classification report. The loans were classified as '0' being a healthy loan of low risk of default, or '1' being high-risk loan of default. The data was split and divided into training and testing for evaluation using accuracy, precision, recall and the confusion matrix.

## Results

#### Logistic Regression Model

Accuracy Score

- 99% of the loans were correctly classified

Precision Score

- 0: 100%; the majority being 97% of the data, of negative predictions that were healthy loans of low risk of the training data
- 1: 84%; the minority being 3% of the data, of positive predictions that were high-risk loan

Recall Score

- 0: 99%; positive predictions that were correct
- 1: 94%; negative predictions that were correct

## Summary

The results from the Logistic Regression Model have a high accuracy of 99%, it accurately classifies loan statuses. For precision '1' high risk loans, the model predicts with 84% accuracy. For recall '1' high risk loans, the model has an effectiveness of identifying '1' by 94%. It minimized false negatives and kept a low false positive rate. Therefore, due to the Logistic Regression Model's high performance of effectiveness, it should be used by the peer-to-peer lending services company.
