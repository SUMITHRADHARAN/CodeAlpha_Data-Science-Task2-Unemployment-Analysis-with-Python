# CodeAlpha_Data-Science-Task2-Unemployment-Analysis-with-Python
This project analyzes unemployment trends in India, focusing on: - Regional &amp; seasonal patterns - Impact of COVID-19 - Forecasting unemployment using ARIMA

## 📌 Project Overview
This project analyzes unemployment rate data using Python. It focuses on data cleaning, visualization, Covid-19 impact analysis, and seasonal trend identification.

This project analyzes unemployment trends in India, focusing on:
- Regional & seasonal patterns
- Impact of COVID-19
- Forecasting unemployment using ARIMA

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Highlights
- Unemployment trend analysis over time
- Impact of Covid-19 on employment
- Seasonal and regional unemployment patterns

## Dataset
Unemployment data containing region-wise monthly statistics.

Dataset includes unemployment rates, labor participation, and employment across states.

---

## 🛠️ Steps Performed
1. **Data Cleaning & Preprocessing**
   - Converted dates to `datetime`
   - Extracted months for seasonality analysis

2. **Exploratory Data Analysis**
   - Heatmaps of unemployment across states & months
   - Trend lines to observe patterns

3. **COVID-19 Impact Analysis**
   - Sharp spikes observed in April–May 2020
   - Urban vs rural differences studied

4. **Forecasting**
   - ARIMA model used to predict next 6 months
   - Forecast summary prepared per region

5. **Insights**
   - Northern states show higher volatility
   - Southern states are more stable
   - Policy recommendations provided

---

## 📊 Results
- Bihar, Haryana, Rajasthan had the **highest spikes**.
- Andhra Pradesh, Chhattisgarh remained **stable**.
- COVID lockdown in **2020** caused unemployment to rise sharply everywhere.
- Forecast indicates gradual recovery but persistent unemployment in some states.

---

## 🚀 How to Run
```bash
# Clone repo
git clone <your-repo-url>
cd unemployment-analysis

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook
