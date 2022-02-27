# Overview

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asked us to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, we’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results


## Deliverable 1
### Naive Random Oversampling:
![This is an image](https://github.com/kellyd7/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling.png)

### SMOTE Oversampling:
![This is an image](https://github.com/kellyd7/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling.png)

### Undersampling:
![This is an image](https://github.com/kellyd7/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

## Deliverable 2
### Combination (Over and Under) Sampling:
![This is an image](https://github.com/kellyd7/Credit_Risk_Analysis/blob/main/Images/Combination%20(Over%20and%20Under)%20Sampling.png)

## Deliverable 3
### Balanced Random Forest Classifier:
![This is an image](https://github.com/kellyd7/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier.png)

### Easy Ensemble AdaBoost Classifier:
![This is an image](https://github.com/kellyd7/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost%20Classifier.png)

# Summary
Each model appeared to be sufficient in identifying low risk loans. However, I would recommend using the SMOTE model considering the results.
