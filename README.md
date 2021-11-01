## Overview of the analysis

The purpose of this analysis is to apply machine learning to predict credit risk. For this analysis I have used credit card credit dataset from LendingClub. I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling with the SMOTEENN algorithm. Next, I compared two new machine learning models that reduced bias, BalancedRandomForestClassifier and EasyEnsembleClassifier in order to predict credit risk. Finally, I evaluated the performance of these models and made a recommendation on whether they should be used to predict credit risk.

## Results: 

1. Oversampling using RandomOverSampler

<img src="https://i.ibb.co/JjkSt94/1-Oversampling.png" alt="1-Oversampling" border="0">

2. SMOTE Oversampling

<img src="https://i.ibb.co/Ltdz4SF/2-SMOTE-Oversampling.png" alt="2-SMOTE-Oversampling" border="0">


3. Undersampling using ClusterCentroids resampler

<img src="https://i.ibb.co/41LkqHD/3-Undersampling.png" alt="3-Undersampling" border="0">

4. Combination (Over and Under) Sampling

<img src="https://i.ibb.co/z61yfvm/4-Combination-over-and-under-sampling.png" alt="4-Combination-over-and-under-sampling" border="0">

5. Balanced Random Forest Classifier

<img src="https://i.ibb.co/JCW9myP/5-Balanced-random-forest-classifier.png" alt="5-Balanced-random-forest-classifier" border="0">

6. Easy Ensemble AdaBoost Classifier

<img src="https://i.ibb.co/CB4Ypc4/6-Easy-ensemble-adaboost-classifier.png" alt="6-Easy-ensemble-adaboost-classifier" border="0">

## Summary: 
