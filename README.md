## Diabetes Detection from ECG Signals Using Machine Learning

# Description
This project applies machine learning to detect diabetes from patient ECG signals. Algorithms tested include Random Forest Classifier, Logistic Regression, and Gaussian Naive Bayes. Feature extraction and preprocessing were applied to ensure high-quality data inputs.

# Dataset & Preprocessing

ECG signal data from patients

Preprocessing: normalization, downsampling, and noise filtering

Features extracted: mean, standard deviation, average time domain, and other signal features

# Modeling

Algorithms applied: Random Forest, Logistic Regression, Gaussian Naive Bayes

Evaluation via confusion matrix: true positives, true negatives, false positives, false negatives

Random Forest achieved 87.5% precision, successfully predicting diabetic patients

# Key Findings

Machine learning can detect diabetes effectively using ECG data

Random Forest performed best among tested algorithms

Preprocessing and feature extraction were critical for model performance

# Usage

Code can be run with any ECG dataset after feature extraction

Modify preprocessing and feature parameters for dataset-specific tuning
