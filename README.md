# Cryptocurrency_Price_Forecasting

**Overview:**  
The proposed project focuses on predicting future prices for various cryptocurrencies, including Monero, Ethereum, Wrapped Bitcoin, and Bitcoin, by utilizing historical price data. It employs a variety of machine learning models—Linear Regression, K-Nearest Neighbors (KNN), XGBoost, Support Vector Regression (SVR), and Random Forest—to forecast cryptocurrency values. The models are evaluated using performance metrics like Mean Squared Error (MSE), R-squared (R²), and Mean Absolute Percentage Error (MAPE).

**Key Features:**
- **Data Preprocessing:** Effective handling of missing data, feature scaling, and the generation of relevant predictors to ensure accurate model training.
- **Models Implemented:**
  - Linear Regression
  - XGBoost (Extreme Gradient Boosting)
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Support Vector Regression (SVR)
- **Performance Metrics:**
  - Mean Squared Error (MSE)
  - R-squared (R²)
  - Mean Absolute Percentage Error (MAPE)

**Highlights:**
. **Linear Regression** was the top performer for predicting Bitcoin and Wrapped Bitcoin prices, achieving R² scores of 0.9823 and 0.9780, respectively.
. **XGBoost** achieved the best results for Monero predictions with the lowest MSE of 325.33, demonstrating its capability to capture price volatility.3.
. The repository provides full implementation, including data processing, feature selection, model training, and performance evaluation, making it useful for enhancing 
  cryptocurrency market analysis and improving investment strategies.

**Technologies Used:**
. Python
. Pandas for data handling
. Numpy for numerical computations
. Scikit-learn for model implementation and evaluation
. Matplotlib and Plotly for visualizations
. XGBoost for gradient boosting models
. Linear Regression
. Random Forest
. Support Vector Regression
. KNN

**Prerequisites:**
. Python version 3.7 or above
. pip for package management

**Future Scope:**  
Incorporating sentiment analysis and economic indicators to further improve the accuracy of predictions and enhance decision-making in cryptocurrency investments.
