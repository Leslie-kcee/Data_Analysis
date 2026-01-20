# Project Overview

This project builds a machine‑learning model to predict whether a borrower will default on a loan. It follows a realistic credit‑risk workflow: data cleaning, feature selection, model training, handling class imbalance, and evaluating performance.


1. What I Did
   
Cleaned and prepared the dataset

Selected financial features such as DTI, credit score, income, loan amount, and more

Trained a Random Forest model to predict default

Used SMOTE to balance the dataset and improve detection of default cases

Evaluated the model using precision, recall, and F1‑score


2. Key Insights
   
-All non default(0) cases are detected, with a precision level of 94%

-Only 4% of default cases are detected, with a precision level of 7%

-The dataset was highly imbalanced, which made default cases hard to detect. Balancing the data helped the model start identifying defaults

-The project demonstrates real‑world challenges in credit‑risk modeling


3. Tools Used
   
Python (pandas, scikit‑learn, imbalanced‑learn)


4. What I Learned
   
How to train and evaluate a classification model

How to handle imbalanced datasets using SMOTE

How to interpret model performance beyond accuracy


5. Machine Learning Output
   

precision    recall  f1-score   support

           0       0.89      1.00      0.94     67681
           1       0.56      0.04      0.07      8924

    accuracy                           0.88     76605
   macro avg       0.72      0.52      0.50     76605
weighted avg       0.85      0.88      0.84     76605
