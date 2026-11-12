# 🌍 Global Air Quality Analysis (2025)

A data analysis project that studies **Air Quality Index (AQI) trends in 2025** across cities around the world. It focuses on **PM2.5** and **PM10**, the fine particles that most affect human health.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

---

## 📌 Overview

Air pollution is one of the biggest environmental health risks. This project cleans and analyses 2025 air quality data for global cities to answer three questions:

- How do pollution levels **change over the year**?
- Which cities have **the worst air quality**?
- Where do pollution levels **exceed WHO safety guidelines**?

---

## 🔍 What This Project Does

| Step | Description |
|------|-------------|
| **Data Cleaning** | Handled missing values, fixed data types and prepared the dataset with Pandas |
| **Statistical Analysis** | Calculated averages, standard deviations and other summary statistics with NumPy |
| **Trend Analysis** | Tracked how PM2.5 and PM10 levels change month by month |
| **Seasonal Patterns** | Found the seasons when pollution is highest and lowest |
| **City Comparison** | Compared pollution levels across cities and regions |
| **WHO Comparison** | Checked city pollution levels against WHO guidelines to find critical areas |
| **Spike Detection** | Found sudden pollution spikes in the time-series data, which can come from traffic, industry or wildfires |

---

## 📏 WHO Air Quality Guidelines (2021)

| Pollutant | Annual Mean | 24-Hour Mean |
|-----------|-------------|--------------|
| **PM2.5** | 5 µg/m³     | 15 µg/m³     |
| **PM10**  | 15 µg/m³    | 45 µg/m³     |

Cities above these limits were marked as **high-risk**.

---

## 📊 Visualizations

Charts made with Matplotlib:

- 📈 **Line charts** of monthly pollution trends
- 📊 **Bar charts** comparing average pollution by city
- 🗓️ **Seasonal plots** of how pollution varies through the year
- 🚨 **WHO threshold charts** that highlight cities above safe limits

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Programming language |
| **Pandas** | Data cleaning and manipulation |
| **NumPy** | Numerical calculations |
| **Matplotlib** | Data visualization |

---

## 💡 Key Insights

- Pollution levels follow **clear seasonal patterns**, often getting worse in colder months.
- Several cities are **well above WHO guidelines** for PM2.5 and PM10.
- **Sudden spikes** in the data point to short-term events like wildfires or heavy traffic.
- The results show **regions where policy action is needed** to improve air quality.

---

## 🎯 Outcome

- Found useful patterns in **global air pollution trends** for 2025
- Highlighted **cities that need urgent attention** based on WHO standards
- Gained hands-on experience in **data cleaning, analysis and visualization** of environmental data
