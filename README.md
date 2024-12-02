# MSE1065: Solubility Prediction Project

This repository contains the implementation of various machine learning models for predicting solubility based on molecular descriptors and features engineered using RDKit.

## **Project Overview**

The goal of this project is to predict the solubility of chemical compounds using traditional machine learning approaches. The dataset includes molecular descriptors for drugs and solvents, engineered using the RDKit library, alongside solubility measurements.

The repository demonstrates feature engineering, exploratory data analysis (EDA), model training, evaluation, and visualization for solubility prediction.

---

## **Key Features**
1. **Feature Engineering**:
   - Molecular descriptors calculated using RDKit, including:
     - Molecular Weight (MolWt)
     - LogP
     - Topological Polar Surface Area (TPSA)
     - Number of Hydrogen Bond Donors and Acceptors
   - Advanced preprocessing techniques to handle missing values and standardize data.

2. **Models Implemented**:
   - Linear Regression
   - Ridge Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - K-Nearest Neighbors (KNN)
   - Support Vector Regressor (SVR)

3. **Evaluation Metrics**:
   - Root Mean Squared Error (RMSE)
   - Coefficient of Determination (\(R^2\))

4. **Visualization**:
   - Model performance comparison plots.
   - Predicted vs. Actual solubility plots.
   - Feature correlation heatmap.
   - PCA visualization for feature dimensionality.

---

## **Repository Structure**

├── data/ # Dataset files ├── notebooks/ # Jupyter notebooks for EDA and model training ├── src/ # Source code for feature engineering and models ├── results/ # Output results and visualizations ├── README.md # Project documentation
