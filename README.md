# Inflation Prediction Model

## Overview
This project analyzes U.S. economic data to predict inflation using unemployment rates and interest rates.

## Data Sources
- CPI (Consumer Price Index)
- UNRATE (Unemployment Rate)
- FEDFUNDS (Federal Funds Rate)
- GS10 (10-Year Treasury Yield)

All data sourced from the Federal Reserve Economic Data (FRED).

## Methodology
- Merged datasets by date
- Calculated year-over-year inflation
- Built regression models to predict inflation
- Evaluated performance using MAE and RMSE
- Compared Linear Regression and Random Forest models

## Results
The model captures general inflation trends. Adding lagged variables improved predictive performance.

## Technologies
- Python
- Pandas
- Matplotlib
- Scikit-learn

## Author
Rishab Anand
