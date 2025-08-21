# 🌍 California Ozone Analysis — 2024

This project analyzes ozone pollution trends across California for the year 2024 using **EPA Air Quality System (AQS)** and **AirNow** datasets.
The study investigates **seasonal variations, regional hotspots, spatial distribution, and weekday/weekend effects** to provide actionable insights for air quality management.

---

## 📊 Key Insights

* **Seasonal Patterns**: Ozone levels peak during **summer months (June–August)** due to higher photochemical activity.
* **Regional Hotspots**: Inland counties consistently report the highest ozone concentrations, with some exceeding the **EPA safety threshold of 70 ppb**.
* **Data Source Comparison**: AQS and AirNow align closely, confirming reliability, though slight variations exist.
* **Weekend Effect**: A t-test (p = 0.4827) shows no significant difference between weekday and weekend ozone levels.
* **Spatial Distribution**: Heatmaps reveal inland regions as ozone hotspots, while coastal areas remain relatively cleaner.

---

## 🛠️ Project Workflow

1. **Data Preprocessing**

   * Cleaned date formats, handled missing values, standardized county names
   * Removed duplicates and created derived features (Month, Day of Week, Weekend flag)

2. **Exploratory Analysis & Visualizations**

   * Seasonal line plots of ozone concentration by measurement source
   * Heatmaps of county-level seasonal variation
   * Spatial distribution using **Folium maps**
   * Weekday vs. weekend comparison with bar plots and t-tests

3. **Statistical Analysis**

   * Independent t-test to evaluate weekend effect
   * Comparison of means across regions and seasons

---

## 📑 Executive Summary

Ozone pollution in California remains a significant environmental concern, with **summer months and inland counties posing the greatest risks**.
The analysis highlights the importance of **seasonally targeted interventions** and demonstrates that activity-based effects (weekend vs. weekday) are minimal.
Findings from this project can aid policymakers, environmental agencies, and researchers in designing **data-driven strategies** for air quality improvement.

---

## ✨ Future Work

* Extend analysis with **multi-year data** for trend detection
* Incorporate **meteorological factors** (temperature, wind, humidity)
* Develop a **predictive model** for ozone concentration forecasting

---

## 👨‍💻 Author

**Sarthak Mangalmurti**

Do you want me to also prepare the **requirements.txt** file for you so it’s ready to drop into the repo?
