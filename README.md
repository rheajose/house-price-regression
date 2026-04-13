# House Price Prediction — Linear Regression

## Problem
Predict residential house sale prices using structured property data
from the Kaggle House Prices dataset.

## Approach
- Exploratory data analysis (distributions, correlations, null handling)
- Feature selection based on correlation with SalePrice
- StandardScaler normalisation to improve coefficient stability
- sklearn LinearRegression with 80/20 train/test split

## Results
| Metric | Score |
|--------|-------|
| RMSE   | ~$30,000 |
| R²     | ~0.85 |

## Files
- `house_price_regression.ipynb` — full notebook with outputs
- `price_distribution.png` — target variable distribution
- `correlation_heatmap.png` — top feature correlations
- `actual_vs_predicted.png` — model fit visualisation
- `residuals_plot.png` — residual diagnostic

## Setup
pip install -r requirements.txt