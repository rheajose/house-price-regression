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

## How to Run
1. Clone this repository
   git clone https://github.com/YOUR_USERNAME/house-price-regression.git

2. Install dependencies
   pip install -r requirements.txt

3. Download train.csv from Kaggle and place it in the project folder

4. Open and run the notebook
   jupyter notebook house_price_regression.ipynb

## Tools & Libraries
- Python 3.9+
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

## Skills Demonstrated
- Data cleaning and exploratory analysis
- Feature engineering and selection
- Supervised ML (linear regression)
- Model evaluation and diagnostics
- End-to-end ML pipeline