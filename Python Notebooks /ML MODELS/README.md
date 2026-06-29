# Machine Learning Models

This folder contains the modeling notebooks for the cybersecurity threat detection capstone project.

The goal of this stage was to evaluate machine learning models for detecting known attacks and identifying unusual behavior.

## Modeling Approach

The project tested both supervised and unsupervised methods.

Supervised learning was used for attack classification.  
Unsupervised learning was used for anomaly detection and clustering.

## Models Tested

- Logistic Regression
- Support Vector Machine
- Random Forest
- Gradient Boosting
- K-Nearest Neighbors
- K-Means Clustering
- DBSCAN
- Hierarchical Clustering
- One-Class SVM

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix
- Silhouette score for clustering

## Main Findings

- Gradient Boosting performed strongly on the BETH dataset.
- SVM with RBF kernel performed strongly on the UNSW-NB15 dataset.
- Anomaly detection methods added value for identifying unusual behavior.
- Some models produced high accuracy but weak rare-class detection, showing why accuracy alone is not enough.
- Class imbalance had a major impact on model performance and interpretation.

## Project Limitation

These models were developed for academic analysis using public datasets.  
They are not production-ready without validation on current organization-specific cybersecurity data.
