# Credit Risk Analysis
## Overview
A p2p lending service company wants to use machine learning to predict credit risk. They need help building and evalutating several machine learning models, oversampling and undersampling the data, and evaluating the performance of the models to see they predict data. Management believes that this will provide a quicker and more reliable loan experience, and lead to a more accurate identification of good candidates for loans.
## Results
Six machine learning models were made and their results include balanced accuracy, precision, and recall scores.

## Naive Random Oversampling
![1](https://github.com/Jandreezy/Credit_Risk_Analysis/blob/main/Images/Results_Oversampling.png?raw=true)
- Balanced Accuracy: 0.6481
- Precision: Low for High-risk loans and high for Low-risk loans
- Recall: High/Low risk = .69/.60
## SMOTE Oversampling
![2](https://github.com/Jandreezy/Credit_Risk_Analysis/blob/main/Images/Results_SMOTE.png?raw=true)
- Balanced Accuracy: 0.6226
- Precision: Low for High-risk loans and is high for Low-risk loans
- Recall: High/Low risk = .63/.69
## Undersampling
![3](https://github.com/Jandreezy/Credit_Risk_Analysis/blob/main/Images/Results_Undersampling.png?raw=true)
- Balanced Accuracy: 0.5442
- Precision: Low for High-risk loans and is high for Low-risk loans
- Recall: High/Low risk = .69/.40
## Combination (Over and Under) Sampling
![4](https://github.com/Jandreezy/Credit_Risk_Analysis/blob/main/Images/Results_Combination_Sampling.png?raw=true)
- Balanced Accuracy: 0.6639
- Precision: Low for High-risk loans and is high for Low-risk loans
- Recall: High/Low risk =  .75/.58
## Random Forest
![5](https://github.com/Jandreezy/Credit_Risk_Analysis/blob/main/Images/Results_Random_Forest.png?raw=true)
- Balanced Accuracy: 0.7888
- Precision: Low for High-risk loans and is high for Low-risk loans
- Recall: High/Low risk = .70/.87
## Easy Ensemble
![6](https://github.com/Jandreezy/Credit_Risk_Analysis/blob/main/Images/Results_EasyEnsemble.png?raw=true)
- Balanced Accuracy: 0.9316
- Precision: Low for High-risk loans and is high for Low-risk loans
- Recall: High/Low risk = .92/.94
## Summary
Since the target goal is 1, the Easy Ensemble is the strongest model with 93% accuracy. The rest of the data models were more than 15% less accurate in comparison. The precision was about the same for each model but based on the data, the Easy Ensemble is the best machine learning model out of the group to conduct the credit card analysis.

