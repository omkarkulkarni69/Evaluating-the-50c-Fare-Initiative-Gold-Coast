# 📊 Analyses at a Glance

This document summarises all the key analyses conducted in this project, categorised into three main themes. The goal was to understand how the Queensland Government's 50c Fare Initiative affected public transport usage and road traffic patterns in the Gold Coast region.

---

## 1. 🚉 Public Transport Analysis

**Objective:** Understand how the 50c fare impacted ridership patterns (daily, monthly, mode-wise, weekday/weekend)

### Analyses Performed:
- 📈 **Trend Analysis (Jan 2022 – Aug 2024)**: Identified monthly fluctuations and peaks
- 📊 **Year-over-Year (YoY) % Change**: Compared same months across years for buses, rail, and light rail
- 📆 **Weekend vs Weekday Comparison**: Found significant differences in ridership behavior
- 🔮 **Forecasting (Aug–Dec 2024)**:
  - Linear Regression for weekday and weekend trips
  - ARIMA model for more robust weekday trip forecasting

📌 **Key Insight:** August 2024 saw the highest increase in public transport usage, indicating a successful early outcome of the fare trial&#8203;:contentReference[oaicite:0]{index=0}.

---

## 2. ⏱️ Delay Hours Analysis

**Objective:** Examine whether road congestion improved due to increased public transport use

### Analyses Performed:
- 📅 **Monthly Delay Trends (Jun–Sep)**: Compared 2023 vs 2024
- 🕒 **Hourly Delay by Time of Day**: Categorized into 7 daily intervals (e.g. Morning Peak, Evening Peak)
- 📈 **Linear Regression**:
  - Morning Peak (8–10 AM)
  - Evening Peak (3–6 PM)
- 📉 **ARIMA Prediction**:
  - Morning Peak and Evening Peak delay forecasting

📌 **Key Insight:** Both morning and evening delays decreased after August 6, 2024. The trend continued steadily through September, suggesting improved traffic flow and reduced congestion&#8203;:contentReference[oaicite:1]{index=1}.

---

## 3. 🚗 Traffic Volume Analysis

**Objective:** Determine whether private vehicle usage dropped post-trial

### Analyses Performed:
- 📊 **Volume Comparison (2023 vs 2024)** for July–September
- 📅 **Weekday vs Weekend Volume Shifts**: Aggregated across common detector sites
- 🌐 **Geospatial Visualisation using QGIS**:
  - Volume changes mapped to specific suburbs/links
- 📈 **Percentage Change Metrics** between matched months

📌 **Key Insight:** Weekday traffic volumes dropped by 2–4% in August 2024 vs August 2023, indicating a probable mode shift to public transport&#8203;:contentReference[oaicite:2]{index=2}.

---

## 🔍 Summary of Methodologies Used

- **Data Cleaning & Aggregation** in Python (pandas)
- **Visualisation** using Matplotlib, Seaborn, and QGIS
- **Predictive Models**:
  - Simple Linear Regression
  - ARIMA (AutoRegressive Integrated Moving Average)

⚠️ Snowflake tables and raw queries have **not** been included in this repository due to IP agreements with the City of Gold Coast.

---

✅ For details on how to replicate the notebooks, refer to `/notebooks/` and `/readme/`.
