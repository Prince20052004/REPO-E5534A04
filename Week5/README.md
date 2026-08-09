# Week 5 — Project 5 Completion: Predictive Modeling (Regression)

## Deliverables
- `Project5_Predictive_Modeling_Regression.ipynb` — full, executed, reproducible notebook:
  EDA, cleaning, feature engineering, Linear Regression vs. tuned Ridge Regression (GridSearchCV),
  test-set evaluation (R²/RMSE/MAE), residual analysis, and coefficient-based business insights.
- `housing_data.csv` — the cleaned/engineered dataset used for modeling.
- `model_predictions.csv` — held-out test set with actual vs. predicted sale price per property.

## Summary of Findings
Ridge Regression (tuned alpha) performs comparably to plain Linear Regression on this feature
set, with OverallQuality, SqFt, and location (Waterfront/Downtown) as the strongest positive
price drivers, and DistanceToCityKm as the strongest negative driver. Residuals show no
systematic bias across the predicted price range.
