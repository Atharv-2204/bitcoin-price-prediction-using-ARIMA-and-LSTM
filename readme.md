# Bitcoin Price Prediction using ARIMA and LSTM

A research-oriented forecasting framework for analyzing and predicting Bitcoin price movements using **Statistical Modeling Autoregressive Integrated Moving Average (ARIMA)** and **Deep Learning Long Short-term Memory (LSTM)**.
The system compares model performance and evaluates their suitability for different time-series data characteristics.

---

## Project Overview

This project presents a comparative research study between **classical time-series forecasting and modern deep learning approaches** for cryptocurrency price prediction.  
It integrates statistical analysis with neural network modeling to evaluate how different techniques perform on Bitcoin price data under varying assumptions such as stationarity and non-linearity.
The system is implemented in **Python using Jupyter Notebook** for transparency, experimentation, and reproducibility..

### Key Objectives
- Forecast Bitcoin prices using ARIMA and LSTM models
- Compare statistical and deep learning approaches for time-series prediction
- Evaluate model accuracy and forecasting behavior
- Identify conditions where traditional models outperform neural networks
- Maintain research clarity, reproducibility, and performance transparency

---

## System Architecture

The framework consists of two primary forecasting modules:
1. **ARIMA Forecasting Module (Statistical Model)**
   - Performs time-series stationarity checks
   - Applies differencing and parameter tuning
   - Builds ARIMA(p, d, q) model
   - Generates future Bitcoin price forecasts
   - Evaluates performance using error metrics

2. **LSTM Forecasting Module (Deep Learning Model)**
   - Normalizes and sequences time-series data
   - Builds a Long Short-Term Memory neural network
   - Learns temporal dependencies in Bitcoin price movements
   - Generates multi-step forecasts
   - Evaluates performance against actual prices

---

## Technologies Used

### Programming & Libraries
- **Python** 3.x
- **Pandas, NumPy** – Data preprocessing and numerical operations
- **Matplotlib / Seaborn** – Data visualization
- **Statsmodels** – ARIMA implementation
- **TensorFlow / Keras** – LSTM neural network modeling

### Tools & Environment
- **Jupyter Notebook** – Experimentation & reproducibility
- **Git & GitHub** – Version control

---

## Time-Series Modeling Details

### 1.ARIMA Model
- **Type**: Statistical Forecasting Model
- **Best For**: Stationary data with structured patterns
- **Strengths**:
  - Interpretable parameters
  - Effective for linear trends and seasonality
  - Lower computational cost
- **Limitations**:
  - Struggles with nonlinear patterns
  - Sensitive to sudden market shocks and outliers

### 2.LSTM Model
- **Type**: Deep Learning Sequential Model
- **Best For**: Complex, nonlinear, and non-stationary data
- **Strengths**:
  - Learns long-term temporal dependencies
  - Handles nonlinear patterns effectively
  - Minimal manual feature engineering
- **Limitations**:
  - Computationally intensive
  - Requires careful tuning and regularization
  - Less interpretable than statistical models

### Evaluation Metrics:
- Both models were evaluated using standard regression error metrics:
    - Mean Absolute Error (MAE)
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
    - Mean Absolute Percentage Error (MAPE)
- Performance comparison was conducted between predicted and actual Bitcoin prices.

---

## Model Comparison Findings

- The dataset used in this project was relatively clean and stationary
- Under these conditions, ARIMA achieved higher forecasting accuracy than LSTM
- This demonstrates that model effectiveness depends on data characteristics, not just model complexity
There is no universally superior model the best choice depends on the structure and behavior of the time-series data.

---

## Project Structure

```text
bitcoin-price-prediction/
│
├── notebooks/
│   └── ARIMA.ipynb
│   └── LSTM.ipynb
│
├── README.md
├── requirements.txt
├── .gitignore
