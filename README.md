# credit-risk-classification

## Overview of the Analysis

- The purpose of this analysis is to test whether the Linear Regression Model is an appropiate model to identify the creditworthiness of burrowers.

- We will explore a dataset of historical lending activity from a peer-to-peer lending services company. This dataset consists of 77,536 records of the following fields:
    - `loan_size`
    - `interest_rate`
    - `burrower_income`
    - `debt_to_income`
    - `num_of_accounts`
    - `derogatory_marks`
    - `total_debt`
    - `loan_status`

## Results
 Describe the accuracy scores and the precision and recall scores of all machine learning models.

- Linear Regression Model:
    - Accuracy Score = 0.99
        - This high accuracy score indicates that the model performs well overall, as the model predicted 99% of the instances in the dataset correctly.
    - Precision 0 = 1.00
        - This high precision score indicates that the model has a low false positive rate. The model was extremely accurate in prediciting which loans would be considered healthy.
    - Recall 0 = 1.00
        - This high recall score indicates that the model has a low false negative rate.
    - Precision 1 = 0.87
        - While not a perfect precision score, we can still confirm that the model performs well as it 87% of the instances predicted as highrisk loans in the dataset were actually high risk loans.
    - Recall 1 = 0.89
        - This recall score indicated that the model correctly identified 89% of the instances of high risk loans.
    

## Summary
- We can conclude that the Logistic Regression Model performs extremely well overall. In regards to prediciting & indentifying healthy loans, the model is practically flawless. While the model is not perfect for prediciting and identifying high risk loans - the model still performed well in this area, and should still be taken into consideration. 
