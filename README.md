# Logistic-regression
---
# Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis was to create a machine learning model that can predict the risk of loan default. A logistic regression model was trained using a dataset of various loan features, and it was tasked with predicting whether a loan would be healthy (0) or high-risk (1).

## Results

The model's performance was evaluated using a confusion matrix and a classification report. Here are the key findings:

- The model correctly predicted 18,699 healthy loans and 539 high-risk loans.
- The model incorrectly predicted 93 healthy loans as high-risk and 53 high-risk loans as healthy.
- The accuracy of the model, which is its ability to correctly predict both healthy and high-risk loans, was 99%.
- The model showed a precision of 1.00 for healthy loans and 0.85 for high-risk loans. Precision measures the model's accuracy in predicting positive instances.
- The recall of the model, which is its ability to find all positive instances, was 1.00 for healthy loans and 0.91 for high-risk loans.
- The F1-score of the model, which is the harmonic mean of precision and recall, was 1.00 for healthy loans and 0.88 for high-risk loans.

## Summary

The logistic regression model demonstrated excellent performance in predicting both healthy and high-risk loans, with an overall accuracy of 99%. The model showed perfect recall for healthy loans and very high recall for high-risk loans, indicating its effectiveness in identifying true positive instances. The model's precision was also high for both classes, suggesting a low rate of false positives.

Despite its slightly lower performance in predicting high-risk loans compared to healthy loans, the model still demonstrated satisfactory results. The benefits of being able to accurately identify high-risk loans – potentially saving the company from costly defaults – likely outweigh the costs of the few false positives and negatives.

Therefore, I would recommend the logistic regression model for use by the company in evaluating loan risks. However, it's important to continue monitoring and tuning the model to ensure it remains effective over time, particularly as new data becomes available.
