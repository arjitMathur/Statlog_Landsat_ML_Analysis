# Statistical & Machine Learning Analysis of the Statlog (Landsat Satellite) Dataset

## Overview
A comprehensive machine learning project analyzing the UCI Statlog (Landsat Satellite) dataset using statistical analysis, supervised learning, and unsupervised clustering.

## Dataset
- UCI Statlog (Landsat Satellite)
- 6,435 samples
- 36 numerical features
- 6 land-cover classes

## Objectives
- Perform exploratory data analysis
- Analyze feature redundancy
- Compare k-NN and SVM classifiers
- Compare K-Means and DBSCAN clustering
- Evaluate classification and clustering performance

## Technologies
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- SciPy

## Models
### Classification
- k-Nearest Neighbors
- Support Vector Machine (RBF)

### Clustering
- K-Means
- DBSCAN

## Evaluation Metrics
Classification
- Accuracy
- Cohen's Kappa
- ROC-AUC

Clustering
- SSE
- Entropy
- Silhouette Score

## Results
- k-NN Accuracy: 90.35%
- SVM Accuracy: 90.35%
- SVM Macro ROC-AUC: 0.9876
- K-Means achieved lower SSE.
- DBSCAN produced purer clusters but labeled ~28% of points as noise.

## Repository Structure
├── data/
├── notebooks/
├── src/
├── figures/
├── report/
├── requirements.txt
└── README.md

## References
UCI Machine Learning Repository
