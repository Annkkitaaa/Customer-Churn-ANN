# Customer-Churn-ANN

## Overview
This repository contains code and documentation for predicting customer churn. Customer churn refers to the phenomenon where customers cease doing business with a company. Predicting churn can be crucial for businesses as it allows them to take proactive measures to retain customers. This README file provides an overview of the project, including key concepts and techniques utilized.

### Key Concepts
#### Customer Churn
Customer churn is a metric that measures the number of customers who leave a service over a given period of time. It is essential for businesses to understand and predict churn to devise strategies for customer retention.

#### Confusion Matrix
A confusion matrix is a performance measurement tool for machine learning classification algorithms. It's a table with four different combinations of predicted and actual values:

* True Positive (TP): Predicted positive correctly.
* True Negative (TN): Predicted negative correctly.
* False Positive (FP): Predicted positive incorrectly.
* False Negative (FN): Predicted negative incorrectly.
  
#### Recall
Recall (also known as Sensitivity or True Positive Rate) is the ratio of correctly predicted positive observations to the all observations in actual class. It measures the ability of the model to capture positive instances.

#### Precision
Precision is the ratio of correctly predicted positive observations to the total predicted positive observations. It measures the relevancy of the model's positive predictions.

#### Accuracy
Accuracy is the ratio of correctly predicted observations to the total observations. It measures the overall correctness of the model.

### Project Workflow
#### Data Cleaning:

Preprocess the dataset to handle missing values, outliers, and inconsistencies. This step ensures the data is suitable for modeling.
#### Data Visualization:

Explore the dataset through various visualizations to gain insights into the underlying patterns and relationships. Visualizations help in understanding the data better and informing feature selection.
#### Artificial Neural Network (ANN):

Build an Artificial Neural Network model for predicting customer churn. ANNs are a class of machine learning algorithms inspired by the biological neural networks of human brains.
#### Confusion Matrix:

Generate a confusion matrix to evaluate the performance of the churn prediction model. Analyze TP, TN, FP, FN values to calculate metrics like precision, recall, and accuracy.
#### Predictions:

Utilize the trained ANN model to make predictions on new or unseen data. Evaluate the model's performance based on various metrics and iterate on the model if necessary.
