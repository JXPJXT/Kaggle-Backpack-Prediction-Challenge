# Kaggle-Backpack-Prediction-Challenge
## Predicting Backpack Prices – Kaggle Tabular Playground Series

This project was developed as part of the Kaggle Tabular Playground Series, with the goal of predicting the price of backpacks based on various attributes. The competition challenges participants to build machine learning models using approachable datasets, with a new challenge released each month.

## Problem Statement

Given a dataset with different backpack attributes, our objective is to predict the **Price** for each backpack. The model performance is evaluated using the **Root Mean Squared Error (RMSE)**, which is defined as:
RMSE = sqrt((1/N) * Σ (y_i - ŷ_i)²)

- *y_i*: The actual price.
- *ŷ_i*: The predicted price for each instance *i*.

## Approach & Methodology

### Data Exploration & Preprocessing
- **Exploratory Data Analysis (EDA):** We examined feature distributions and identified any anomalies or missing values.
- **Data Cleaning:** The dataset was preprocessed to remove inconsistencies and prepare high-quality inputs for our modeling.

### Feature Engineering
- **Transformation:** New features were created and existing ones transformed to better capture underlying patterns.
- **Combination Testing:** Various feature combinations were experimented with to improve model generalization and prediction accuracy.

### Modeling
- **Model Experimentation:** Multiple regression models were explored to determine the best fit for predicting backpack prices.
- **Hyperparameter Tuning:** We fine-tuned our models using cross-validation to optimize the RMSE score.

### Evaluation
- **Metric:** Our primary metric is RMSE.
- **Outcome:** The final model configuration achieved a competitive RMSE on the validation set, indicating effective preprocessing, feature engineering, and model tuning.

### Submission Preparation
- The final predictions are structured into a submission file with the required format:

## Competition Details

- **Competition Name:** Kaggle Tabular Playground Series
- **Objective:** Predict the price of backpacks given various attributes.
- **Timeline:**
- **Start Date:** February 1, 2025
- **Final Submission Deadline:** February 28, 2025 (all deadlines are at 11:59 PM UTC)
- **Evaluation Metric:** RMSE

The competition provides an interesting and approachable dataset, allowing the Kaggle community to practice their machine learning skills and iterate rapidly through various model and feature engineering ideas.

## Authors

- **Japjot**
- **Gurkirat**
- **Hardik**
