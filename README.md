# Supervised Machine Learning & Predictive Pipeline

## Project Overview
This repository contains an end-to-end supervised machine learning pipeline implemented in Python[cite: 5]. The project analyzes historical Steam player metrics to predict average concurrent player counts using game characteristics, release features, and historical engagement trends[cite: 5].

## Key Technical Implementation
- **Data Ingestion & Cleaning:** Programmatically fetched and processed tens of thousands of historical gaming records from the TidyTuesday repository[cite: 5], handling missing values and validating shapes[cite: 5].
- **Exploratory Data Analysis & Visualizations:** Generated logarithmic distribution plots and correlation heatmaps to explore player base skews and feature collinearity[cite: 5].
- **Model Training & Hyperparameter Tuning:** Developed robust regression pipelines using `scikit-learn` across Multiple Linear Regression, Random Forest Regressor, and K-Nearest Neighbors (KNN) models[cite: 5].
- **Rigorous 10-Fold Cross-Validation:** Evaluated models using 10-fold cross-validation with $R^2$ scoring metrics to prevent overfitting and robustly benchmark predictive accuracy[cite: 5].

## Model Performance Summary
| Model | Mean $R^2$ Score | Standard Deviation |
| :--- | :--- | :--- |
| **Multiple Linear Regression** | 0.9730 | +/- 0.0103 |
| **Random Forest Regressor** | **0.9797** | **+/- 0.0107** |
| **K-Nearest Neighbors (KNN)** | 0.9572 | +/- 0.0190 |

## Tech Stack
- **Language:** Python[cite: 5]
- **Libraries:** Scikit-Learn[cite: 5], Pandas[cite: 5], NumPy[cite: 5], Matplotlib[cite: 5], Seaborn[cite: 5]
- **Environment:** Jupyter Notebook / Google Colab[cite: 5]

## Repository File Structure
- `DAT502_Project2_VideoGames.ipynb` — Full source code notebook containing data preprocessing, feature engineering, cross-validation, and performance evaluation metrics[cite: 5].
