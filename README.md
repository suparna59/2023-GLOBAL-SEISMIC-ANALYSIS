# 🌍 2023-GLOBAL-SEISMIC-ANALYSIS
Statistical and machine learning analysis of the 2023 Global Seismic dataset to explore seismic patterns, event types, and risk factors.

This project analyzes the **2023 Global Seismic dataset** from the **United States Geological Survey (USGS)** to uncover trends and patterns in seismic activity. The dataset includes a variety of events such as earthquakes, volcanic eruptions, explosions, and landslides recorded globally during 2023. The analysis supports hazard assessment, risk mitigation, and emergency preparedness planning.

---

## 📁 Dataset Overview

- **Source:** United States Geological Survey (USGS) via Kaggle  
- **Year Covered:** 2023  
- **Number of Variables:** 22  
- **Event Types:** Earthquakes, Volcanic Eruptions, Explosions, Landslides  

**Key Columns:**
- **Spatial:** `latitude`, `longitude`, `depth`  
- **Temporal:** `time`  
- **Seismic Data:** `mag`, `magType`, `nst`, `gap`, `dmin`, `rms`  
- **Metadata:** `place`, `type`, `status`, `id`, `locationSource`, `magSource`, `depthError`, etc.

---

## 🧹 Data Cleaning

- Removed duplicate rows to ensure each event is uniquely represented  
- Handled missing values by replacing them with `0` for consistency  
  > Note: Zero imputation is a temporary solution and may affect statistical outcomes. Future work may apply better imputation techniques.

---

## 🎯 Project Objectives

- Explore global seismic activity patterns in 2023  
- Analyze relationships between variables like depth, magnitude, and event type  
- Identify clusters of related seismic events  
- Build visual dashboards for geographic and temporal insights  

---

## 🛠 Tools Used

- **R**  
  - `tidyverse` for data manipulation  
  - `ggplot2` for visualizations  
  - `dplyr`, `readr`, `lubridate` for cleaning and processing  
  - `cluster`, `factoextra` for clustering  
  - `caret` for basic classification tasks  

- **Tableau**  
  - Used for building interactive dashboards  
  - Visualized earthquake distribution, magnitude vs. depth, and event types by region

---

## 📊 Methods Applied

- Exploratory Data Analysis (EDA)  
- Correlation analysis  
- Clustering (e.g., k-means)  
- Classification modeling for event type prediction  
- Geospatial and temporal visualizations using Tableau  

---

## 📈 Visual Outputs

- 🌍 World map of seismic events by type  
- 📊 Bar charts of event counts per month  
- 🌀 Cluster plots of seismic groups  
- 📍 Tableau dashboards for interactive exploration  

---

## 🔍 Future Enhancements

- Improve missing value handling using imputation techniques  
- Apply spatial analysis using R packages like `sf` or `leaflet`  
- Integrate real-time data sources for live monitoring  
- Expand Tableau dashboards with filters and drill-down options  
