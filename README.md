# Credit Risk Analysis

Using Resampling Models and Classifiers to Predict Credit Risk

## Overview

The purpose of this analysis is to test how machine models are able to assess credit card risk. Included models are RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier.

## Results 

### Random Oversampling <br>
![randomover](https://github.com/albertomontilla17/Credit_Risk_Analysis/blob/main/images/randomover.png) <br>
Balanced Accuracy Score: 0.6514336592657054 <br>
high risk performance: 
- precision is very low (0.01)
- recall is good (0.64)

low risk performance:
- precision is perfect (1.00)
- recall is good (0.66)

### SMOTE <br>
![smote](https://github.com/albertomontilla17/Credit_Risk_Analysis/blob/main/images/SMOOTE.png) <br>
Balanced Accuracy Score: 0.6092175608655539 <br>
high risk performance: 
- precision is very low (0.01)
- recall is good (0.56)

low risk performance:
- precision is perfect (1.00)
- recall is good (0.66)

### Cluster Centroid Undersampling
![undersampling](https://github.com/albertomontilla17/Credit_Risk_Analysis/blob/main/images/undersampling.png) <br>
Balanced Accuracy Score: 0.6092175608655539 <br>
high risk performance: 
- precision is very low(0.01)
- recall is fairly good (0.56)

low risk performance:
- precision is perfect (1.00)
- recall is good (0.66)

### Smoteen <br>
![smoteenn](https://github.com/albertomontilla17/Credit_Risk_Analysis/blob/main/images/SMOOTEN.png) <br>
Balanced Accuracy Score: 0.6501575272651091
high risk performance: 
- precision is low (0.01)
- recall is great (0.72)

low risk performance:
- precision is perfect (1.00)
- recall is fair (0.58)

### Balanced Random Forest Classifier <br>
![randomforest](https://github.com/albertomontilla17/Credit_Risk_Analysis/blob/main/images/random_forest.png) <br>
Balanced Accuracy Score: 0.795829959187949 <br>
high risk performance: 
- precision is low (0.03)
- recall is good (0.71)

low risk performance:
- precision is perfect (1.00)
- recall is great (0.88)


### Easy Ensemble Classifier <br>
![easy ensemble](https://github.com/albertomontilla17/Credit_Risk_Analysis/blob/main/images/easy_ensemble.png) <br>
Balanced Accuracy Score: 0.9263912558266958 <br>
high risk performance: 
- precision is low (0.08)
- recall is great (0.91)

low risk performance:
- precision is perfect (1.00)
- recall is great (0.94)

## Summary 

The F1 score can be characterized as a single summary statistic of precision and sensitivity(recall). Given this, the F1 score is a great measurement to gauge model performance. Based on F1 scores the best forming model is the Easy Ensemble Classifier with an average F1 score of 0.97. While the worst performing is Cluster Centroid with an average F1 score of 0.61. 

Typically in these models, a good result is when there is a good balance of recall and precision. Hence, the ensemble classifiers are better than the first four models. The Easy Ensemble Adaboost Classifier model had the best balance of all the models because of its high accuracy score and good balance of precision and recall scores - this makes it the best model to use.
