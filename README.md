**Evaluating the 50c Fare Initiative: A Data Analysis of Gold Coast Transport Systems**

This project analyzes the impact of the Queensland Government’s 50-cent public transport fare initiative, introduced on August 6, 2024. The aim is to evaluate whether this initiative influenced traffic congestion, delay hours, and public transport usage in the City of Gold Coast.

---

## 🔍 Analyses at a Glance

This study is grouped into three major themes: public transport usage, traffic delays, and volume changes.

### 🚉 Public Transport Analysis
- Passenger trends from 2022 to 2024 (monthly, weekday vs weekend)
- Mode-by-mode analysis (Bus, Rail, Light Rail)
- Forecasts using Linear Regression and ARIMA

### ⏱️ Delay Hours Analysis
- Delay comparison between 2023 and 2024
- Segmentation by 7 time periods (e.g., Morning Peak, Evening Peak)
- Predictive analysis using Linear Regression and ARIMA

### 🚗 Traffic Volume Analysis
- Aggregated vehicle volume comparison (Jul–Sep 2023 vs 2024)
- Weekday vs weekend differences
- Geospatial visualisation using QGIS

📌 Data has been cleaned, aggregated, and anonymised to ensure privacy and compliance with IP agreements.

---

## 📁 Repository Structure

- `/notebooks`: Jupyter notebooks with delay hours and public transport analysis  
- `/data`: Cleaned datasets (anonymised, no raw Snowflake data)  
- `/qgis`: QGIS project files for link-level visualisation  
- `/docs`: Proposal, user manuals, final report, and presentation (no confidential material)  
- `/readme`: Notebook-specific markdown guides  
- `README.md`: Project overview (this file)  
- `.gitignore`: Files/folders excluded from Git version control  
- `LICENSE`: MIT License

⚠️ SQL queries, Snowflake tables, and raw datasets from the City of Gold Coast are **not included** due to IP protection.  
⚠️ Confidential agreements and communications are also excluded from this repository.

---

## 🛠️ Tech Stack

- **Python 3.7+**  
  - pandas, matplotlib, seaborn  
  - scikit-learn (for linear regression)  
  - statsmodels (for ARIMA)  
- **Jupyter Notebooks**  
- **QGIS** for spatial visualisation

---

## 📊 Key Deliverables

- 📈 Public transport usage trends (2022–2024)
- ⏱️ Delay analysis by time category and month
- 🚗 Traffic volume trends and link-level maps
- 🔮 Forecast models (Linear Regression, ARIMA) for delay and ridership

---

## 👥 Team Members

- Omkar Kulkarni  
- Vishal Kumar  
- Viet An Nguyen  
- Zhanrui Liao  

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgements

Special thanks to:
- City of Gold Coast (Client: Phillip Karfs)  
- Griffith University  
- Professor Elizabeth Chang (Supervisor)

---
