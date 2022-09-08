# Cryptocurrencies

## Overview 

The objective is to use unsupervised machine learning to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for a new investment. 

The assignment consists of four technical analysis deliverableslisted as follows:

* Deliverable 1: Preprocessing the Data for PCA
* Deliverable 2: Reducing Data Dimensions Using PCA
* Deliverable 3: Clustering Cryptocurrencies Using K-means
* Deliverable 4: Visualizing Cryptocurrencies Results

## Results
The results of the 6 machine learning models are described as follows:

### Naive Random Ovesampling

![](Resources/Naive_Random_Oversampling.png)

* Balanced Accuracy Score: 62.4%
* Precision: for high risk loans, the precision is low at 1% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 57% and for low risk loans at 67%  

### SMOTE Oversampling

![](Resources/SMOTE_Oversampling.png)

* Balanced Accuracy Score: 65%
* Precision: for high risk loans, the precision is low at 1% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 64% and for low risk loans at 65%

### Undersampling

![](Resources/Undersampling.png)

* Balanced Accuracy Score: 65%
* Precision: for high risk loans, the precision is low at 1% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 61% and for low risk loans at 45%


### Combination (Over and Under) Sampling

![](Resources/Combination_(Over_and_Under)_sampling.png)

* Balanced Accuracy Score: 64%
* Precision: for high risk loans, the precision is low at 1% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 70% and for low risk loans at 57%


### Balanced Random Forest Classifier

![](Resources/BalancedRandomForestClass.png)

* Balanced Accuracy Score: 79%
* Precision: for high risk loans, the precision is low at 4% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 67% and for low risk loans at 91%


### Easy Ensemble AdaBoost Classifier

![](Resources/EasyEnsembleClass.png)

* Balanced Accuracy Score: 93%
* Precision: for high risk loans, the precision is low at 7% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 91% and for low risk loans at 94%

## Summary
Looking at the results of the six models, the EasyEnsembleClassifer model resulted with an accuracy of 93% and a precision of 7% for High Risk loans, the recall was also high with this model compared to the others with a rate of 91%. For the Low Risk loans, the recall was also high with a rate of 94%. Given the better results of this model compare to the others, it is recommended to use this model for making predictions of credit risk
