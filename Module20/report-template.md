# Module 20 Report 

## Overview of the Analysis


In this credit risk analysis, machine learning techniques were employed to predict loan outcomes, distinguishing between healthy (0) and high-risk (1) loans. The evaluation involved comparing two models: one trained on the original data and another on additional data to address class imbalance. Remarkably, the model with extra data showcased enhanced performance, particularly in identifying high-risk loans. This emphasizes the effectiveness of incorporating more data, known as oversampling, for improved credit risk assessment in the financial sector.


## Results

The following results provide an overview of the performance metrics of two machine learning models, one trained on the original data and the other on resampled data, to predict loan outcomes.

Machine Learning Model 1 (Logistic Regression with Original Data):

Balanced Accuracy Score: 0.9521352751368186
Precision: 0 :1.00
           1 :0.86 
Recall:    0 :1.00 
           1 :0.91 
f1-score   0 :1.00
           1 :0.88
           
Machine Learning Model 2 (Logistic Regression with Resampled Data):

Balanced Accuracy Score: 0.9941749445500477
Precision: 0 :1.00
           1 :0.85
Recall:    0 :1.00
           1 :0.99
f1-score   0 :1.00
           1 :0.88           

## Summary

In this credit risk analysis, machine learning was used to predict healthy and high-risk loans. Two models were compared. One model trained on the original data and another on additional data to address imbalance. The model with extra data performed better, especially in spotting high-risk loans. This emphasizes the benefit of adding data, called oversampling, for improved credit risk assessment and better lending decisions in finance.