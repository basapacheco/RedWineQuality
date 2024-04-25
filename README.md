# RedWineQuality

## Overview

This repository contains two Jupyter notebooks that explore and model the quality of red wines based on physicochemical properties from the Portuguese "Vinho Verde" wine dataset. The project is aimed at practitioners interested in regression, classification, and feature engineering within the context of wine quality evaluation.

## Projects

### 1. RedWineQuality.ipynb

**Description**: This notebook focuses on basic exploratory data analysis and classification using several machine learning algorithms including RandomForest, SVC, and SGD classifiers. The goal is to predict the quality of wine as 'good' or 'bad' based on physicochemical tests.

**Techniques Used**:
- Data visualization with seaborn
- Classification with RandomForest, SVC, and SGD classifiers
- Model evaluation and parameter tuning using GridSearchCV

### 2. Advanced_Wine_Quality_Prediction_Regression_Feature_Engineering_and_PCA_Analysis.ipynb

**Description**: This advanced analysis notebook extends the initial exploration to include feature engineering, PCA for dimensionality reduction, and uses Gradient Boosting for regression. It also employs hyperparameter optimization with Optuna to improve model performance.

**Techniques Used**:
- Feature engineering
- PCA for dimension reduction
- Regression with Gradient Boosting Regressor
- Hyperparameter optimization with Optuna

## Dataset

The dataset used in these analyses contains attributes related to the red variants of the Portuguese "Vinho Verde" wine. It includes physicochemical properties such as acidity, sugar, pH levels, and alcohol content, which are used to predict sensory-based quality scores from 0 to 10.

**Source**: The dataset is available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality) but is also included in this repository for convenience.

## Citation

Please cite the following work if you use this dataset:
- P. Cortez, A. Cerdeira, F. Almeida, T. Matos, and J. Reis, "Modeling wine preferences by data mining from physicochemical properties," Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## Installation

Required libraries for this analysis include pandas, numpy, seaborn, matplotlib, scikit-learn, and optuna. These can be installed via pip if they are not already available in the Python environment.

## About the Author

This project was developed by Pablo Basa Pacheco. For more information or to connect, please visit my [LinkedIn profile](https://www.linkedin.com/in/pablobasadata).
