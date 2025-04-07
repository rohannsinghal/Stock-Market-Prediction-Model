# Stock-Market-Prediction-Model

## 📈 Project Overview
This project focuses on predicting the *Close* price of multiple stocks for the years 2023-2024 using historical stock market data from 2018-2022. The dataset provided included the following parameters for each stock:
- Open
- High
- Low
- Close
- Volume

The objective was to build an LSTM-based time series prediction model that forecasts the *Close* price accurately.

---

## 🔥 Key Features
- Data Preprocessing:
  - Excel to CSV conversion
  - Feature engineering (SMA, EMA, Rolling Mean, Lag Features)
  
- LSTM Model:
  - Trained separate models for each stock
  - Special handling for Stock `N` (limited data points)
  
- Prediction & Output:
  - Generated predictions for 2023-2024
  - Final combined submission-ready spreadsheet for all stocks

- Achieved a very low validation loss of: 0.00017
- ---

## 🛠️ Tech Stack
- Python  
- Pandas & NumPy (Data Handling)  
- TensorFlow / Keras (Model Building)  
- Matplotlib / Seaborn (Visualization)  
- Jupyter Notebook / Colab  

---
## 🚀 Installation Guide

### 1. Clone the Repository
```bash
git clone https://github.com/rohannsinghal/Stock-Market-Prediction-Model.git
