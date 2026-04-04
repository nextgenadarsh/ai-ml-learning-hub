# Hyperparameter Tuning & Optimization

## Overview
This lab covers hyperparameter tuning strategies, practical recipes, and experiment management. Topics include grid search, random search, Bayesian optimization (Optuna), and practical tips for tuning deep learning models.

## Learning Objectives
- Understand hyperparameters vs parameters
- Use `GridSearchCV` and `RandomizedSearchCV` for scikit-learn models
- Implement Bayesian optimization with `Optuna`
- Track experiments with `wandb` or `mlflow`
- Practical heuristics for tuning deep networks

## Example: Optuna quick-start
```python
import optuna
from sklearn.datasets import load_iris
from sklearn.svm import SVC
from sklearn.model_selection import cross_val_score

X, y = load_iris(return_X_y=True)

def objective(trial):
    C = trial.suggest_loguniform('C', 1e-3, 1e3)
    gamma = trial.suggest_loguniform('gamma', 1e-4, 1e-1)
    clf = SVC(C=C, gamma=gamma)
    return cross_val_score(clf, X, y, n_jobs=-1, cv=3).mean()

study = optuna.create_study(direction='maximize')
study.optimize(objective, n_trials=50)
print(study.best_params)
```

## Exercises
- Tune an XGBoost model on a tabular dataset using Optuna
- Compare grid vs random vs Bayesian search timings and results
- Use early stopping and pruning in Optuna for deep learning

---

> See `requirements.txt` for `optuna` and experiment tracking tools.