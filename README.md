# Store Sales Time Series Forecasting

This repository contains a comprehensive analysis and implementation of time series forecasting for store sales using various machine learning models and data engineering techniques.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Overview](#data-overview)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Feature Engineering](#feature-engineering)
5. [Modeling](#modeling)
6. [Evaluation](#evaluation)
7. [How to Use](#how-to-use)
8. [Dependencies](#dependencies)

## Introduction

This project aims to predict store sales based on historical data using advanced feature engineering and machine learning models. The workflow includes data preprocessing, exploratory data analysis, feature engineering, modeling, and evaluation.

## Data Overview

The project utilizes data from the Kaggle competition [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting). Key datasets include:

- `train.csv`: Historical sales data for training.
- `test.csv`: Data for testing model predictions.
- `oil.csv`: Daily oil prices.
- `holidays_events.csv`: Holiday and event information.
- `stores.csv`: Store metadata.
- `transactions.csv`: Transaction details.

## Exploratory Data Analysis

Key steps in EDA include:
- Understanding data distributions.
- Identifying missing values and handling them appropriately.
- Analyzing relationships between features.

## Feature Engineering

Notable techniques applied:
- Date feature extraction (e.g., year, month, day).
- Handling categorical data using encoding methods.
- Outlier detection and skewness adjustments.
- One-hot encoding for categorical variables.

## Modeling

Several regression models were tested, including:
- Linear Regression
- Ridge Regression
- Decision Tree Regressor

Models were evaluated using metrics like:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared Score (R²)

## Evaluation

The Decision Tree Regressor provided the best performance, achieving high accuracy on test datasets. Visualizations of model comparisons are available in the notebook.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/bharath03-a/time_series


## Dependencies
The project uses the following Python libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn