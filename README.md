# Bank Stock Forecasting Project

## Overview

This project explores how different modeling approaches perform in forecasting stock prices of major U.S. banks.

We compare:

* Econometric models
* Machine learning algorithms
* Deep learning models

on financial time-series data enriched with macroeconomic indicators and sentiment signals.

---

## Key Highlights

* Multi-model comparison: ARIMAX, GARCH, LightGBM, LSTM
* Multi-source data: stock prices + macro + sentiment
* Time-series feature engineering (lag, volatility, returns)
* Real-world financial forecasting use case

---

## Dataset

The analysis focuses on:

* JPMorgan Chase (JPM)
* Bank of America (BAC)
* Wells Fargo (WFC)

📅 Time range: **2018 – 2025**

### Features

**Market Data**

* Open, High, Low, Close, Volume

**Macroeconomic Indicators**

* VIX
* S&P 500
* Federal Funds Rate

**Sentiment Data**

* News-based sentiment scores

---

## Data Processing

* Log returns calculation
* Rolling volatility estimation
* Lag feature creation
* Data alignment (macro + stock)
* Missing value handling
* Feature scaling

---

## Models Implemented

### Econometric Models

* ARIMAX
* SARIMAX
* GARCH(1,1)

### Machine Learning

* Logistic Regression
* SVM
* LightGBM

### Deep Learning

* GRU
* LSTM
* LSTM + Sentiment

---

## Evaluation Metrics

**Regression**

* RMSE
* MAE
* MAPE

**Classification**

* Accuracy
* Precision
* Recall
* F1-score

---

## Results & Visualization
### Example: Stock Price Prediction

![Stock Prediction](images/stock_prediction.png)

### Example: Model Comparison

![Model Comparison](images/model_comparison.png)

### Example: Feature Importance (SHAP)

![SHAP](images/shap_summary.png)

---

## Key Insights

* No single model dominates across all tasks
* Econometric models capture macro trends well
* ML models handle nonlinear relationships
* Deep learning models perform well for short-term prediction
* Sentiment impact depends heavily on data quality

---

## 🗂️ Project Structure

```
project/
│── data/
│── notebooks/
│── src/
│── models/
│── images/
│── README.md
```

---

## Installation

```bash
git clone https://github.com/vu-leonguyen/bank-stock-analysis-ml-dl.git
cd bank-stock-analysis-ml-dl
pip install -r requirements.txt
```

---

## Usage

```bash
python train.py
```

or open notebooks:

```bash
jupyter notebook
```

---

## Technologies Used

* Python
* Pandas, NumPy
* scikit-learn
* statsmodels
* LightGBM
* TensorFlow / Keras
* SHAP
* Matplotlib, Seaborn

---

## 👨‍💻 Author

Information Systems – University of Information Technology (UIT)

* Nguyễn Trường Vũ
* Phạm Hùng Quốc Việt
* Đặng Hữu Thọ
* Phạm Minh Ngân

Interests:

* Data Analytics
* Financial Data
* Machine Learning
* Big Data Systems
