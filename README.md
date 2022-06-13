# Challenge 12

## Overview of the Analysis

This is analysis was conducted to build a model that can identify the creditworthiness of borrowers using a dataset of historical lending activity from a lending services company for the prediction of imbalanced classes.

In this analysis i used tools like value_counts() and train_test_split() to provide a streamlined approach towards further data prediction and analysis.

The stages for the machine learning component were as follows:
1. Data Preparation - Slicing and preperaing it for integration
2. Logistic Regression - Standard "model-fit-predict" structure 
3. Resampled Data using OverSampling -  A model will often generate skewed or predictive data towards the class with more data, so random oversamping adds more banace.
4. Visual Comparison of the two models.


## Results

* Machine Learning Model 1:
Accuracy: 95%
Precision: 99%
Recall: 99%



* Machine Learning Model 2:
Accuracy: 99%
Precision: 99%
Recall: 99%

## Summary

Model 2 (Resampled Data) had higher accuracy and overall higher scores provided by the classification report.
The oversampled model predicts healthy loans with 100% accuracy while high-risk loan is predicted with 84% accuracy, which is 1% lower than the non-oversampled data.