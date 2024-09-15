# Walmart Sales Forecast Modeling

This repository contains a Jupyter Notebook for modeling and forecasting Walmart sales. The goal is to predict future sales based on historical data using machine learning models like Random Forest and XGBoost.

## Overview

The notebook outlines the process of:
- Loading and preprocessing sales data.
- Performing data analysis and visualization.
- Training machine learning models to forecast Walmart sales.

## Project Steps

1. **Importing Libraries**:  
   The notebook begins by importing essential libraries including `pandas`, `matplotlib`, `seaborn`, and machine learning tools such as `RandomForestRegressor`, `ExtraTreesRegressor`, and `XGBoost`.

2. **Loading Data**:  
   The dataset (`trte_featured.csv`) is loaded for analysis, containing features such as dates and sales information.

3. **Data Preprocessing**:  
   Various data preparation techniques are applied, including handling missing values, data normalization, and feature engineering.

4. **Model Training**:  
   Models like Random Forest and XGBoost are trained on the preprocessed dataset. The notebook also leverages `RandomizedSearchCV` for hyperparameter tuning.

5. **Evaluation**:  
   The model's performance is evaluated using metrics such as `mean_squared_error`, `mean_absolute_error`, `r2_score`, and `mean_absolute_percentage_error`.

6. **Model Saving**:  
   Trained models are saved using `pickle` for later use.

## How to Run the Project

### Prerequisites

- Python 3.x
- Jupyter Notebook
- The following Python libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `xgboost`
  - `statsmodels`

### Installation

To install the required packages, run:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost statsmodels
