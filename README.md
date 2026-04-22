# 📊 Time Series Forecasting using Custom RNN

This project implements a time-series forecasting pipeline with a **Custom RNN built from scratch**, along with comparisons to MLP, LSTM, and Transformer models.

---

## 🎯 Overview

- Converts raw time-series data into input-output windows  
- Trains models to predict future values from past observations  
- Evaluates performance using MSE, MAE, RMSE  
- Includes ablation study on window size  

---

## 📂 Datasets

Two datasets are used to test model performance and generalization:

- **Electric Production Dataset**  
  Monthly electricity production data with real-world trends and variations  

- **Airline Passengers Dataset**  
  Time-series data with clear trend and seasonal patterns  

---

## ⚙️ Models

- MLP (baseline, no sequence awareness)  
- Custom RNN (implemented from scratch)  
- LSTM (prebuilt)  
- Transformer (prebuilt)  

---

## 📈 Evaluation

- Chronological train-test split  
- Metrics: MSE, MAE, RMSE  
- Prediction vs actual plots  

---

## 🔬 Ablation Study

Effect of window size:
- Smaller window → less context  
- Larger window → more noise  

---

## 🧠 Key Insight

Sequence models (RNN, LSTM, Transformer) perform better than MLP as they capture temporal dependencies in the data.

---
