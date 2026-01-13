# Crime Time Series Forecasting 

This repository contains the development of a Data Science project focused on extracting, analyzing, and predicting brazilian crime data. The primary goal is to identify historical patterns and forecast future trends using time series modeling.

---

## 📌 Project Structure

The project is organized into three main notebooks, following a standard data pipeline:

### 1. [Scraping.ipynb](./Scraping.ipynb)
Handles automated data collection from the official Government portal.
* **Data Coverage:** Full historical records from 2015 to 2025.
* **Features:** Web scraping routines that manage downloads and initial data ingestion.

### 2. [Exploratory.ipynb](./Exploratory.ipynb)
*Status: Under Construction*
Dedicated to data understanding and hypothesis generation.
* Time series decomposition (trend and seasonality).
* Identification of outliers and critical time windows.
* Visual exploration of crime distributions over time.

### 3. [Forecasting.ipynb](./Forecasting.ipynb)
Development and validation of mathematical models for prediction.
* **Implemented Model:** Holt-Winters (Triple Exponential Smoothing).
* **Approach:** One-step-ahead forecasting to validate model accuracy against recent data.
* **Goal:** To establish a baseline for future comparisons with more complex models (e.g., SARIMA, Prophet).

---

## 🛠️ Tech Stack

* **Language:** Python 
* **Web Scraping:** `BeautifulSoup`, `Selenium`, or `Requests`
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Statistical Modeling:** `Statsmodels`

---

## 📈 Methodology

The current model utilizes the **Holt-Winters** method, which is effective for series showing both trend and seasonality. It calculates forecasts based on three essential components:

1.  **Level ($L_t$):** The smoothed average of the series.
2.  **Trend ($b_t$):** The growth or decline over time.
3.  **Seasonality ($s_t$):** Periodic fluctuations occurring at fixed intervals.

---

## ✒️ Author

* Rodrigo Caland
