Epileptic Seizure Classification using EEG Data
===============================================

This repository contains the code for an epileptic seizure classification project using machine learning. The project employs Support Vector Machines (SVM) and Principal Component Analysis (PCA) to analyze Electroencephalogram (EEG) data and classify whether a subject is experiencing an epileptic seizure.

Key Components:
---------------
1. Data preprocessing: Standardizing the features.
2. SVM classifiers: Training and evaluating SVM models with linear, polynomial, and RBF kernels.
3. Performance evaluation: Using sensitivity and specificity metrics.
4. k-fold stratified cross-validation: Improving model generalization.
5. PCA: Dimensionality reduction for better model performance.

Requirements:
-------------
- Python 3.7+
- numpy
- pandas
- scikit-learn
- matplotlib

Usage:
------
1. Ensure you have the required Python libraries installed.
2. Run the script with the dataset (in .csv format) in the same directory.
3. Evaluate the performance of the models and compare the results to choose the best model for the classification task.

Note:
-----
The dataset used in this project is not included in this repository. Please acquire the dataset separately and ensure it is formatted according to the project requirements.
