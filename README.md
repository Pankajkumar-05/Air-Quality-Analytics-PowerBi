# 🌍 Air Quality, Pollution and Health Impact Analysis using Power BI

## 📊 Project Overview

Air pollution has become a major environmental and public health concern in many cities. This project analyzes Air Quality Index (AQI) data across Indian cities to identify pollution trends, compare city-level air quality, analyze dominant pollutants, and evaluate potential health risks.

The project is developed using Microsoft Power BI, transforming large-scale air quality data into an interactive and user-friendly dashboard for analytical insights and decision support.

---

## 🎯 Project Objectives

- Analyze overall air quality trends across multiple years
- Identify the most polluted and cleanest cities
- Understand AQI category distribution
- Identify dominant pollutants affecting air quality
- Evaluate health risk exposure using derived indicators
- Analyze daily AQI trends for short-term fluctuations
- Build an interactive dashboard with slicers and navigation buttons

---

## 📌 Dashboard Pages

### 1️⃣ Air Quality Overview

This page provides a high-level summary of air quality conditions.

**Key Components**
- Average AQI KPI
- Best AQI City
- Worst AQI City
- Percentage of Poor/Severe AQI
- Yearly AQI Trend (Area Chart)
- India City-Level AQI Map

**Purpose**
To provide a quick understanding of overall air quality trends and pollution hotspots.

---

### 2️⃣ City-Level AQI Analysis & Distribution

This page focuses on comparing cities and AQI categories.

**Key Components**
- Top 10 Worst Polluted Cities
- Top 10 Cleanest Cities
- AQI Status Distribution

**Purpose**
To identify pollution-heavy cities and understand the distribution of AQI categories.

---

### 3️⃣ Health Impact & Exposure Analysis

This page connects air pollution with potential health risk indicators.

**Key Components**
- Average Health Impact Score
- High-Risk Cities Count (AQI > 200)
- Safe Cities Count (AQI ≤ 100)
- Prominent Pollutants Analysis
- Daily AQI Trend (Area Chart with Year & Month slicers)

**Purpose**
To analyze pollution exposure, dominant pollutants, and short-term AQI behavior.

---

## 📈 Key Insights

- PM2.5 appears as the most dominant pollutant across cities.
- A small number of cities contribute significantly to poor AQI levels.
- Moderate to Poor AQI categories occur frequently.
- Higher AQI values correspond to increased health risk levels.
- Daily AQI analysis reveals short-term fluctuations in air quality.

---

## 🛠 Tools & Technologies Used

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel

---

## 📊 KPI Definitions

- **Average AQI:** Represents overall pollution severity.
- **Best AQI City:** City with lowest average AQI.
- **Worst AQI City:** City with highest average AQI.
- **Poor/Severe AQI %:** Share of critical air quality observations.
- **Average Health Impact Score:** Derived indicator representing health risk level.
- **High-Risk Cities Count:** Cities where AQI exceeds 200.
- **Safe Cities Count:** Cities where AQI is 100 or below.

---

## ⚠ Challenges Faced

- Large dataset handling and performance optimization
- Absence of direct health impact data
- Map visualization dependency on internet connectivity
- Overcrowded visuals during initial analysis

---

## ✅ Solutions Implemented

- Aggregated measures for performance improvement
- Derived Health Impact Score using AQI thresholds
- Optimized visuals using Top-N filtering
- Separate slicers for daily AQI analysis

---

## 👤 Author

**Pankaj Kumar**  
Course: Data Pre-Processing and Business Analytics

---

## ⭐ If you found this project useful
Feel free to star this repository.
