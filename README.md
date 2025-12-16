# Next Best Action Recommender System
This repository implements a comprehensive set of data mining and recommender system techniques to identify and predict Next Best Actions (NBA) for customers using grocery transaction data. The project combines exploratory data analysis, feature-engineered collaborative filtering models (SVD and ALS), and pattern discovery methods (association rule mining and sequential pattern mining) to uncover customer purchasing behavior. These approaches provide actionable insights for personalized recommendations, product bundling, and marketing strategies by capturing both latent preferences and frequent or sequential buying patterns.

## Task
Explore different machine learning models or approaches to create a recommender system.


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

