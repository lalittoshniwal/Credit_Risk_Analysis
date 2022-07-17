# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of the project was to analyze the credit card credit dataset from LendingClub, a peer-to-peer lending services company using six different machine learning models to predict credit risk. Since credit risk is an inherently unbalanced classification problem, I employed different techniques to train and evaluate models with unbalanced classes.

## Results: 
As follows are the balanced accuracy scores and the precision and recall scores of all six machine learning models. As expected all the models have a very high precision score, which was due to high precision in predicting a "low risk" outcome.

1. Random Over Sampler
- Precision: 0.99 - very high score but mostly from the low-risk outcome.
- Recall: 0.68 - decent score; able to fairly accurately predict high-risk outcomes.
- Balanced accuracy score: 0.64 - decent score, able to fairly accurately predict both low and high-risk outcomes
<img src="/Resources/RandomOverSampler.png" >

2. SMOTE
- Precision: 0.99 - very high score but mostly from the low-risk outcome.
- Recall: 0.63 - decent score; able to fairly accurately predict high-risk outcomes.
- Balanced accuracy score: 0.64 - decent score, able to fairly accurately predict both low and high-risk outcomes
<img src="/Resources/SMOTE.png" >

3. Cluster Centroids
- Precision: 0.99 - very high score but mostly from the low-risk outcome.
- Recall: 0.57 - not as high as other models;  not able to as accurately predict high-risk outcomes.
- Balanced accuracy score: 0.59 - low score compared to other models, not able to accurately predict both low and high-risk outcomes
<img src="/Resources/ClusterCentroids.png" >

4. SMOTEENN
- Precision: 0.99 - very high score but mostly from the low-risk outcome.
- Recall: 0.57 - not as high as other models;  not able to as accurately predict high-risk outcomes.
- Balanced accuracy score: 0.63 - decent score, able to fairly accurately predict both low and high-risk outcomes
<img src="/Resources/SMOTEENN.png" >

5. Balanced Random Forest Classifier
- Precision: 0.99 - very high score but mostly from the low-risk outcome.
- Recall: 0.91 - high score; able to accurately predict high-risk outcomes.
- Balanced accuracy score: 0.79 - high score, able to accurately predict both low and high-risk outcomes
<img src="/Resources/BalancedRandomForestClassifier.png" >

6. Easy Ensemble Classifier
- Precision: 0.99 - very high score but mostly from the low-risk outcome.
- Recall: 0.93 - high score; able to accurately predict high-risk outcomes.
- Balanced accuracy score: 0.94 - very high score, able to very accurately predict both low and high-risk outcomes
<img src="/Resources/EasyEnsembleClassifier.png" >


## Summary: 
All the machine learning models performed well. Since it was an unbalanced classification problem, as expected all the models had a high precision score. Ensemble classifiers had a higher recall and balanced accuracy scores as compared to over- and undersampling models.

 Based on my analysis, I recommend using the Easy Ensemble Classifier to predict the credit risk. It not only has the highest recall score for predicting high-risk outcomes of 0.91 but also a high balanced accuracy score of 0.94.