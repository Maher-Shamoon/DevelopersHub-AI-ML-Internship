# Task 6: House Price Prediction

## Objective
Predict median house prices using property and neighborhood features.

## Dataset
- **Name:** California Housing Dataset
- **Source:** Built-in via Scikit-learn
- **Size:** 20,640 house records from 1990 California census

## Models Applied
- Linear Regression (baseline)
- Gradient Boosting Regressor (200 trees)

## Key Results & Findings
- Gradient Boosting achieved R² of approximately 0.85+
- Linear Regression achieved R² of approximately 0.60
- Median income is the single strongest price predictor
- Location (latitude/longitude) is second most important factor
- Coastal California areas are 2-3x more expensive than inland
- Engineered features (RoomsPerBedroom, IncomePerOccupant) added value