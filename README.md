# Tamina-ML-Tg-project


This repository contains code for predicting the glass transition temperature (Tg) of polymers using machine learning techniques. The model utilizes Extended Connectivity Fingerprints (ECFP) for feature representation and implements various regression algorithms, including LightGBM, XGBoost, and Random Forest.

Features
Data Preparation: Converts SMILES representations of polymers to ECFP4.
Model Training: Implements multiple regression models for Tg prediction.
Evaluation Metrics: Evaluates model performance using RMSE and R².
Requirements
Python 3.x
Pandas
NumPy
Scikit-learn
LightGBM
XGBoost
CatBoost
RDKit
Usage
Clone this repository.
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Run the main script to train the models and make predictions.
