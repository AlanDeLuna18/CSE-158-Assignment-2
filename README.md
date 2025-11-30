#### **Project Overview**

This project focuses on building and evaluating recommender systems for **recipe rating prediction** using the Food.com dataset. In the modern digital age, online recipe platforms host millions of recipes with user-generated ratings and reviews. Understanding what drives user satisfaction and accurately predicting recipe ratings is crucial for improving user experience and content recommendation.

Our primary objective is to **predict user ratings for recipes** (on a scale of 1-5 stars) by developing and comparing multiple recommendation algorithms. This regression task aims to minimize the Root Mean Squared Error (RMSE) between predicted and actual ratings.

We implement and evaluate several approaches:
- **Baseline models**: Global averages and popularity-based predictors
- **Latent factor models**: Matrix factorization with user and item biases
- **Markov Chain models**: Sequential pattern modeling for user behavior
- **Ensemble methods**: XGBoost and LightGBM with engineered features
- **Neighborhood methods**: k-Nearest Neighbors with content similarity
