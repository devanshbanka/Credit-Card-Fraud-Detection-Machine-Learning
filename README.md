# Credit Card Fraud Detection System
This project aims to develop a machine learning-based Credit Card Fraud Detection system capable of accurately classifying transactions as fraudulent or legitimate. Fraudulent transactions pose significant risks to financial institutions and consumers alike, making it imperative to develop robust detection systems. Leveraging machine learning models, the system analyzes transaction data to identify fraudulent patterns and mitigate potential risks.

## Problem Statement:
Detecting fraudulent credit card transactions is a challenging task due to the highly imbalanced nature of transaction data. In real-world scenarios, fraudulent transactions are a minority class, comprising less than 0.1% of all transactions. This imbalance poses a significant challenge as models trained on imbalanced datasets tend to bias towards the majority class, resulting in poor detection of fraudulent transactions. Moreover, traditional accuracy metrics can be misleading, as a model predicting all transactions as legitimate could achieve high accuracy despite failing to detect fraudulent transactions. Hence, the primary challenge lies in developing a detection system that effectively identifies fraudulent transactions while minimizing false positives.

## Techniques Used:
Machine Learning Techniques:
* Random Forest
* Decision Trees
  
Deep Learning Techniques:
* Neural Network using 5 fully connected layers

## Results:
The project compares the performance of different machine learning and deep learning techniques for credit card fraud detection. The best results are achieved by employing the Synthetic Minority Oversampling Technique (SMOTE) to address the class imbalance issue. With SMOTE, the model successfully detects 100% of all fraudulent transactions in the unseen test set while maintaining an acceptable number of false positives. This approach significantly enhances the system's ability to detect abnormal transactions and reduces the workload for fraud detection departments by minimizing false positives.
