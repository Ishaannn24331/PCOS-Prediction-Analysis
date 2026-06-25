# PCOS Prediction and Subtype Analysis using Machine Learning

## Overview

This project applies both supervised and unsupervised machine learning techniques to analyze Polycystic Ovary Syndrome (PCOS) data.

The primary objectives of this project are:

- Predict PCOS occurrence using classification models.
- Discover hidden patient subtypes using clustering techniques.
- Evaluate model performance using multiple statistical metrics.
- Compare the effectiveness of different machine learning approaches.

---

## Dataset

The project uses a PCOS dataset containing clinical, physiological, and diagnostic parameters related to Polycystic Ovary Syndrome.

The dataset was preprocessed before model development to ensure data quality and model reliability.

---

## Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Feature selection and cleaning
- Standardization using StandardScaler
- Dimensionality reduction using PCA
- Train-Test splitting for supervised learning

---

## Supervised Learning Models

The following classification models were implemented and evaluated:

### Logistic Regression
A baseline linear classification model used for PCOS prediction.

### Decision Tree
A tree-based model capable of capturing nonlinear decision boundaries.

### Random Forest
An ensemble learning technique that improves predictive performance by combining multiple decision trees.

### Support Vector Machine (SVM)
A powerful classifier used to separate PCOS and non-PCOS cases.

### K-Nearest Neighbors (KNN)
A distance-based classification algorithm used for comparative analysis.

---

## Hyperparameter Optimization

Random Forest performance was improved using GridSearchCV.

The following parameters were tuned:

- Number of estimators
- Maximum tree depth
- Minimum samples split
- Minimum samples leaf

---

## Unsupervised Learning Models

To identify hidden patterns and possible PCOS subtypes, the following clustering techniques were applied:

### Gaussian Mixture Model (GMM)

Used to identify probabilistic clusters and patient subgroup distributions.

### Spectral Clustering

Applied for discovering complex cluster structures in the dataset.

### Hierarchical Clustering

Used to visualize cluster relationships and patient grouping patterns.

---

## Evaluation Metrics

### Classification Metrics

- Accuracy Score
- F1 Score
- Precision
- Recall
- Confusion Matrix
- Classification Report

### Clustering Metrics

- Silhouette Score
- Davies-Bouldin Index
- Clinical Coherence Analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## Key Outcomes

- Developed multiple machine learning models for PCOS prediction.
- Performed clustering-based patient subtype discovery.
- Applied dimensionality reduction using PCA.
- Optimized model performance through hyperparameter tuning.
- Compared supervised and unsupervised learning approaches.
- Evaluated models using both classification and clustering metrics.

---

## Future Improvements

Potential future enhancements include:

- Deep Learning based PCOS prediction models
- Explainable AI (XAI) techniques for model interpretation
- Feature importance analysis using SHAP values
- Deployment as a web-based diagnostic support tool

---

## Author

**Ishaan Selvakumar**

B.Tech Artificial Intelligence & Data Science

Amrita Vishwa Vidyapeetham

Machine Learning | Deep Learning | Computer Vision
