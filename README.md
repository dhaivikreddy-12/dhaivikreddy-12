# Dhaivik Reddy

**Data Science & Machine Learning Student** · Hyderabad, India

I build machine learning systems that start small, get measured honestly, and end up in front of real people.

---

## About

My first line of ML code was a linear regression on house prices, and I remember being genuinely surprised that a straight line could explain 90% of the variance in something as messy as real estate.

That curiosity turned into a habit: pick a problem, build the simplest thing that works, then measure how badly it fails. Most of what I've learned came from step two — when the model hit 0.62 AUC and I had to figure out *why* rather than swap in something bigger.

I'm not trying to pretend I'm an expert. I'm a student who builds things, reads the documentation, breaks them, fixes them, and writes down what happened. Every repo here runs end-to-end on a laptop, and every metric quoted is one I actually measured.

---

## What I'm working on

- **Deep learning** — CNNs, LSTMs, and now transfer learning
- **ML engineering** — packaging models, serving them behind APIs, reproducible experiments
- **Statistics literacy** — knowing what a metric means before trusting it
- **Clean code** — because a model nobody else can run isn't finished

---

## Stack

```
Python · pandas · NumPy · scikit-learn · PyTorch
Matplotlib · Seaborn · XGBoost · imbalanced-learn
Git · Linux · Jupyter · Docker
```

---

## Projects

Ten projects, organised into the three stages I actually worked through. The level isn't marketing — it's roughly the order I'd tackle them in if I were starting again.

### Level 1 — Foundations

Getting comfortable with the core loop: load data, split it, fit a model, read the metrics.

| Project | Problem it solves | Concept it taught me |
|---|---|---|
| [House Price Prediction](https://github.com/dhaivikreddy-12/house-price-prediction) | Estimate a home's value from size, rooms, and age | Regression, R² vs RMSE, why you always need a test set |
| [Iris Classifier](https://github.com/dhaivikreddy-12/iris-classifier) | Sort a flower into one of three species | KNN vs logistic regression, reading a confusion matrix |
| [Student Marks Predictor](https://github.com/dhaivikreddy-12/student-marks-predictor) | Predict exam scores from study habits | Random forests, feature importance as a story |

### Level 2 — Real-world problems

Where the data fights back: imbalance, messy categories, and metrics that matter more than accuracy.

| Project | Problem it solves | Concept it taught me |
|---|---|---|
| [Customer Churn Prediction](https://github.com/dhaivikreddy-12/customer-churn-prediction) | Find subscribers about to cancel | Why accuracy lies on imbalanced data; AUC |
| [Credit Card Fraud Detection](https://github.com/dhaivikreddy-12/credit-card-fraud-detection) | Flag fraud in 20,000 transactions | SMOTE, precision/recall trade-offs, threshold tuning |
| [Spam Message Classifier](https://github.com/dhaivikreddy-12/spam-message-classifier) | Separate spam from genuine messages | TF-IDF, text preprocessing, why Naive Bayes still wins |
| [Heart Disease Risk Prediction](https://github.com/dhaivikreddy-12/heart-disease-risk-prediction) | Screen patients for cardiovascular risk | Cross-validation, and the ethics of medical-adjacent models |

### Level 3 — Deep learning

Moving past hand-engineered features into representation learning.

| Project | Problem it solves | Concept it taught me |
|---|---|---|
| [Image Classification CNN](https://github.com/dhaivikreddy-12/image-classification-cnn) | Recognise shapes from raw pixels | Convolutions, the training loop, PyTorch |
| [Stock Price Forecasting LSTM](https://github.com/dhaivikreddy-12/stock-price-forecasting-lstm) | Forecast a price series from its history | Why sequence models exist, and where they still fail |
| [Movie Recommender System](https://github.com/dhaivikreddy-12/movie-recommender-system) | Suggest films from rating behaviour alone | Matrix factorization, latent features, collaborative filtering |

Every repo is self-contained — synthetic datasets are generated on first run, so `pip install -r requirements.txt` then the entry-point script is genuinely all you need. No download walls, no missing data.

---

## Approach

A few things I've settled into while building these:

- **Baseline first.** Most of the time the answer is logistic regression, not a transformer.
- **One metric isn't enough.** If I can't state the business cost of a false positive, I don't understand the problem yet.
- **Synthetic data is a teaching tool.** It lets the whole pipeline run offline, which means more people can actually learn from it.
- **Write the honest result.** A model that scores 1.1 RMSE and says so is more useful than one that hides the number.

---

## Currently learning

Transfer learning and fine-tuning · model deployment behind FastAPI · experiment tracking with MLflow and W&B · reinforcement learning fundamentals

## Connect

[![GitHub](https://img.shields.io/badge/GitHub-dhaivikreddy--12-181717?style=flat&logo=github&logoColor=white)](https://github.com/dhaivikreddy-12)

Open to feedback on any of these projects, and to collaborating on anything data-shaped.

---

*Still a student. Still building. Still measuring honestly.*
