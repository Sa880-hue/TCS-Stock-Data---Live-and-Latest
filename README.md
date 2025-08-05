# TCS Stock Data – Live and Latest

This project focuses on end-to-end analysis and forecasting of TCS (Tata Consultancy Services) stock data using Machine Learning and Excel Dashboards. The goal is to perform data cleaning, feature engineering, visualization, and predictive modeling (Linear Regression and LSTM) to extract insights and forecast stock prices.

---

## Project Overview

- **Domain**: Data Analytics / Finance  
- **Tools Used**: Google Colab, Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow, Keras, Excel  
- **Difficulty**: Advanced  
- **Languages**: Python, SQL (optional), Excel  

---

## Project Pipeline (Phases)

| Phase | Description |
|-------|-------------|
| Phase 1 | Data Collection & Loading (3 CSVs for TCS stock) |
| Phase 2 | Data Cleaning & Preprocessing |
| Phase 3 | Exploratory Data Analysis |
| Phase 4 | Feature Engineering |
| Phase 5 | Predictive Modeling (Linear Regression & LSTM) |
| Phase 6 | Model Saving & Excel Export |
| Phase 7 | Interactive Excel Dashboard |

---

## Machine Learning Models

### Linear Regression
- **Goal**: Predict the Close price based on historical data and engineered features.
- **Metrics**: MAE, RMSE, R²

### LSTM (Long Short-Term Memory)
- **Goal**: Time-series based prediction of stock Close price.
- **Model Structure**: 2 LSTM layers + 1 Dense layer
- **Loss**: Mean Squared Error
- **Metrics**: MAE, RMSE

---

## Excel Dashboard

An interactive Excel Dashboard was created with slicers and charts to allow filtering by **Year** and **Month**. Key components:
- Total Trading Days
- Highest/Lowest Close Prices
- Average Daily % Change
- Line Chart with Moving Averages (Close, MA7, MA21)
- Histogram of Daily % Change
- Trading Volume (Bar Chart)

---


## Conclusion

This project showcases a complete pipeline from raw data to model deployment and dashboarding. It integrates data science techniques with business reporting using Excel, making it both technically rich and user-friendly for decision-making.

---

