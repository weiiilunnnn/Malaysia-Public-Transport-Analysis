# Malaysia Public Transport Optimization

This project explores and analyzes public transport ridership data across Malaysia using Python and data science techniques. The project begins with data cleaning and exploratory analysis, then progresses through feature engineering, data reduction, and predictive modeling. 
The final goal is to forecast ridership patterns and identify usage trends across different transport modes (MRT, LRT, buses, and national rails). Insights generated will be visualized using **Power BI dashboards** to assist policymakers, urban planners, and transport authorities in making informed, data-driven decisions for future transport planning, resource allocation, and service optimization.

---

## 📊 Dataset

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

## 🧹 Data Cleaning Highlights

- Converted date to `datetime` format
- Missing values imputed with `0` where appropriate
- Non-active or niche transport modes (peak ridership < 50,000) flagged for removal

---

## 📌 Key Findings

- Ridership dropped by ~96% during the MCO (March 2020)
- Highest ridership occurred on New Year’s Eve 2024
- Strong correlations found among city-based public transport
- MRT Kajang and MRT Putrajaya show similar behavior (~0.76 correlation)
- Bus RKL and Bus RPN are the most correlated pair (~0.97)

---

## 🧠 Planned Next Steps

- Data Reduction: Remove low-impact transport columns
- Feature Engineering: Add new variables (e.g., weekend flag, moving averages)
- Predictive Modeling: Forecast future ridership using time-series or ML methods

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

Created by [@weiiilunnnn](https://github.com/weiiilunnnn)

For questions, reach out via GitHub Issues or fork this repo!
