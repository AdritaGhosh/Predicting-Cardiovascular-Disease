# Predicting Cardiovascular Disease
Cardiovascular disease (CVD) is a leading cause of death globally. This project leverages AI and machine learning to predict heart disease early, using patient data including medical history, lifestyle factors, and genetic information. Early diagnosis is crucial for effective prevention and management. Description of this project is given in my [medium article](https://medium.com/@adrita21/predicting-cardiovascular-disease-using-advanced-ai-techniques-7b48c3f66541).

## Project Proposal
* **Problem Statement:** Traditional CVD diagnosis methods can be time-consuming and costly.
* **Aim and Objective:** Accurately predict the presence and severity of heart disease using various medical attributes.
* **Dataset:** [Processed Cleveland dataset](https://archive.ics.uci.edu/dataset/45/heart+disease) from the UCI Machine Learning Repository, with 303 instances and 14 attributes.

## Data Pre-processing and Visualisation
The dataset underwent cleaning, transformation, and visualisation to handle missing values, correct data types, and address class imbalance. Methods included label encoding, MinMaxScaler, and RandomOverSampler.

## Basic Task Implementation
Implemented and evaluated several models:
* **Multiclass SVM**
* **Multilayer Perceptron (MLP)**
* **Deep CNN**
* **KMeans Clustering**

## Enhancing Task Accuracy
Enhanced model accuracy using advanced AI techniques:
* Hyperparameter Tuning and Scaling for SVM
* RandomizedSearchCV for MLP
* Batch Normalization and Data Reshaping for CNN
* PCA and Gaussian Mixture Models for Clustering

## Evaluation
Significant improvements were observed:
* **SVM:** Test accuracy improved to 91.67%
* **MLP:** Test accuracy improved to 76.67%
* **CNN:** Test accuracy improved to 80.00%
* **Clustering:** Improved ARI to 0.06

## Conclusion
Advanced AI techniques significantly enhance the accuracy of heart disease prediction. Ethical considerations must be addressed to ensure responsible implementation in healthcare.


