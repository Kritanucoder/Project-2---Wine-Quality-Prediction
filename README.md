# Project-2---Wine-Quality-Prediction
This project applies a supervised regression framework to predict red wine quality based on physicochemical measurements. Leveraging the UCI Red Wine Quality dataset, the goal is to estimate quality scores—rated by human tasters—using machine learning models trained on features such as acidity, sulphates, and alcohol content.

The dataset undergoes preprocessing steps including duplicate removal and feature normalization using StandardScaler. Exploratory Data Analysis (EDA) is conducted through correlation heatmaps and distribution plots to identify influential predictors and class imbalance in quality ratings.

A range of regression models are developed and evaluated:

Linear Regression (baseline)

Random Forest Regressor

Multi-Layer Perceptron (MLP) Regressor

XGBoost Regressor

Models are trained using an 80-20 train-test split and evaluated with key performance metrics: R² Score and Root Mean Squared Error (RMSE). Among all models, the XGBoost Regressor consistently achieved the best predictive performance, outperforming both traditional and deep learning models in accuracy and generalization.

This notebook demonstrates an end-to-end machine learning pipeline—from preprocessing and visualization to model training and evaluation. It serves as a practical reference for tackling real-world regression tasks using structured numerical data and ensemble learning techniques.
