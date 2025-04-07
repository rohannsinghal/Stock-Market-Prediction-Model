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
- TensorFlow (Model Building)  
- Matplotlib (Visualization)  
- Jupyter Notebook 

---
## 🔧 Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/rohannsinghal/Stock-Market-Prediction-Model.git
cd Stock-Market-Prediction-Model
```
2. Create Virtual Environment:
```bash
conda create -n stock-pred python=3.9
conda activate stock-pred
```
3. Install Dependencies:
```bash
pip install -r requirements.txt
```
---

## 💡 Usage

1. To explore data & train models:
Go to notebooks/ → Run .ipynb files

2. To check results:
Go to results/ → Visuals & Graphs

3. To see final predictions:
Check submission/ folder

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📞 Contact Me
GitHub: rohannsinghal

LinkedIn: https://www.linkedin.com/in/rohan-singhal-6776271bb/

Email: singhalrohan04@gmail.com
