# HousePricePrediction

## Task Objective
Predict house prices using Machine Learning models based on key property features.

## Dataset Used
- Dataset: Housing Price Dataset from Kaggle"
- Features include: number of bedrooms, bathrooms, square footage, location, year built, and others.
- Target variable: `Price` (continuous variable)
- Total records:489 entries

## Models Applied
- Linear Regression
- Gradient Boosting Regressor

## Key Results & Findings
- Linear Regression:
  - Mean Absolute Error (MAE): 50207.807
  - Root Mean Squared Error (RMSE): 64271.86
  - R² Score: 0.8386

- Gradient Boosting:
  - Mean Absolute Error (MAE):46693.439
  - Root Mean Squared Error (RMSE): 59551.506
  - R² Score: 0.812
- Insights:
  - Gradient Boosting performed better for non-linear relationships and gave more accurate predictions.
  - Important features affecting house prices: location, square footage, number of bedrooms, and year built.
  - Visualizations like predicted vs actual price plots help assess model performance.

## How to Run
1. Open `HousePricePrediction.ipynb` in Google Colab.
2. Run all cells to preprocess data, train models, and evaluate performance.
3. Results, plots, and metrics will display in the notebook.
