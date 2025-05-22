# Time-series-analysis-and-forcasting
Time series analysis and forcasting : Tesla stock price Prediction using ARIMA / SARIMA model . 
# 📈 Time Series Analysis & Forecasting: Tesla Stock Price Prediction

A data science project focused on forecasting Tesla's stock prices using ARIMA and SARIMA models. This project includes time series analysis, model building, evaluation, and forecasting using historical stock price data.

---

## 🧠 Project Objective

To analyze Tesla's historical stock prices, identify underlying trends and seasonality, and build accurate forecasting models using ARIMA and SARIMA techniques.

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib / Seaborn
- Statsmodels
- pmdarima
- yfinance (for data collection)

---

## 📊 Key Steps in the Project

### 1. **Data Collection**
- Fetched historical Tesla stock data using `yfinance`.

### 2. **Exploratory Data Analysis**
- Visualized time series components (trend, seasonality, noise).
- Analyzed rolling statistics and decomposed the series.

### 3. **Stationarity Checks**
- Used Augmented Dickey-Fuller (ADF) test to confirm stationarity.
- Differencing applied to stabilize mean and remove trends.

### 4. **Modeling**
- Implemented ARIMA using `auto_arima` for parameter selection.
- Built SARIMA models to incorporate seasonality.
- Compared models using AIC, BIC, and residual diagnostics.

### 5. **Forecasting**
- Generated future price predictions.
- Visualized forecast vs actual values with confidence intervals.

### 6. **Model Evaluation**
- Evaluated model accuracy using RMSE, MAE, and visual inspection of residuals.

---

## 📁 Project Structure

```
Tesla-Stock-Forecasting/
│
├── Tesla_Stock_ARIMA_SARIMA.ipynb   # Main Jupyter Notebook
├── data/
│   └── tesla_stock.csv              # Optional: locally saved data
├── plots/                           # Saved visualization outputs (optional)
└── README.md                        # Project documentation
```

---

## 📌 Dataset Source

- [Yahoo Finance - Tesla (TSLA)](https://finance.yahoo.com/quote/TSLA)

---

## 📈 Sample Visualizations

- Time series line plot of TSLA stock
- ACF and PACF plots
- Forecast vs Actual comparison chart
- Residual plots to check model assumptions

---

## 🧠 Skills Applied

- Time Series Analysis
- Statistical Modeling
- Forecasting Techniques
- ARIMA & SARIMA Modeling
- Data Visualization
- Python for Financial Data Analysis

---

## ✅ Conclusion

Successfully modeled and forecasted Tesla stock prices using ARIMA and SARIMA, demonstrating strong understanding of time series forecasting techniques. The project highlights data preprocessing, statistical testing, and predictive analytics.

---

## 📜 License

This project is licensed under the MIT License.

