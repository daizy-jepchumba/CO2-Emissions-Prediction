# SDG13 — Predicting CO₂ Emissions (Daizy Jepchumba)

## Project Overview
This project predicts country-level CO₂ emissions (kt) using historical data from Kaggle.
**SDG:** 13 — Climate Action

## Dataset
Source: CO₂ Emissions by Country — Kaggle  
Path: `/kaggle/input/co2-emissions-by-country/co2_emissions_kt_by_country.csv`

## Approach
- Exploratory Data Analysis (global and per-country trends)
- Models:
  - Baseline: Linear Regression (country + year)
  - Improved: Random Forest Regressor
- Evaluation: MAE, MSE, R², and visual actual vs predicted plots

## Results
Model Evaluation:
Mean Absolute Error (MAE): 1278837.16
Mean Squared Error (MSE): 6726124881346.41
R² Score: 0.00 
Kenya R2: 0.7978302393535925

## How to run
1. Open `notebook.ipynb` in Jupyter/Kaggle.  
2. Run all cells.  
3. See the “Model Evaluation” outputs and plots.

## Author
Daizy Jepchumba Kiplagat — daisyjepchum@gmail.com
