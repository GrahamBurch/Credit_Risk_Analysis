# Credit_Risk_Analysis

## Overview
* This analysis used machine learning algorithms in jupyter notebook to assess which method from among Naive Random Oversampling, SMOTE, Cluster Centroids, SMOTEENN, Balanced Random Forest Classifiers and Easy Ensemble Classifiers best predictors credit risk.

## Results
* Naive Random Oversampling:

    ![Naive Random Oversampling](Images/naive_oversampling_imbalanced_classification.JPG)


* SMOTE:

    ![SMOTE](Images/SMOTE_imbalanced_classification.JPG)


* Cluster Centroids Algorithm:

    ![Cluster Centroids Algorithm](Images/cluster_centroids_imbalanced_classification.JPG)


* SMOTEENN:

    ![SMOTEENN](Images/smote_een_imbalanced_classification.JPG)


* Balanced Random Forest Classifier:

    ![Balanced Random Forest Classifier](Images/balanced_random_forest_classification.JPG)


* Easy Ensemble AdaBoost Classifier:

    ![Easy Ensemble AdaBoost Classifier](Images/Adaboost_classification.JPG)

## Conclusions

* The Easy Ensemble AdaBoost Classifier performed the best at accurately categorizing high-risk applications with an accuracy score of 93%. The precision scores could be improved, meaning some loans which are not really high-risk are still being classified as such, but the Easy Ensemble algorithm nonetheless performs the best of the group tested here.