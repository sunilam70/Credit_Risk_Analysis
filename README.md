# Credit Risk Analysis
Using Supervised Machine Learning and Jupiter Notebook to conduct credit risk analysis

Overview of Project

-Purpose

For analysing Credit risk, we built up our skills in data preparation,statistical reasoning, and machine learning.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.
Therefore, we would need to employ different techniques to train and evaluate models with unbalanced classes. Jill (our client)  asks
us to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will oversample
 the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids
 algorithm. Then, we will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
 Next, we will  compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier,
 to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written
 recommendation on whether they should be used to predict credit risk.


Results

Please refer to the 6 images for more details.

1) Naive random oversampling 
![](Resources/naive.png)

2) SMOTE Oversampling
![](Resources/smoteover.png)


3) SMOTE undersampling
![](Resources/smoteunder.png)


4) Combination (over and under sampling)
![](Resources/smoteenn.png)

5) Balanced Random Forest Classifier
![](Resources/RForest.png)

6) Easy Emsemble Adaboost Classifier
![](Resources/easy.png)

- Summary

Class imbalance refers to a situation in which the existing classes in a dataset aren't equally represented. 
Oversampling or undersampling or a combination of the two will help mitigate the risk of this happening.





