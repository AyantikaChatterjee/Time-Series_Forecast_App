# 📊 Hotel Bookings Time Series Forecasting

An interactive web application to forecast monthly hotel bookings using historical data and advanced time series models. Built with Python and Streamlit, the app helps users visualize trends, apply decomposition, and compare models like ARIMA, ETS, Prophet, and LSTM.

---

## 🚀 Project Overview

Forecasting hotel bookings is critical for improving staffing, marketing, and inventory decisions. This project implements a full forecasting pipeline and deploys it in an easy-to-use Streamlit app.

---

## 🔧 Features

- Upload your own time series CSV file
- Auto-clean and resample data to monthly frequency
- Visualize trends, seasonality, and residuals using additive/multiplicative decomposition
- Choose from 4 forecasting models:
  - ARIMA
  - ETS (Exponential Smoothing)
  - Prophet (Facebook)
  - LSTM (Deep Learning)
- Set forecast horizon (6–36 months)
- View forecast results with metrics:
  - RMSE
  - MAE
  - MAPE
  - MSE

---

## 🧠 Models Compared

| Model     | Description                          |
|-----------|--------------------------------------|
| ARIMA     | Classical linear forecasting         |
| ETS       | Trend & seasonal exponential smoothing |
| Prophet   | Handles seasonality & changepoints   |
| LSTM      | Neural network for complex patterns  |

---

## 📁 Files Included

- `App.py` – Streamlit app code
- `hotel_bookings.csv` – Raw dataset
- `cleaned_timeseries.csv` – Aggregated monthly data
- `hotel_bookings.ipynb` – Notebook for model development
- `Report_Group3_HotelBookings.docx` – Final report
- `Group3_ML2_Presentation.pptx` – Slides

---

## ▶️ Deployment

This app is live on **Streamlit Cloud**

🔗 [Click here to view the deployed app](https://python-eyvn5awzbjn3zmbdcbmzac.streamlit.app)
