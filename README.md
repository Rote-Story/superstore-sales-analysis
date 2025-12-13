# Sales Performance Dashboard with Regional Filters and Time Series Forecasting

An interactive sales analytics dashboard built in Google Sheets using historical Superstore sales data. 
This project analyzes sales performance across regions, states, customer segments, and product categories, and includes a forward-looking time-series sales forecast.

---

## 🔗 Live Dashboard
[View the interactive dashboard in Google Sheets](https://docs.google.com/spreadsheets/d/1DE3KF34I9PIPSfMDHr4_zBekXn7rN9u-nk1KAYc3PLs/edit?usp=sharing)

> Note: Dashboard is view-only. Use the Region and State slicers to explore the data.

---

## 📊 Dashboard Preview

![Sales Performance Dashboard](images/dashboard_overview.png)

---

## 🎯 Project Objective

The goal of this project is to:
- Analyze historical retail sales performance
- Identify trends across geography, customer segments, and product categories
- Provide a clean, executive-style dashboard with interactive filters
- Generate a monthly time-series forecast to support forward-looking analysis

---

## 🗂️ Data Source

- **Dataset:** Superstore Sales Dataset 
- **Platform:** Kaggle 
- **Link:** https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting 
- **Time Range:** 2014–2017 
- **Granularity:** Order-line level transactional data 

---

## 🛠️ Tools & Skills Demonstrated

- Google Sheets
- Data cleaning and preparation
- Feature engineering (time-based features, KPIs)
- Pivot tables and slicers
- Dashboard design and layout
- Time-series aggregation and forecasting
- Data modeling across multiple levels of granularity

---

## 🔧 Data Preparation & Feature Engineering

Key preparation steps include:
- Cleaning and standardizing raw transactional data
- Creating time-based features (Year, Month, Year-Month)
- Building a centralized analytics table to support dashboard slicers
- Calculating key metrics such as:
  - Total Sales
  - Average Order Value (AOV)
  - Total Customers
  - Year-over-Year (YoY) Sales Growth

---

## 📈 Forecasting Approach

- Sales data was aggregated at a **monthly level** to generate a time-series forecast
- Forecast values were joined back to transactional data using a **Year–Month key**
- This approach allows forecast visuals to remain responsive to dashboard slicers while preserving the original transaction-level data

---

## 📌 Dashboard Features

- **KPI Scorecards:** Total Sales, Average Order Value, Total Customers, YoY Sales Growth
- **Trend Analysis:** Monthly sales performance over time
- **Forecasting:** Actual vs. forecasted monthly sales
- **Segmentation:** Sales by customer segment and product category
- **Interactivity:** Global Region and State slicers affecting all visuals

---

## ⚠️ Assumptions & Limitations

- Forecasts are based solely on historical sales trends and do not account for external factors
- Profitability analysis is excluded due to limited cost information in the dataset
- Customer behavior is inferred from transactional data only

---

## 🔮 Potential Improvements

- Implement more advanced forecasting methods
- Add profitability analysis if cost data becomes available
- Expand customer behavior metrics (e.g., repeat purchase analysis)

---

## 📎 Notes

This project was created as part of a personal data analytics portfolio to demonstrate end-to-end analysis, dashboard design, and data modeling skills using Google Sheets.

