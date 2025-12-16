# Next Best Action Recommender System

This repository implements multiple data mining and recommender system approaches
to predict **Next Best Actions (NBA)** for customers based on grocery transaction data.

## Team
- Isaiah Mariano – ALS Collaborative Filtering
- Angela De Leon – SVD Recommender System
- Lion Batoy – Association & Sequential Rule Mining

## Methods Used
- Exploratory Data Analysis (EDA)
- Feature Engineering (Frequency, Adjusted Frequency, TF-IDF, Ratio Ratings)
- Collaborative Filtering
  - Singular Value Decomposition (SVD)
  - Alternating Least Squares (ALS)
- Pattern Mining
  - FP-Growth
  - Apriori
  - Generalized Sequential Pattern (GSP)

## Folder Guide
- `data/` – raw and processed datasets
- `notebooks/` – Jupyter notebooks per method
- `src/` – reusable Python functions
- `results/` – outputs and evaluation metrics
- `reports/` – final paper / presentation PDF

## Key Findings
- Snack brands (Lay’s, Doritos, Ruffles) show strong repeat and sequential buying behavior
- Health supplements frequently co-occur and appear in sequential purchases
- TF-IDF-inspired ratings reduced popularity bias in collaborative filtering
- SVD achieved lower RMSE than ALS under sparse interaction settings

## Tools
- Python, Pandas, NumPy
- Surprise (SVD)
- PySpark / implicit (ALS)
- mlxtend (Apriori, FP-Growth)

