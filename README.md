# Credit Score Prediction

A machine learning project that predicts customer **Credit Score** categories using financial and credit-related features.

The project compares **Random Forest** and **XGBoost** models and analyzes the most influential features contributing to credit score predictions.

## Project Overview

Credit scoring is an important process in financial services because it helps assess a customer's creditworthiness based on their financial behavior and credit history.

This project applies supervised machine learning to classify customers into different credit score categories and evaluates the performance of two tree-based ensemble models.

## Objectives

This project aims to:

* Build machine learning models for credit score classification.
* Compare Random Forest and XGBoost performance.
* Evaluate models using multiple classification metrics.
* Identify the most important features influencing predictions.
* Interpret the model results from a financial perspective.

## Models

Two machine learning algorithms were evaluated:

* **Random Forest**
* **XGBoost**

## Feature Importance

Feature importance analysis was performed using the selected XGBoost model.

The analysis indicates that several credit-related variables contribute strongly to the model's predictions, including:

* `Payment_of_Min_Amount`
* `Credit_Mix`
* `Outstanding_Debt`
* `Interest_Rate`
* `Num_Credit_Card`
* `Delay_from_due_date`
* `Num_Bank_Accounts`

These variables represent different aspects of a customer's payment behavior, credit structure, and financial obligations.

## Key Insight

The feature importance analysis suggests that **payment behavior and credit characteristics** play an important role in distinguishing credit score categories within the dataset.

However, feature importance represents the contribution of variables to model predictions and should not automatically be interpreted as a causal relationship.
