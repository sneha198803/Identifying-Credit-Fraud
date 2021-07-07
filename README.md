# Identifying-Credit-Fraud

This project deals with European Credit transactions and identifies fraud transactions in the data that has a very high class imbalance.

Summary of the project

It is important that credit card companies can recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. Even though the percent of a fraudulent transaction is very low in proportion to the total transactions, fraud transactions can hamper the consumer sentiment. This will be a damaging thing to the company, as the customer might not use the card later, and for the country, because a huge negative sentiment will put the consumption-based economies at risk. So, we decided to use our skills to build a model that can accurately classify fraud transactions. We found this problem particularly interesting because the problem at hand has a huge class imbalance. It is a challenge to address this issue and simultaneously build models that have good recall and accuracy. So, we want to use all the techniques available to address the class imbalance and build the best model that has the highest predictive capability. We are addressing a real-world problem with real-world data. All transaction monitoring companies such as credit card companies, banks, insurance companies, etc. can make use of this project.

Objectives

Understand the European credit fraud data
Look at the summary statistics and identify the class imbalance
Clean, transform the data so that they are ready for modeling
Deal with class imbalance using techniques like undersampling, oversampling, SMOTE, etc.
Build several machine learning models like decision trees, logistic regression, support vector machines, and neural networks
Cross-validate the results and assess the performance of each model on test data
Select the champion model
Highlights

Data Transformation
Data Reduction (Performed PCA)
Sub-sampling (SMOTE-TOMEK oversampling)
Holdout Method and Cross-Validation
Clustering
Data Standardization
Used L1, L2 and Elastic Net regularization
Dealt with severe Class imbalance
Models built

Logistic Regression (with several solvers)
Decision Trees and variants (Gradient Boosting and Random Forests)
SVM
KNN
Data The dataset has been collected and analyzed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. They have uploaded the anonymized data on Kaggle for public use and I downloaded it from Kaggle (https://www.kaggle.com/mlg-ulb/creditcardfraud).
