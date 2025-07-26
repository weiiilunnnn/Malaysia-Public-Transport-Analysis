# Malaysia Public Transport Ridership Analysis & Forecasting

This project focuses on analysing and predicting Malaysia's public transport ridership data using Python and Data Science Techniques witha clear pipeline from Data Cleaning and Exploratory Data Analysis (EDA) to Predictive Modeling and Business Intelligence (BI) visualization. The ultimate goal is to discovered usage patterns across MRT, LRT, Monorail, Buses, National Rail and build a predictive model for urbain rail ridership. The generated insights are visualized in Power BI dashboards to support decision-making for transport policy and planning.

---

## 📊 Dataset Overview

- **Source**: [[Custom ridership dataset of Malaysia’s public transport](https://data.gov.my/data-catalogue/ridership_headline)]
- **Time Span**: 2019 – 2025
- **Features**:
  - Daily ridership for MRT, LRT, Monorail, Buses, and National Rails
  - Date column, monthly trends
  - Urban vs regional transport modes

---

## 🔍 Exploratory Data Analysis (EDA)

Conducted in `01_data_cleaning_and_eda.ipynb`, the EDA process includes:

- Data type correction and null handling
- Total daily ridership trend analysis
- Minimum and maximum ridership days identified
- MCO (COVID-19 lockdown) impact quantified
- Monthly average ridership breakdown by transport mode
- Correlation matrix and clustering of transport modes:
  - Urban rails (LRT, MRT) show strong positive correlation (~0.97)
  - Bus services in different cities are also highly correlated
  - National rail services form a separate behavioral group

---

## 🧹 Data Cleaning Process

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

## 📉 Data Reduction Outcome

- Ridership dropped by ~96% during the MCO (March 2020)
- Highest ridership occurred on New Year’s Eve 2024
- Strong correlations found among city-based public transport
- MRT Kajang and MRT Putrajaya show similar behavior (~0.76 correlation)
- Bus RKL and Bus RPN are the most correlated pair (~0.97)

---

## Next Step

- Conduct Predictive Modeling
- Building BI Visualization

---

## 🔎 Key Insights

- ~96% drop during MCO (March 2020)
- Weekend ridership is consistently lower across all modes
- Urban rail ridership shows stable, predictable patterns
- National rails and regional buses follow different trends
- MRT Putrajaya has lower early correlation due to recent operation

---
## 🛠 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Power BI
- Streamlit
- Git & GitHub

---

## 💡 Motivation

Malaysia's growing urban population puts pressure on public transportation. By analyzing past usage and identifying behavioral trends, we aim to inform transport planning, scheduling, and infrastructure investment.

---

## 📬 Contact

Build by [@weiiilunnnn](https://github.com/weiiilunnnn)

For questions, reach out via GitHub Issues or fork this project.
