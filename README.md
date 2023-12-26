**Module 12 Report**

## Overview of the Analysis

In this analysis, the goal was to evaluate the performance of two machine learning models trained on oversampled data to predict loan outcomes. The purpose was to assess their accuracy, precision, and recall scores in the context of financial data.

- **Financial Information:** The data pertains to loan outcomes, specifically predicting the likelihood of high-risk loans. The target variable is binary, with 0 indicating a healthy loan and 1 indicating a high-risk loan.

- **Variables to Predict:** The primary focus was on predicting the binary outcome of loan health (0) or high risk (1).

- **Stages of the Machine Learning Process:**
  - Data exploration and preprocessing.
  - Splitting the data into training and testing sets.
  - Implementing machine learning models, including logistic regression.
  - Training models on oversampled data to address class imbalance.

## Results

### Machine Learning Model 1:

- **Accuracy:** 99%
- **Precision (Label 0 - Healthy Loan):** 100%
- **Precision (Label 1 - High-Risk Loan):** 85%
- **Recall (Label 0):** 99%
- **Recall (Label 1):** 91%

### Machine Learning Model 2:

- **Accuracy:** 99%
- **Precision (Label 0):** 99%
- **Precision (Label 1):** 99%
- **Recall (Label 0):** 99%
- **Recall (Label 1):** 99%

## Summary

Both machine learning models exhibit exceptional performance, achieving high accuracy and balanced precision and recall scores.

- **Model 1:** Shows strong precision for predicting healthy loans but slightly lower precision for high-risk loans. It balances this with high recall for healthy loans.

- **Model 2:** Demonstrates uniform high performance with balanced precision and recall for both healthy and high-risk loans.

### Recommendation:

Considering the overall strong performance and balanced predictions, Model 2 is recommended for use by the company. However, the final choice should align with specific business requirements and the relative importance of precision and recall based on the company's risk tolerance.

- **Performance Evaluation:**
  - Model 2 performs consistently well across all metrics.
  - The choice might depend on the business's emphasis—whether it is more critical to accurately predict healthy loans (Label 0) or identify high-risk loans (Label 1).

In summary, the recommendation is to proceed with Model 2, but a careful consideration of business priorities is advised.
