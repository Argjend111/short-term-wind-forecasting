# 🌬️ Wind Power Forecasting – Kosovo

A research-oriented machine learning pipeline for **short-term wind power forecasting** using hybrid models (LSTM, Transformer, SARIMA, Prophet) and ensemble techniques.

---

## 📌 Project Overview

This project aims to improve **grid stability and energy efficiency** by accurately forecasting wind power generation.

It combines:

* Deep Learning (LSTM, Transformer)
* Statistical Models (SARIMA, Prophet)
* STL Decomposition
* Ensemble Learning

---

## ⚙️ Features

* 📊 Time-series preprocessing (cleaning, resampling)
* 🔧 Feature engineering (lags, rolling stats, weather data)
* 🔍 STL decomposition (trend, seasonality, residual)
* 🤖 Multiple models:

  * LSTM
  * Transformer (iTransformer)
  * SARIMA
  * Prophet
* 🧠 Hyperparameter tuning (PSO / GA)
* 🔗 Ensemble methods (weighted average, stacking)
* 📈 Evaluation metrics (RMSE, MAE, MAPE)

---

## 📁 Project Structure

```
wind-forecasting/
│
├── data/              # Raw & processed datasets
├── notebooks/         # EDA and experiments
├── src/               # Core code
├── configs/           # Hyperparameters
├── results/           # Outputs & metrics
└── README.md
```

---

## 🚀 Installation

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the full pipeline:

```bash
python src/training.py
```

Evaluate models:

```bash
python src/evaluation.py
```

---

## 📊 Models Used

| Model       | Type          | Purpose                     |
| ----------- | ------------- | --------------------------- |
| LSTM        | Deep Learning | Capture sequential patterns |
| Transformer | Deep Learning | Long-range dependencies     |
| SARIMA      | Statistical   | Seasonal baseline           |
| Prophet     | Statistical   | Trend + seasonality         |

---

## 📈 Evaluation Metrics

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* MAPE (Mean Absolute Percentage Error)

---

## 🧪 Experiments

* STL vs No STL
* LSTM vs Transformer
* With vs Without weather features
* Ensemble vs single models

---

## 📦 Requirements

* Python 3.9+
* PyTorch / TensorFlow
* pandas, numpy
* scikit-learn
* statsmodels
* prophet
* pyswarms

---

## ⚠️ Limitations

* Limited data availability for Kosovo
* Sensitivity to extreme weather events
* High computational cost for deep models

---

## 📅 Future Work

* Add real-time forecasting
* Improve uncertainty estimation
* Deploy as API / dashboard

---

## 👤 Author

Argjend Bytyçi

---

## 📜 License

This project is for academic/research purposes.
