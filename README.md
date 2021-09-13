# Credit Risk Analysis

Using Resampling Models and Classifiers to Predict Credit Risk

## Overview

The purpose of this analysis is to test how machine models are able to assess credit card risk. Included models are RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier.

## Results 

### Random Oversampling <br>
![randomover]() <br>
Balanced Accuracy Score: 0.6400925019439107 <br>
high risk performance: 
- precision is very low (0.0.1)
- recall is good (0.61)

low risk performance:
- precision is perfect (1.00)
- recall is good (0.67)

### SMOTE <br>
![smote]() <br>
Balanced Accuracy Score: 0.6195656115160086 <br>
high risk performance: 
- precision is very low (0.0.1)
- recall is good (0.60)

low risk performance:
- precision is perfect (1.00)
- recall is good (0.64)

### Cluster Centroid 
![undersampling]() <br>
Balanced Accuracy Score: 0.6195656115160086 <br>
high risk performance: 
- precision is very low(0.01)
- recall is fairly good (0.61)

low risk performance:
- precision is perfect (1.00)
- recall is low (0.42)

### Smoteen <br>
![smoteenn]() <br>
Balanced Accuracy Score: 0.6400726134353378
high risk performance: 
- precision is low (0.01)
- recall is great (0.70)

low risk performance:
- precision is perfect (1.00)
- recall is fair (0.57?

### Balanced Random Forest Classifier <br>
![randomforest]() <br>
Balanced Accuracy Score: 0.7877672625306695 <br>
high risk performance: 
- precision is low (0.04)
- recall is good (0.67)

low risk performance:
- precision is perfect (1.00)
- recall is great (0.91)


### Easy Ensemble Classifier <br>
![easy ensemble]() <br>
Balanced Accuracy Score: 0.925427358175101 <br>
high risk performance: 
- precision is low (0.09)
- recall is great (0.92)

low risk performance:
- precision is perfect (1.00)
- recall is great (0.94)
