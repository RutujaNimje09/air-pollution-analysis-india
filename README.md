# 🌍 Air Pollution Analysis India
### Interactive Power BI Dashboard for Air Quality Analysis across Indian States & Cities

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-green)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-Analytics-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📖 Overview

This project presents an **interactive Power BI dashboard** built to analyze **PM10 concentration** and **Acute Respiratory Illness (ARI)** across Indian states and cities using publicly available government air quality data.

The dashboard enables users to identify pollution hotspots, compare air quality across regions, analyze historical trends, and explore urban versus rural pollution levels through interactive visualizations and filters.

---

# 📊 Dashboard Preview

## 🏠 Dashboard Overview

![Dashboard Overview](images/overview.png)

---

## 📈 Trend Analysis

![Trend Analysis](images/trends.png)

---

# 🎯 Objectives

- Analyze PM10 concentration across Indian cities and states.
- Compare pollution levels between different regions.
- Track historical PM10 trends across multiple years.
- Identify locations with the highest and lowest pollution levels.
- Compare Urban and Rural air quality.
- Build an interactive dashboard for data-driven exploration.

---

# 🗂 Dataset

**Source**

Publicly available Government air quality data compiled from official reports and articles.

**Coverage**

- 🇮🇳 India
- State-wise Acute Respiratory Illness (ARI) count
- City-wise PM10 Concentration
- Historical pollution trends

---

# 🧹 Data Preparation

The dataset was cleaned and transformed using **Power Query**.

### Data Cleaning & Transformation

- Removed blank rows
- Filtered unnecessary records
- Trimmed text values
- Renamed columns
- Changed data types
- Replaced inconsistent values
- Split text using delimiters
- Removed unwanted columns
- Created derived tables for trend analysis

---

# 🏗 Data Model

The dashboard combines PM10 and ARI datasets using relationships within the Power BI data model.

Additional supporting tables were created to improve dashboard performance and enable:

- Trend Analysis
- Time-series Visualizations
- Data Reshaping (Unpivoted Tables)

---

# 📌 Dashboard Features

### KPI Cards

- 📍 Average PM10 Concentration
- 📍 Average ARI (%)
- 📍 Highest PM10
- 📍 Lowest PM10

### Interactive Visualizations

- 🗺 Map Visualization
- 📈 Line Chart
- 📊 Clustered Bar Chart
- 📉 Stacked Bar Chart
- 🎯 Scatter Plot
- 🌳 Treemap
- 🍩 Donut Chart
- 🎛 Interactive Slicers

---

# 🔍 Key Insights

- Urban areas generally exhibit higher PM10 concentrations compared to rural areas.
- Significant variation in pollution levels can be observed across Indian states.
- The dashboard highlights cities with the highest and lowest PM10 concentrations.
- Historical trends provide insight into changes in pollution over multiple years.
- Interactive filtering allows users to explore pollution data at both the state and city level.

---

# 🛠 Technologies Used

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization

---

# 💡 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Measure Creation
- Dashboard Design
- KPI Reporting
- Interactive Reporting
- Business Intelligence
- Analytical Storytelling

---

# 📂 Repository Structure

```text
air-pollution-analysis-india/
│
├── AirPollution_ARI_Dashboard.pbix
├── README.md
│
└── images/
    ├── overview.png
    └── trends.png
```

---

# 🚀 How to Use

1. Clone or download this repository.
2. Open **AirPollution_ARI_Dashboard.pbix** using Microsoft Power BI Desktop.
3. Interact with the dashboard using the available slicers and filters.
4. Explore pollution trends across Indian cities and states.

---

# 🔮 Future Improvements

- Include additional air quality indicators such as PM2.5, NO₂, SO₂ and CO.
- Integrate live air quality APIs for real-time monitoring.
- Add forecasting models for future pollution trends.
- Improve drill-through analysis and report navigation.

---

## ⭐ If you found this project interesting, consider giving the repository a star!
