# Module-20

## Overview of the Analysis

*The objective of this analytical undertaking is to construct a robust model that can effectively discern the creditworthiness of prospective borrowers.

*The Dependant variable (y value) in this analysis was the "loan status" indicating if a loan is healthy or at risk. Independent Variables (x values) were loan size, interest rate, borrower income, debt to income ratio, number of accounts and derogatory marks.

*The analysis involved developing two distinct logistic regression models based on the original dataset and a randomly over-sampled dataset to address the issue of imbalances. Ultimately, the results obtained through the utilization of the scikit-learn library were compared.



## Results

* Machine Learning Model 1:
<img width="458" alt="Screenshot 2023-03-23 at 9 50 30 PM" src="https://user-images.githubusercontent.com/114380365/227411864-587a8833-bc75-4d35-a718-a1f51c781106.png">

## Summary

  The model predicts high-risk loans extremly well. Healthy loans also have a high prediction rate although not as high as high-risk loan predictions. The analysis demonstrates the effectiveness of the collected data in training and testing the machine learning classification model. However, to improve predictions, addressing the imbalance sampling issue is essential. Random oversampling of the data proved to enhance the balanced accuracy and recall scores. A higher recall value indicates a greater accuracy in predicting risky loans. False positives and false negatives are two concerns associated with incorrect predictions, where users are erroneously classified as risky or healthy. Both cases have consequences, making it crucial to accurately predict both outcomes. Thus, the model's accuracy must be assessed in terms of both.



