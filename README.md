# Dhaivik Reddy

**Data Science & Machine Learning Student** · Hyderabad, India

I build machine learning systems that start small, get measured honestly, and end up in front of real people.

---

## About

My first line of ML code was a linear regression on house prices, and I remember being surprised that a straight line could explain most of the variation in something as messy as real estate.

Then I made the same project with invented numbers and got an R² of 0.90 — and it felt hollow. Switching to the real California Housing dataset dropped it to 0.81 and taught me more in an afternoon than months of tutorials. Every project here runs on real public data now, measured honestly, including the parts where the result isn't flattering.

I'm a student who builds things, breaks them, reads the error, and writes down what happened. Every metric in every repo is one I actually measured by running the code.

---

## What I'm working on

- **Deep learning** — CNNs and LSTMs, working toward transfer learning
- **ML engineering** — packaging models, serving them behind APIs, reproducible experiments
- **Statistics literacy** — knowing what a metric means before trusting it
- **Clean code** — because a model nobody else can run isn't finished

---

## Stack

```
Python · pandas · NumPy · scikit-learn · PyTorch · XGBoost
Matplotlib · Seaborn · imbalanced-learn · torchvision
Git · Linux · Jupyter · Docker · pytest
```

---

## Projects

Ten projects across the three stages I actually worked through. The levels aren't marketing — they're roughly the order I'd tackle them in if I started again.

Every repo runs on **real public data**, downloads it automatically on first run, and includes a LICENSE, tests, and a CI workflow.

### Level 1 — Foundations

Getting comfortable with the core loop: load data, split it, fit a model, read the metrics.

| Project | Dataset | Concept it taught me |
|---|---|---|
| [House Price Prediction](https://github.com/dhaivikreddy-12/house-price-prediction) | California Housing, 20,640 real homes | Regression, R² vs RMSE, comparing three models fairly |
| [Iris Classifier](https://github.com/dhaivikreddy-12/iris-classifier) | Fisher's Iris, 150 samples | KNN vs logistic regression, reading a confusion matrix |
| [Diabetes Progression Predictor](https://github.com/dhaivikreddy-12/diabetes-progression-predictor) | Diabetes, 442 real patients | Random forests, feature importance as a story |

### Level 2 — Real-world problems

Where the data fights back: imbalance, missing values, and metrics that matter more than accuracy.

| Project | Dataset | Concept it taught me |
|---|---|---|
| [Customer Churn Prediction](https://github.com/dhaivikreddy-12/customer-churn-prediction) | Telco Churn, 7,043 subscribers | Why accuracy lies on imbalanced data; a text column that needs coercing |
| [Credit Card Fraud Detection](https://github.com/dhaivikreddy-12/credit-card-fraud-detection) | Credit Card Fraud, 284,807 transactions (0.17% fraud) | SMOTE, average precision vs ROC-AUC, threshold tuning |
| [Spam Message Classifier](https://github.com/dhaivikreddy-12/spam-message-classifier) | UCI SMS Spam, 5,572 real messages | TF-IDF, text preprocessing, why Naive Bayes still wins |
| [Heart Disease Risk Prediction](https://github.com/dhaivikreddy-12/heart-disease-risk-prediction) | UCI Cleveland, 303 patients | Cross-validation, imputing real missing values, medical ML ethics |

### Level 3 — Deep learning

Moving past hand-engineered features into representation learning.

| Project | Dataset | Concept it taught me |
|---|---|---|
| [Image Classification CNN](https://github.com/dhaivikreddy-12/image-classification-cnn) | MNIST, 70,000 real handwritten digits | Convolutions, batch norm, LR schedules, validation splits |
| [Stock Price Forecasting LSTM](https://github.com/dhaivikreddy-12/stock-price-forecasting-lstm) | Real AAPL daily prices, 1,255 sessions | Sequence models, normalisation, where LSTMs still fail |
| [Movie Recommender System](https://github.com/dhaivikreddy-12/movie-recommender-system) | MovieLens, 100,836 real ratings | Matrix factorization, early stopping, honest baselines |

---

## Approach

A few things I've settled into while building these:

- **Real data or nothing.** Synthetic data teaches the syntax of a pipeline and nothing about the data. Every project here downloads a genuine public dataset.
- **Baseline first.** Most of the time the answer is logistic regression, not a transformer.
- **Compare against an honest baseline.** Using the test-set mean to score a model flatters it — I did exactly that in the recommender and had to redo it.
- **Impute inside the pipeline.** Never before the split. The Cleveland dataset has real missing values, which is the point.
- **Report the unflattering number too.** The recommender was worse than baseline until I added early stopping. That debugging story is more useful than the final score.

---

## Currently learning

Transfer learning and fine-tuning · model deployment behind FastAPI · experiment tracking with MLflow and W&B · reinforcement learning fundamentals

## Connect

[![GitHub](https://img.shields.io/badge/GitHub-dhaivikreddy--12-181717?style=flat&logo=github&logoColor=white)](https://github.com/dhaivikreddy-12)

Open to feedback on any of these projects, and to collaborating on anything data-shaped.

---

*Still a student. Still building. Still measuring honestly.*
