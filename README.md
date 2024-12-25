## Machine-Learning-Based-Prediction-of-CO2-Storage-Site-Stability
# Overview
This project focuses on predicting the stability of CO2 storage sites using machine learning techniques. With the growing importance of carbon capture and storage (CCS) in reducing atmospheric CO2 levels, ensuring the stability of CO2 storage sites is critical for preventing risks such as CO2 leakage and site failure. The project employs two machine learning models—XGBoost and Logistic Regression—to predict the geomechanical stability of these storage sites, utilizing various geological and geophysical features.

# Project Description
This project aims to assess the stability of CO2 storage sites using predictive models. By analyzing geological, geophysical, and other relevant parameters, we can estimate the likelihood of CO2 leakage or storage site failure. Machine learning models are trained on data containing key features such as rock properties, pressure, temperature, and depth to predict the stability of potential CO2 storage sites.

# Dataset
The dataset used for training the models consists of various geological features of potential CO2 storage sites. These features include rock properties, fault lines, pressure, temperature, and other geophysical data relevant to the stability of storage sites.

# Features
Pressure: Pressure of CO2 at the storage site (in Pascals).
Temperature: Temperature of CO2 at the storage site (in degrees Celsius).
Rock_Permeability: Permeability of the rock formations (in Darcy).
Fault_Probability: Probability of fault occurrence at the storage site.
Depth: Depth of the storage formation (in meters).
Porosity: Porosity of the rock formations at the storage site.
Additional geological and geophysical parameters.

# Methodology
The methodology for this project includes the following steps:

Data Preprocessing: Handling missing values, normalizing the data, and feature engineering.
Feature Selection: Identifying the most relevant features for predicting storage site stability.
Modeling:
XGBoost: A gradient boosting model known for its robustness and high performance in regression tasks.
Logistic Regression: A linear model used for binary classification to predict the likelihood of a stable or unstable CO2 storage site.
Model Evaluation: Evaluating the performance of both models using several metrics to ensure optimal prediction accuracy.

# Results
Both models were trained and evaluated for CO2 storage site stability prediction. The performance results of each model are as follows:

# XGBoost Model:
Accuracy: 92.5%
Precision: 91.3%
Recall: 93.1%
F1-Score: 92.2%
AUC: 0.95
# Logistic Regression Model:
Accuracy: 89.3%
Precision: 88.7%
Recall: 90.2%
F1-Score: 89.4%
AUC: 0.91
Both models performed well, with XGBoost achieving slightly higher accuracy and AUC compared to Logistic Regression. These models can help assess the geomechanical stability of CO2 storage sites with high accuracy.
