# Bank Loan Approval Classification

## Overview

This project involves predicting bank loan approval outcomes using supervised machine learning classification models. Several traditional classifiers and a neural network were evaluated to identify the best-performing approach.

## Dataset

* Name: Bank Loan Approval Dataset
* Source: Kaggle
* Link: https://www.kaggle.com/datasets/vikramamin/bank-loan-approval-lr-dt-rf-andauc

The dataset contains structured financial and applicant-related features used for loan approval prediction.

## Approach

### Data Preparation

* Handled missing values
* Encoded categorical variables
* Standardized features
* Converted target labels to numerical values

### Model Training \& Evaluation

All classification models were trained using the same training–testing split.

Models implemented:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier
* Neural Network Classifier

### Evaluation Metric

* Primary metric: Accuracy

## Results

* Best Performing Model: XGBoost Classifier
* Accuracy: 0.9920

## How to Run

1. Clone the repository
2. Open the notebook for the loan approval classification project
3. Run all cells in order to:

   * Prepare and preprocess the data
   * Train classification models
   * Evaluate model performance

## Summary

XGBoost achieved near-perfect accuracy on the structured loan approval dataset. Ensemble methods consistently performed strongly, while Logistic Regression provided an interpretable baseline.

