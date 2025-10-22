Crop Yield Prediction using Machine Learning and Deep Learning

Author: Marie Elyse Uyiringiye
Course: Introduction to Machine Learning
Institution: African Leadership University
Date: October 2025

 Project Overview

This project applies both classical machine learning and deep learning approaches to predict crop yield (hg/ha_yield) using environmental and agricultural features such as average rainfall, temperature, and pesticide usage. The goal is to compare the performance of different models and identify which techniques best capture the complex relationships influencing agricultural productivity.

The mission is to harness data-driven insights to improve agricultural decision-making and support sustainable farming practices in the context of climate variability and food security challenges.

 Objectives

Develop and evaluate multiple predictive models for crop yield estimation.

Compare traditional ML algorithms (e.g., Random Forest, XGBoost) with deep learning models (e.g., CNN, LSTM).

Visualize and analyze model performance using learning curves, loss curves, confusion matrices, and ROC curves.

Interpret results to identify patterns, potential improvements, and real-world implications.

 Dataset

The dataset contains 28,242 records with the following key features:

Feature	Description
Area	Country or region name
Item	Crop type
Year	Observation year
hg/ha_yield	Crop yield (hectogram per hectare)
average_rain_fall_mm_per_year	Annual average rainfall
pesticides_tonnes	Amount of pesticides used
avg_temp	Average annual temperature

Source: FAO (Food and Agriculture Organization) public dataset.

 Methodology

Data Preprocessing – Handling missing values, encoding categorical variables, normalization, and feature selection.

Model Development – Implementing:

Traditional ML models: Linear Regression, Ridge, Lasso, Random Forest, Gradient Boosting, XGBoost, SVR.

Deep Learning models: Simple DNN, Deep DNN, CNN, LSTM, Functional API.

Model Evaluation – Comparing performance using metrics:

Mean Absolute Error (MAE)

Root Mean Square Error (RMSE)

R² Score

Visualization – Validation curves, ROC curves, and confusion matrices.

 Model Results Summary
Model	MAE	RMSE	R²
Random Forest	3492.06	9677.71	0.9878
XGBoost	7834.22	13865.96	0.9735
Gradient Boosting	20440.27	32361.61	0.8556
Ridge Regression	62370.96	81499.16	0.0843
Lasso Regression	62370.69	81499.30	0.0843
Linear Regression	62370.68	81499.30	0.0843
SVR	57253.08	93415.39	-0.2030

 Best Model: Random Forest (highest R² and lowest MAE)

 Deep Learning Results

Figure: Validation MAE Comparison Across Deep Learning Models
(Insert your visual here.)

LSTM and CNN models showed competitive results but were outperformed by ensemble-based ML models (Random Forest and XGBoost), highlighting the efficiency of tree-based learners for structured tabular data.

 Visualizations

Include the following visuals in your notebook/report:

Correlation heatmap (feature relationships)

Scatter plots (Yield vs Temperature/Rainfall)

Learning/Loss curves for DL models

ROC curves and Confusion Matrices

Model comparison bar charts

 How to Run the Notebook
Open the summative_Intro.ipynb file in Jupyter or Google Colab.

Install dependencies:

pip install numpy pandas seaborn matplotlib scikit-learn tensorflow xgboost


Run all cells sequentially (Runtime → Run all).

Review model outputs and plots in the notebook.
Open the summative_Intro.ipynb file in Jupyter or Google Colab.

Install dependencies:

pip install numpy pandas seaborn matplotlib scikit-learn tensorflow xgboost


Run all cells sequentially (Runtime → Run all).

Review model outputs and plots in the notebook.
