PCOS Prediction and Subtype Analysis using Machine Learning
Overview

This project applies supervised and unsupervised machine learning techniques to analyze Polycystic Ovary Syndrome (PCOS) data.

The objective is to:

Predict PCOS occurrence using classification models.
Discover hidden patient subtypes using clustering techniques.
Evaluate model performance using multiple statistical metrics.
Dataset

PCOS Dataset

The dataset contains clinical, hormonal, and physiological measurements relevant to PCOS diagnosis.

Data Preprocessing
Missing value imputation
Numeric feature conversion
Standardization using StandardScaler
PCA-based dimensionality reduction

Supervised Learning Models
Logistic Regression
Random Forest
Decision Tree
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Hyperparameter Optimization

Random Forest optimization performed using GridSearchCV.

Parameters tuned:

Number of trees
Tree depth
Minimum samples split
Minimum samples leaf
Unsupervised Learning Models
Gaussian Mixture Model (GMM)
Spectral Clustering
Hierarchical Clustering
Evaluation Metrics
Classification
Accuracy
F1 Score

Classification Report
Confusion Matrix
Clustering
Silhouette Score
Davies-Bouldin Index
Clinical Coherence Score

Technologies Used
Python
Pandas
NumPy
Scikit-Learn
Matplotlib
Seaborn

Key Outcomes
Developed multiple machine learning models for PCOS prediction.
Performed clustering-based subtype identification.
Compared supervised and unsupervised learning approaches.
Applied optimization techniques to improve model performance.
