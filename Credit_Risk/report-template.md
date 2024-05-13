# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The analysis aims to build a machine learning model to predict the risk of default for loans, using financial information as input.

* Explain what financial information the data was on, and what you needed to predict.

The data contains information on various financial attributes of loans, such as loan amount, interest rate, and credit score, ultimate goal is to predict whether a loan is healthy (0) or has a high risk of default (1) based on this information.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The variable to predict is 'loan_status', with two classes: '0' (healthy loan) and '1' (high-risk loan) and determining information can be obtained using the value_counts() function to show total loans with healthy or high risk status for further analysis of interrelated ratios.

* Describe the stages of the machine learning process you went through as part of this analysis.

Data Preprocessing: Reading the dataset, splitting it into features and labels, and splitting the data into training and testing sets.

Model Building: Instantiating a logistic regression model and fitting it to the training data.

Model Evaluation: Assessing the model's performance using metrics such as accuracy, precision, and recall.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithm).

Logistic Regression: used to build the  model due to its simplicity for classifying binary data.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

Logistic Regression:
Accuracy: 99%
Precision for class '0': 1.00
Precision for class '1': 0.86
Recall for class '0': 1.00
Recall for class '1': 0.91


## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?

The logistic regression model performs very well in predicting healthy loans ('0'), It also performs comparably well in predicting high-risk loans ('1'), with somewhat lower precision and recall compared to healthy loans. The model has an overall accuracy of 99%, indicating its effectiveness in grouping healthy and high-risk loans.



* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Yes it does depend on the type of peroblem. Predicting healthy loans ('0') is important to ensure businesses growth, but also identifying high-risk loans ('1') is important to mitigate default risks and loss for business.

If you do not recommend any of the models, please justify your reasoning.
