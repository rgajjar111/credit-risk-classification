# credit-risk-classification
## Overview of Analysis Purpose:
### Objective: 
Evaluate the performance of a logistic regression model in predicting loan health (0) and high-risk loans (1) using both original and resampled data.
### Approach: 
Utilize a Random OverSampler to address class imbalance and compare model performance metrics.
### Model Evaluation Scores:
Original Data:
Accuracy: 99%
Precision (1): 84%
Recall (1): 94%
Resampled Data:
Accuracy: 99%
Precision (1): 84%
Recall (1): 99%
Summary of Results:
Accuracy: Both datasets achieve high accuracy, indicating effective overall prediction.
Precision (1 - High-risk loan): Consistent at 84% for both datasets.
Recall (1 - High-risk loan): Improved from 94% to 99% with resampling, indicating better identification of high-risk loans.
### Recommendation and Justification:
#### Recommendation: 
Recommend using the logistic regression model trained on resampled data.
#### Justification:
The model shows excellent performance in identifying high-risk loans after resampling.
The balanced accuracy score and recall for the minority class have significantly improved.
The model is well-suited for the company's objective of identifying high-risk loans, contributing to more informed lending decisions.
The resampling technique effectively addresses class imbalance, enhancing the model's robustness.
