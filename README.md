🌍 California Ozone Analysis — 2024

This project analyzes ozone pollution trends across California for the year 2024 using EPA Air Quality System (AQS) and AirNow datasets.
The study investigates seasonal variations, regional hotspots, spatial distribution, and weekday/weekend effects to provide actionable insights for air quality management.

📊 Key Insights

Seasonal Patterns: Ozone levels peak during summer months (June–August) due to higher photochemical activity.

Regional Hotspots: Inland counties consistently report the highest ozone concentrations, with some exceeding the EPA safety threshold of 70 ppb.

Data Source Comparison: AQS and AirNow align closely, confirming reliability, though slight variations exist.

Weekend Effect: A t-test (p = 0.4827) shows no significant difference between weekday and weekend ozone levels.

Spatial Distribution: Heatmaps reveal inland regions as ozone hotspots, while coastal areas remain relatively cleaner.

🛠️ Project Workflow

Data Preprocessing

Cleaned date formats, handled missing values, standardized county names

Removed duplicates and created derived features (Month, Day of Week, Weekend flag)

Exploratory Analysis & Visualizations

Seasonal line plots of ozone concentration by measurement source

Heatmaps of county-level seasonal variation

Spatial distribution using Folium maps

Weekday vs. weekend comparison with bar plots and t-tests

Statistical Analysis

Independent t-test to evaluate weekend effect

Comparison of means across regions and seasons
