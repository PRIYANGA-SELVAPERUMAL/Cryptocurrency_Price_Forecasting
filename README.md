
# 📈 Cryptocurrency Price Forecasting using Machine Learning

A comprehensive machine learning workflow that predicts future prices of leading cryptocurrencies—Bitcoin (BTC), Ethereum (ETH), Wrapped Bitcoin (WBTC), and Monero (XMR)—using historical price data. The project encompasses data preprocessing, model training, evaluation, and visualization to assist investors and analysts in making informed decisions.

---

## 📌 Table of Contents

* [About the Project](#about-the-project)
* [Dataset](#dataset)
* [Problem Statement](#problem-statement)
* [Methodology](#methodology)
* [Models Implemented](#models-implemented)
* [Performance Metrics](#performance-metrics)
* [Results](#results)
* [Tech Stack](#tech-stack)
* [How to Run the Project](#how-to-run-the-project)
* [Future Enhancements](#future-enhancements)
---

<a name="about-the-project"></a>
## 📖 About the Project

Cryptocurrencies exhibit high volatility, making price prediction a challenging task. This project leverages various machine learning algorithms to forecast the prices of BTC, ETH, WBTC, and XMR. By analyzing historical price data, the models aim to capture patterns and trends to predict future prices accurately.

---

<a name="dataset"></a>
## 🗂 Dataset

* **Source**: [Dataset.zip](Dataset.zip)
* **Contents**: Historical price data for BTC, ETH, WBTC, and XMR

| **Attribute**  | **Description**                              |
| -------------- | -------------------------------------------- |
| Cryptocurrency | 23 types including Bitcoin, Ethereum, Ripple |
| Date           | Date of observation                          |
| Open           | Opening price of the day                     |
| High           | Highest price of the day                     |
| Low            | Lowest price of the day                      |
| Close          | Closing price of the day                     |
| Volume         | Daily transaction volume                     |
| Market Cap     | Market capitalization in USD                 |
| Time Period    | April 2013 – July 2021                       |


---

<a name="problem-statement"></a>
## ❓ Problem Statement

Develop machine learning models that can accurately predict the future prices of selected cryptocurrencies based on historical data, aiding investors in making data-driven decisions.

---

<a name="methodology"></a>
## 🔍 Methodology

### Data Preprocessing:

* Handling missing values
* Feature scaling using Min-Max normalization
* Generating relevant predictors (e.g., moving averages, price differentials)

### Model Training & Evaluation:

* Splitting data into training and testing sets
* Training multiple regression models
* Evaluating models using MSE, R², and MAPE

---

<a name="models-implemented"></a>
## 🤖 Models Implemented

* Linear Regression
* K-Nearest Neighbors (KNN)
* XGBoost (Extreme Gradient Boosting)
* Support Vector Regression (SVR)
* Random Forest Regressor

---

<a name="performance-metrics"></a>
## 📏 Performance Metrics

* **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual values.
* **R-squared (R²)**: Indicates the proportion of variance in the dependent variable predictable from the independent variables.
* **Mean Absolute Percentage Error (MAPE)**: Expresses accuracy as a percentage.

---

<a name="results"></a>
## ✅ Results

| Cryptocurrency      | Model             | MSE            | R² Score | MAPE    |
| ------------------- | ----------------- | -------------- | -------- | ------- |
| **Monero**          | Linear Regression | 326.03         | 0.9578   | 114.80% |
|                     | KNN               | 350.21         | 0.9547   | 11.62%  |
|                     | XGBoost           | 325.33         | 0.9579   | 21.92%  |
|                     | SVR               | 496.20         | 0.9358   | 12.02%  |
|                     | Random Forest     | 329.75         | 0.9573   | 12.62%  |
| **Ethereum**        | Linear Regression | 6663.21        | 0.9824   | 113.04% |
|                     | KNN               | 316326.55      | 0.1646   | 21.04%  |
|                     | XGBoost           | 312335.10      | 0.1751   | 21.58%  |
|                     | SVR               | 394334.81      | -0.0414  | 25.96%  |
|                     | Random Forest     | 311287.01      | 0.1779   | 22.10%  |
| **Wrapped Bitcoin** | Linear Regression | 5,752,449.84   | 0.9780   | 7.39%   |
|                     | KNN               | 520,365,880.81 | -0.9857  | 95.81%  |
|                     | XGBoost           | 520,031,010.13 | -0.9844  | 95.70%  |
|                     | SVR               | 526,294,086.96 | -1.0083  | 97.77%  |
|                     | Random Forest     | 519,927,745.65 | -0.9840  | 95.67%  |
| **Bitcoin**         | Linear Regression | 1,506,676.98   | 0.9823   | 12.33%  |
|                     | KNN               | 114,665,355.10 | -0.3468  | 59.50%  |
|                     | XGBoost           | 114,551,786.04 | -0.3454  | 59.13%  |
|                     | SVR               | 116,692,957.95 | -0.3706  | 68.81%  |
|                     | Random Forest     | 114,516,856.63 | -0.3450  | 59.50%  |


---

<a name="tech-stack"></a>
## 🛠️ Tech Stack

* **Programming Language**: Python
* **Data Handling**: Pandas, NumPy
* **Modeling & Evaluation**: Scikit-learn, XGBoost
* **Visualization**: Matplotlib, Plotly([arxiv.org][8])

---

<a name="how-to-run-the-project"></a>
## ⚙️ How to Run the Project

1. **Clone the repository**:

   ```bash
   git clone https://github.com/PRIYANGA-SELVAPERUMAL/Cryptocurrency_Price_Forecasting.git
   cd Cryptocurrency_Price_Forecasting
   ```



2. **Create and activate a virtual environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```



3. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```



4. **Run the Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```



Open `cryptocurrency_price_forecasting.ipynb` and execute the cells sequentially.

---

<a name="future-enhancements"></a>
## 🔭 Future Enhancements

* Integrate sentiment analysis from social media and news sources to capture market sentiment.
* Incorporate macroeconomic indicators to enhance prediction accuracy.
* Develop a web application for real-time price prediction and visualization.
* Explore deep learning models like LSTM and GRU for capturing temporal dependencies.([arxiv.org][9], [github.com][10])

## 📄 Published Paper

🔗 [IEEE Xplore: Cryptocurrency Price Forecasting using ML Models](https://doi.org/10.1109/ICIETDW61607.2024.10941381)



