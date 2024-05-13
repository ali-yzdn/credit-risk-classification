# Loan Default Prediction Model

This project aims to build a machine learning model to predict the risk of default for loans based on financial information. The model utilizes logistic regression to classify loans as either healthy or high-risk.

## Overview

The analysis involves the following stages:

- **Data Preparation**: Reading the dataset containing financial information about loans.
- **Data Exploration**: Understanding the structure and content of the dataset, including variable types and distributions.
- **Data Preprocessing**: Preparing the data for modeling, including splitting it into features and labels, and splitting into training and testing sets.
- **Model Building**: Utilizing logistic regression to build the predictive model.
- **Model Evaluation**: Assessing the model's performance using metrics such as accuracy, precision, and recall.

## Dataset

The dataset contains information on various financial attributes of loans, such as loan amount, interest rate, and credit score. The target variable is 'loan_status', with two classes: '0' (healthy loan) and '1' (high-risk loan).

## Model Performance

The logistic regression model achieved the following performance metrics:

- **Accuracy**: 99%
- **Precision for class '0'**: 1.00
- **Precision for class '1'**: 0.86
- **Recall for class '0'**: 1.00
- **Recall for class '1'**: 0.91
