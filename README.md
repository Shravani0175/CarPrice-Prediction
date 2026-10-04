# Used Car Price Predictor

Predicts the selling price of a used car from age, kilometres driven, fuel type, brand and more.

## Problem
Helps buyers and sellers judge a fair price for a used car.

## Data
- Source: (paste your Kaggle link here), N rows
- Cleaning: duplicates removed, missing values filled, outliers trimmed, text columns converted to numbers

## Approach
- Features: car age, brand (rare brands grouped), one-hot encoded categories
- Target: log(price) to handle skew
- Models: Linear Regression, Random Forest, XGBoost, compared with 5-fold cross-validation

## Results
| Model | Test R² | MAE (₹) | RMSE (₹) |
|---|---|---|---|
| Linear Regression | | | |
| Random Forest | | | |
| XGBoost | | | |

Key price drivers: (fill in from the feature importance chart)

## Limitations
- (e.g. no city, variant or condition data; weaker on rare luxury cars)

## How to run
pip install -r requirements.txt
jupyter notebook car_price_predictor.ipynb
Download the dataset from the Kaggle link above and save it as cars.csv.
