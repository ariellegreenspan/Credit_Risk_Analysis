# Credit_Risk_Analysis

## Overview of the analysis: 
  The purpose of this analysis is to determine credit risk of the loan data utilizing different sampling and machine-learning models, including Random Oversampling, SMOTE Oversampling, Cluster Centroids, SMOTEEN, Balanced Forest Random Classifier, and Easy Ensemble AdaBoost Classifier.  

## Results: 

1) Naive Random Oversampling:

![Naive Random Oversampling](Resources/Naive_Random_Oversampling.png)
  
  * balanced accuracy score = 0.65
  * precision score: 1% for high-risk loans, 100% for low-risk loans
  * recall score: 63% for high-risk loans, 67% for low-risk loans

2) SMOTE Oversampling:

![SMOTE Oversampling](Resources/SMOTE_Oversampling.png)

  * balanced accuracy score = 0.65
  * precision score: 1% for high-risk loans, 100% for low-risk loans
  * recall score: 63% for high-risk loans, 67% for low-risk loans
 
3) Cluster Centroids

![Cluster Centroids](Resources/Cluster_Centroids.png)

  * balanced accuracy score = 0.53
  * precision score: 1% for high-risk loans, 100% for low-risk loans
  * recall score: 61% for high-risk loans, 45% for low-risk loans

4) SMOTEEN:

![SMOTEEN](Resources/SMOTEEN.png)

  * balanced accuracy score = 0.64
  * precision score: 1% for high-risk loans, 100% for low-risk loans
  * recall score: 70% for high-risk loans, 57% for low-risk loans

5) Balanced Random Forest Classifier

![Balanced Random Forest Classifier](Resources/Balanced_Random_Forest_Classifier.png)

  * balanced accuracy score = 0.79
  * precision score: 4% for high-risk loans, 100% for low-risk loans
  * recall score: 67% for high-risk loans, 91% for low-risk loans 

6) Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](Resources/Easy_Ensemble_AdaBoost_Classifier.png)

  * balanced accuracy score = 0.93
  * precision score: 7% for high-risk loans, 100% for low-risk loans
  * recall score: 91% for high-risk loans, 94% for low-risk loans 

## Summary:
  All of the data models utilized exhibited low precision when determining if credit risk would be high. All the data models exhibited high precision when determining if credit risk would be low. The model with the greatest precision score was the Easy Ensemble AdaBoost Classifier Model. The model with the highest balanced accuracy score was the Easy Ensemble AdaBoost Classifier Model. The model which exhibited the highest recall score for high-risk loans was also the Easy Ensemble AdaBoost Classifier Model. Based on the results, where the Easy Ensemble AdaBoost Classifier Model scored the highest in all categories used to determine accuracy, precision, and sensitivity, I would utilize the Easy Ensemble AdaBoost Classifier Model in future analyses. 
