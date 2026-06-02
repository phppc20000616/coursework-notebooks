# Machine Learning Refined — Implementations & Analysis

Implementations and analyses from EE 475 (Machine Learning) at Northwestern University, following the *Machine Learning Refined* curriculum. Covers optimization theory, convex analysis, supervised learning, and ensemble methods, with a capstone regression project.

---

## Notebooks

| File | Topic |
|------|-------|
| [`optimization-fundamentals.ipynb`](optimization-fundamentals.ipynb) | Gradient descent, random sampling, curse of dimensionality |
| [`convex-functions.ipynb`](convex-functions.ipynb) | Convexity, logistic loss, softplus, quadratic forms |
| [`newtons-method.ipynb`](newtons-method.ipynb) | Newton's method, quadratic approximation, convergence |
| [`supervised-learning.ipynb`](supervised-learning.ipynb) | Linear & logistic regression, softmax multi-class classification |
| [`nonlinear-regression.ipynb`](nonlinear-regression.ipynb) | Log-linear regression (Moore's Law), polynomial feature expansion |
| [`cross-validation.ipynb`](cross-validation.ipynb) | Model selection, train/validation splits, polynomial degree tuning |
| [`bagging-ensemble.ipynb`](bagging-ensemble.ipynb) | Bagging over polynomial classifiers, majority-vote aggregation |

---

## Project: Housing Price Prediction

[`housing-price-prediction/`](housing-price-prediction/) — End-to-end regression analysis on Cook County (Chicago) residential property records from the Cook County Assessor's Office. Key steps:

- **EDA & cleaning** — log-transformed skewed price distribution, filtered outliers
- **Feature engineering** — extracted bedroom counts from text descriptions; one-hot encoded categorical variables
- **Modeling** — compared linear regression, ridge regression, and gradient-boosted regressors via cross-validation
- **Diagnostics** — residual analysis, prediction vs. actual plots

Key file: [`housing-price-prediction.ipynb`](housing-price-prediction/housing-price-prediction.ipynb)  
*Note: training data (~94 MB) excluded due to size.*

---

## Datasets

Small datasets used by the notebooks are included in [`mlrefined_datasets/`](mlrefined_datasets/) — a subset of the companion data for the *Machine Learning Refined* textbook (Watt, Borhani & Katsaggelos). Large files (face data, gene expression) are excluded; the full dataset collection is available at [github.com/jermwatt/machine_learning_refined](https://github.com/jermwatt/machine_learning_refined).

---

## Tech Stack

- **Python** — NumPy, pandas, scikit-learn, matplotlib
- **Autograd** — automatic differentiation for gradient and Hessian computation
