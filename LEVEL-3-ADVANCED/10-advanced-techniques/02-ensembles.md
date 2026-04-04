# Ensemble Methods

## Overview
Covers bagging, boosting, stacking, and practical ensemble strategies for improving model performance and robustness.

## Learning Objectives
- Implement Random Forests and Gradient Boosting
- Understand boosting algorithms (XGBoost, LightGBM, CatBoost)
- Build stacking ensembles and blending strategies
- Evaluate when ensembles are beneficial

## Example: Simple stacking with scikit-learn
```python
from sklearn.ensemble import RandomForestClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import cross_val_predict
from sklearn.datasets import load_breast_cancer
from sklearn.metrics import accuracy_score

X, y = load_breast_cancer(return_X_y=True)
base1 = RandomForestClassifier(n_estimators=50)
base2 = RandomForestClassifier(n_estimators=100, max_depth=3)

# Create simple stacking features
p1 = cross_val_predict(base1, X, y, cv=5, method='predict_proba')[:,1]
p2 = cross_val_predict(base2, X, y, cv=5, method='predict_proba')[:,1]

import numpy as np
X_stack = np.vstack([p1, p2]).T
meta = LogisticRegression()
meta.fit(X_stack, y)
print('Stacking ready')
```

## Exercises
- Build a stacking ensemble for a Kaggle tabular problem
- Compare performance of single models vs ensemble
- Implement model selection to reduce ensemble size
