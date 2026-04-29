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

## Limitations

This model captures general inflation trends but is not highly accurate. Inflation is influenced by many complex and nonlinear factors beyond unemployment and interest rates, including external factors such as the COVID-19 pandemic.

Additionally, linear regression assumes a simple linear relationship and cannot fully capture sudden spikes or structural changes in the data. While adding lagged variables improved performance, more advanced models and additional features would be required for higher accuracy.

## Technologies
- Python
- Pandas
- Matplotlib
- Scikit-learn

## Author
Rishab Anand
