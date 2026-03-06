# UQDSCRP - The Principles of Machine Learning

Course materials and notebooks for **The Principles of Machine Learning** workshop.

## Project Overview

This repository contains hands-on notebooks that walk through a binary classification workflow using the **Breast Cancer Wisconsin Diagnostic** dataset (UCI dataset id `17`).

Topics covered include:

- Data loading from UCI
- Exploratory data analysis and visualization
- Label encoding
- Feature scaling
- Train/test split
- K-Nearest Neighbors (KNN)
- Cross-validation (K-Fold and Stratified K-Fold)
- Hyperparameter tuning with GridSearchCV
- Logistic Regression baseline model

## Repository Structure

- `Code_The_Principles_of_Machine_Learning.ipynb`  
  Main notebook with preprocessing, KNN, CV, grid search, and logistic regression.
- `wdbc_visualization.ipynb`  
  Additional visual analysis notebook.
- `README.md`  
  Project documentation.

## Requirements

Create a `requirements.txt` file in the project root with:

```txt
pandas
numpy
matplotlib
scikit-learn
ucimlrepo
