# 🌤️ Glassmorphism Weather Forecast App

A sleek, modern, and high-performance Weather Forecast Dashboard built using **Streamlit**, **Python**, and **Machine Learning (Random Forest)**. This application fetches live weather analytics from the OpenWeatherMap API and uses historical data to predict future hourly trends with interactive visual elements.

## ✨ Features
* **Live Weather Data:** Fetches real-time temperature, feels-like temperature, humidity, wind speed, pressure, and cloudiness.
* **Predictive Insights:** Uses a trained `RandomForestRegressor` model to forecast future temperature and humidity levels for the upcoming hours.
* **Premium Glassmorphism UI:** Features a gorgeous dark-theme responsive UI with semi-transparent frosted glass containers and customized layout.
* **Secure API Integration:** Implements Streamlit Secrets management to safeguard API keys against public repository leaks.

## 🛠️ Tech Stack
* **Frontend UI:** Streamlit, HTML5, Custom CSS3
* **Backend Logic:** Python 3
* **Data & Analytics:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest Regressor)
* **API Integration:** OpenWeatherMap API, Requests

## 🚀 Getting Started

Follow these steps to run the project locally on your machine:

### 1. Prerequisites
Make sure you have Python installed, along with the required libraries:
```bash
pip install streamlit requests pandas numpy scikit-learn pytz
