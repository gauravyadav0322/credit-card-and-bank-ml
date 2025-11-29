# credit-card-and-bank-ml

Author: Gaurav Yadav  
Email: gauravyadav.e0322@gmail.com  
LinkedIn: https://www.linkedin.com/in/gaurav-y-a2b7b8234  
Portfolio: https://gaurav-yadav-portfolio.lovable.app/  
GitHub: https://github.com/gauravyadav0322

## Project Overview

This repository contains two machine learning projects built during my Data Science training:

1. **Credit Card Machine Learning**  
   - Notebook: `Gaurav Yadav Credit Card Machine Learning.ipynb`  
   - Dataset: `credit_card.csv`  
   - Objective: Build and evaluate classification models to detect/predict credit card related outcomes (fraud/default/target as per dataset). Includes full pipeline: EDA, preprocessing, feature engineering, model training, evaluation, and interpretation.

2. **Bank Machine Learning / PGA29 WD**  
   - Notebook: `Gaurav Yadav PGA29 WD Machine Learning (Bank).ipynb`  
   - Dataset: `bank.csv`  
   - Objective: Customer analytics and predictive modeling for bank dataset. Covers data cleaning, EDA, feature engineering, model training and performance reporting.

These notebooks demonstrate practical end-to-end ML workflows, from raw CSV files to evaluated models and visualizations.

## Repository Structure

.
├── credit_card.csv
├── bank.csv
├── "Gaurav Yadav Credit Card Machine Learning.ipynb"
├── "Gaurav Yadav PGA29 WD Machine Learning (Bank).ipynb"
└── README.md



## Key Features

- Exploratory Data Analysis (EDA) with descriptive statistics and visualizations
- Data cleaning and preprocessing pipelines (missing values, encoding, scaling)
- Feature engineering and correlation analysis
- Model building: baseline models and tree-based / ensemble models (e.g., Logistic Regression, Random Forest, XGBoost as applicable)
- Model evaluation: accuracy, precision, recall, F1-score, ROC-AUC and confusion matrix
- Basic interpretability: feature importances, partial dependence (where applicable)
- Reproducible Jupyter notebooks that walk through the steps and findings

## Requirements

Tested with Python 3.8+. Install the required packages:

```bash
pip install -r requirements.txt
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
xgboost
imbalanced-learn
joblib
plotly
