# Malaysia Public Transport Ridership - Descriptive Analysis

This project performs descriptive analysis on Malaysia's public transport ridership dataset using Python and Business Intelligence tools. The focus is on understanding past trends and summarizing ridership behavior across MRT, LRT, Monorail, Bus, and National Rail services from 2019–2025. Insights discovered help inform better transport policy planning and public service improvements.

---

## 📊 Dataset Overview

- **Source**: [[Custom ridership dataset of Malaysia’s public transport](https://data.gov.my/data-catalogue/ridership_headline)]
- **Time Span**: 2019 – 2025
- **Features**:
  - Daily ridership for MRT, LRT, Monorail, Buses, and National Rails
  - Date column, monthly trends
  - Urban vs regional transport modes

---

## 🧹 Data Preparation

- Converted date to `datetime` format
- Rows with missing data due to inactive modes handled
- Transport modes with consistently low ridership removed
- A metadata table was created to log operation start dates and mode-specific inf

---

## ⚒️ Data Transformation

- Perform feature engineering by extracted time columns, `year`, `weekday`
- Transport mode clustering
- Discover relationship by scatterplot
- Transformation dataset used for BI visualization

---

## 🔍 Descriptive Analysis Highlights

- 96% ridership drop during COVID-19 MCO (March 2020)
- New Year’s Eve 2024 recorded highest ridership across all modes
- Weekend ridership is consistently lower than weekdays
- Strong correlation found between MRT Kajang and MRT Putrajaya
- Bus RKL and Bus RPN show the highest pairwise correlation (~0.97)
- Monthly and weekday trends show stable patterns for urban rails
- Correlation matrix & clustering show similar behavior across urban modes

---

## 📁 Data Versions

- cleaned_data.csv: Fully cleaned, used for BI & reporting
- transformed_data.csv: Includes added time features like year, weekday
- reduced_data.csv: Certain low-usage transport modes removed for cleaner insights

---

## 🔎 Dashboard (Power BI)

Created descriptive visuals showing:

- Monthly & yearly ridership trend
- Ridership comparison by transport mode
- Impact of MCO and major public holidays
- Correlation heatmap among different transport types

---
## 🛠 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Power BI
- Git & GitHub for version control

---

## 💡 Project Purpose

With Malaysia’s increasing urbanization, public transport plays a key role in sustainable development. This descriptive analysis helps authorities and stakeholders understand how the system is used over time, especially in response to events like MCO, weekends, and festive seasons.

---

## 📬 Contact

Build by [@weiiilunnnn](https://github.com/weiiilunnnn)

For questions, reach out via GitHub Issues or fork this project.
