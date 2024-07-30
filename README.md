# Music Genre Classification and Recommendation System

This repository contains a project focused on classifying music genres and recommending similar songs using supervised learning techniques. The project is structured into two main parts: building and comparing supervised learning models, and developing a recommendation system.

## Repository Structure

- **Data/**: This folder contains the dataset used for the project, including audio files, `features_3_sec.csv`, and `features_30_sec.csv`.
- **Supervised Learning Models.ipynb**: A Jupyter notebook that includes the implementation and comparison of various supervised learning models for music genre classification.
- **Recommendation System.ipynb**: A Jupyter notebook that contains the implementation of the music genre classification and the recommendation system.
- **best_xgb_model.pkl**: The saved best XGBoost model from the classification task.
- **knn_model.pkl**: The saved KNN model used for the recommendation system.

# Project Overview
## Music Genre Classification
The classification task involves training several supervised learning models, including Random Forest, SVM, KNN, Decision Tree, and XGBoost, to classify music genres based on extracted features. The models are evaluated using metrics such as accuracy, confusion matrix, and ROC-AUC score.

## Recommendation System
The recommendation system uses a K-Nearest Neighbors (KNN) approach to recommend similar songs based on cosine similarity of their features. The system is designed to provide recommendations for a given song from the dataset.

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook

Library requirements:
```txt
pandas
numpy
scikit-learn
xgboost
joblib
seaborn
matplotlib
