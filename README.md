# Credit Risk Analysis

## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling including:

1. Imbalanced-learn
2. Scikit-learn
3. RandomOverSampler
4. SMOTE algorithms
5. ClusterCentroids algorithm
6. SMOTEENN algorithm
7. BalancedRandomForestClassifier (bias reduction model)
8. EasyEnsembleClassifier (bias reduction model)

## Results

### Naive Random Oversampling

![Alt text](https://github.com/dntalx/Credit_Risk_Analysis/blob/main/Resources/Oversampling.png)

* Accuracy = .64
* Precision = .99
* Recall = .62

### Random Forest Classifier

![Alt text](https://github.com/dntalx/Credit_Risk_Analysis/blob/main/Resources/Random_Forest_Classifier.png)

* Accuracy = .78
* Precision = .99
* Recall = .91

### Ensemble AdaBoost Classifier

![Alt text](https://github.com/dntalx/Credit_Risk_Analysis/blob/main/Resources/Easy_Ensamble_Classifier.png)

* Accuracy = .93
* Precision = .99
* Recall = .94

### SMOTE Oversampling

![Alt text](https://github.com/dntalx/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Oversampling.png)

* Accuracy = .63
* Precision = .99
* Recall = .64

### Cluster Centroids Undersampling

![Alt text](https://github.com/dntalx/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

* Accuracy = .51
* Precision = .99
* Recall = .45

### Combination Sampling

![Alt text](https://github.com/dntalx/Credit_Risk_Analysis/blob/main/Resources/Combination_Sampling.png)

* Accuracy = .64
* Precision = .99
* Recall = .58

## Summary
