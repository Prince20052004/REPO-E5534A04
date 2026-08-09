# Week 4 — Project 5 Development: Predictive Modeling (Regression)

## Work Completed
- Built and explored the housing dataset (EDA, correlation analysis)
- Cleaned missing values (median imputation on GarageSpaces)
- Engineered features (RoomsTotal, QualityPerAge) and set up a leak-free preprocessing +
  modeling pipeline (scaling + one-hot encoding via ColumnTransformer)
- Trained a baseline Linear Regression model

## Working Analysis
See the full, executed notebook in `Week5/Project5_Predictive_Modeling_Regression.ipynb`,
which contains this development work plus the completed model tuning and evaluation
(Sections 1–6 cover this week's scope).

## Next Steps (Week 5)
- Tune Ridge Regression via cross-validated GridSearchCV
- Evaluate both models on the held-out test set (R², RMSE, MAE), run residual diagnostics,
  and interpret coefficients for business insight
