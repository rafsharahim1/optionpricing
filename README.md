Options Pricing: Black-Scholes vs. Machine Learning (Random Forest and XGBoost)
This project compares the predictive accuracy of the traditional Black-Scholes option pricing model with modern machine learning models, specifically Random Forest and XGBoost. Using historical stock data, the goal is to evaluate whether machine learning models can outperform Black-Scholes in pricing financial options, particularly for out-of-the-money (OTM) options.

Project Overview
Options pricing is a crucial aspect of financial markets, and the Black-Scholes model has long been a standard method for calculating option prices. However, the model's assumptions, such as constant volatility, limit its accuracy in real-world market dynamics. This project explores whether machine learning models, which can capture more complex patterns, offer better accuracy in predicting option prices.

Key Features
Data Source: Historical stock data from Yahoo Finance.
Models Used:
Black-Scholes Model: Traditional financial model for option pricing.
Random Forest Regressor: A decision tree-based ensemble model.
XGBoost Regressor: A gradient boosting model optimized for speed and performance.
Feature Engineering: Includes rolling volatility, stock price metrics (Open, High, Low, Close), and volume.
Model Comparison: Evaluates pricing accuracy based on RMSE (Root Mean Squared Error) and residual analysis.
Visualization: Side-by-side comparison of actual stock prices, Black-Scholes predictions, and machine learning predictions.
Results
Both Random Forest and XGBoost outperformed the Black-Scholes model, particularly for OTM options.
XGBoost showed the best balance between accuracy and generalization, making it a preferred choice for option pricing in dynamic market environments.
Black-Scholes struggled with volatility sensitivity, leading to mispricing when volatility was inaccurately estimated.
