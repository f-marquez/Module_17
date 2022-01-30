# Module_17
Credit Risk Analysis

## Overview
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

This new assignment consists of three technical analysis deliverables and a written report. You will submit the following:

  - **Deliverable 1:** Use Resampling Models to Predict Credit Risk<br>
  - **Deliverable 2:** Use the SMOTEENN algorithm to Predict Credit Risk<br>
  - **Deliverable 3:** Use Ensemble Classifiers to Predict Credit Risk<br>
  - **Deliverable 4:** A Written Report on the Credit Risk Analysis (README.md)<br>

## Deliverable 1: Use Resampling Models to Predict Credit Risk<br>
For all three algorithms, the following have been completed:
   - An accuracy score for the model is calculated 
   - A confusion matrix has been generated 
   - An imbalanced classification report has been generated

## Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk<br>
The combinatorial SMOTEENN algorithm does the following:
  - An accuracy score for the model is calculated
  - A confusion matrix has been generated
  - An imbalanced classification report has been generated
## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk<br?
The BalancedRandomForestClassifier algorithm does the following:
  
  - **An accuracy score for the model is calculated**
    - A confusion matrix has been generated
    - An imbalanced classification report has been generated
    - The features are sorted in descending order by feature importance
  - **The EasyEnsembleClassifier algorithm does the following:**
    - An accuracy score of the model is calculated
    - A confusion matrix has been generated
    - An imbalanced classification report has been generated
## Deliverable 4: A Written Report

Our original dataset contained 115,675 loan applications in Q1 of 2019. By using the "loan status" we were able to determine whether the application was considered "LOW " or "HIGH" risk. 
 - Applications that were listed as  "current" on the "loan status" were classified as "Low Risk" 
 - Appplications that were listed as any other status were deemed "High Risk". 
 - Ultimately this reduced the dataset to 68,817 total applications that were classified as "Low Risk".

Ranking of models in descending order based on "High Risk" results:
  - **EasyEnsembleClassifer:** 
      - 93.2% accuracy, 9% precision, 92% recall, and 16% F1 Score
  - **BalancedRandomForestClassifer:** 
      - 78.9% accuracy, 3% precision, 70% recall and 6% F1 Score
  - **SMOTE:** 
      - 65.2% accuracy, 1% precision, 61% recall and 2% F1 Score
  - **SMOTEENN:** 
      - 64.5% accuracy, 1% precision, 72% recall and 2% F1 Score
  - **RandomOverSampler:** 
      - 64.0% accuracy, 1% precision, 66% recall and 2% F1 Score
  - **ClusterCentroids:** 
      - 54.5% accuracy, 1% precision, 69% recall and 1% F1 Score
