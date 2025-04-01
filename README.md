# 🚦 Evaluating the 50c Fare Initiative: A Data Analysis of Gold Coast Transport Systems

## 🧠 Project Summary  
This project, in collaboration with the **City of Gold Coast**, analysed the impact of the Queensland Government’s **50c public transport fare initiative** on traffic congestion, delay hours, and public transport usage.

We worked with **IoT sensor data**, public transport datasets, and historical patterns across 2020–2024 to uncover behavioural shifts in travel. The results were presented to city stakeholders to inform future transport policy.

---

## 📊 Key Analyses  
- **Traffic Volume Trends** – Aggregated 70+ traffic datasets to compare 2023 and 2024 volumes before and after the 50c trial  
- **Delay Hour Forecasting** – Used **ARIMA** and **Linear Regression** to predict congestion trends through Dec 2024  
- **Public Transport Mode Shift** – Compared passenger counts across train, tram, and bus modes  
- **Weekday vs Weekend Behaviour** – Identified usage and congestion profile differences  
- **Geospatial Mapping** – Used **QGIS** to identify congestion hotspots and route-level shifts  

---

## 🧰 Tools & Technologies  
- **Languages:** Python, SQL  
- **Platforms:** Snowflake, Paws DBT (internal), Jupyter Notebook  
- **Visualisation:** Seaborn, Matplotlib, QGIS, Power BI (internal)  
- **Models:** Linear Regression, ARIMA  
- **Data Sources:** IoT traffic sensors, TransLink public transport feeds  

---

## 🧾 Deliverables  
- ✅ Python notebooks for volume, delay, and public transport analyses  
- ✅ Forecasting scripts and plots  
- ✅ QGIS files for geospatial visualisation  
- ✅ User manuals and client-facing documentation  

---

## 🔒 Note on Internal Tools  
Some analyses involving **Paws DBT** and **Power BI dashboards** were created for internal stakeholder use and are not included in the public repo due to data sharing restrictions.

---

## 📁 Repository Structure  
- `notebooks/` – Jupyter notebooks for volume, delay, and PT analysis  
- `qgis/` – Geospatial files for route- and suburb-level analysis  
- `docs/` – Final report, user guides, and supporting documentation  
- `datasets/` – Sample files only (primary datasets not included for confidentiality)  

---

## 🖼️ Visual Highlights  

### 📉 Traffic Delay Forecast (Aug–Dec 2024)  
![image](https://github.com/user-attachments/assets/33f366ca-ae90-44af-8463-3eafea0e918f)
*Overview of Morning Peak Time delay hours.*

![image](https://github.com/user-attachments/assets/f06d7fd0-f08a-4d67-b9fd-2ec49fac3181)
*Overview of Evening Peak Time delay hours.*

![image](https://github.com/user-attachments/assets/671c5446-4c9f-4a39-9d94-60bd0997cae3)
*Forecasted Morning Peak Time delay hours using ARIMA.*

![image](https://github.com/user-attachments/assets/090ea332-746b-4305-aaa2-43279e3f5ecd)
*Forecasted Evening Peak Time delay hours using ARIMA.*

### 🧭 Geospatial Heatmap of Congestion Hotspots  
![image](https://github.com/user-attachments/assets/811f2a0d-74ec-4e35-92da-58b285bd10e6) 

*Congestion clusters mapped across Gold Coast suburbs using QGIS.*

### 🚆 Public Transport Mode Shift Comparison  
![image](https://github.com/user-attachments/assets/53ba7c6d-f79c-48be-8455-ffd144a3a6ab)

*Monthly usage trends (2023 vs 2024) across light rail, train, and bus services.*

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
