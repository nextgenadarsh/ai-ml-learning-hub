# Model Interpretability & Explainability

## Overview
Covers interpretation tools and techniques such as SHAP, LIME, feature importance, partial dependence plots, and model debugging.

## Learning Objectives
- Use SHAP to explain tree-based and neural models
- Create partial dependence and ICE plots
- Diagnose model errors via feature contributions
- Build interpretable pipelines and document assumptions

## Example: SHAP with XGBoost
```python
import xgboost as xgb
import shap
from sklearn.datasets import load_boston

X, y = load_boston(return_X_y=True)
model = xgb.XGBRegressor().fit(X, y)
explainer = shap.TreeExplainer(model)
shap_values = explainer.shap_values(X)
shap.summary_plot(shap_values, X)
```

## Exercises
- Generate SHAP explanations for a classification model
- Use partial dependence plots to inspect feature interactions
- Create a reproducible interpretability report
