# Module 12 Report Template

## Overview of the Analysis

### In this section, describe the analysis you completed for the machine learning models used in this Challenge.

The analysis I completed in this challenge was to identify high-risk loans (class 1) versus healthy loans (class 0).

The dataset used in this analysis contained financial information related to loans, including attributes like loan size, interest rate, borrower income, debt to income, number of account, derogatory marks, total debt, and loan status. The goal was to predict the loan status as healthy or high-risk using machine learning models that are based on the financial attributes listed earlier. The variable to predict was the loan status. 0 is a healthy loan, 1 is a high risk loan.

Throughout this analysis, I completed data preprocessing, in-depth exploration of the dataset, constructed predictive models, and model evaluations. An important part was addressing class imbalance to improve the model's overall performance.

I used a logistic regression model as the initial baseline model. To gain more insights into the effects of class imbalance, I proceeded to train an alternative model on resampled data. By conducting this comparative analysis, I determined how class imbalance mitigation techniques impacted the model's effectiveness in classifying loans.

## Results

### Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

- Machine Learning Model 1:

    - Balanced Accuracy Score for Model 1: 0.952
    - Precision for Class 0 (Healthy Loans): 1.00
    - Recall for Class 0 (Healthy Loans): 1.00
    - F1-score for Class 0 (Healthy Loans): 1.00
    - Precision for Class 1 (High-Risk Loans): 0.86
    - Recall for Class 1 (High-Risk Loans): 0.91
    - F1-score for Class 1 (High-Risk Loans): 0.88

- Machine Learning Model 2:
    - Balanced Accuracy Score for Model 1: 0.994
    - Precision for Class 0 (Healthy Loans): 1.00
    - Recall for Class 0 (Healthy Loans): .99
    - F1-score for Class 0 (Healthy Loans): 1.00
    - Precision for Class 1 (High-Risk Loans): 0.85
    - Recall for Class 1 (High-Risk Loans): 0.99
    - F1-score for Class 1 (High-Risk Loans): 0.92


## Summary

### Summarize the results of the machine learning models, and include a recommendation on the model to use, if any.

The first machine learning model does a good job because the balanced accuracy score is 0.952, this indicates the model usually is correct in classifying both healthy and high-risk loans. The precision for class 0 is 1.00, meaning when the model predicts a healthy loan it's correct 100% of the time. The recall is 1.00, indicating that the model captures 100% of the actual healthy loans. The precision for clas 1 is .86, meaning when the model predicts a loan as high-risk it's correct 86% of the time. The recall for class 1 is 0.91, indicating that the model captures 91% of the actual high-risk loans.

The second machine learning model is the one I would recommend to use. It does a better job of predicting both a heathly loan and a high risk loan. A couple reason why it does a better job is because the balanced accuracy score is 0.994, this indicates the model usually is correct in classifying both healthy and high-risk loans. The precision for class 0 is 1.00, meaning when the model predicts a healthy loan it's correct 100% of the time. The recall is .99, indicating that the model captures 99% of the actual healthy loans. The precision for clas 1 is .85, meaning when the model predicts a loan as high-risk it's correct 85% of the time. The recall for class 1 is 0.99, indicating that the model captures 99% of the actual high-risk loans. 

