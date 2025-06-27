# 🏏 Cricsheet Match Data Analysis

This project analyzes international cricket match data (Test, ODI, and T20 formats) from [Cricsheet.org](https://cricsheet.org), focusing on transforming raw JSON files into structured databases and powerful dashboards for actionable insights.

---
## 📸 Demo Screenshots

![Preview](https://github.com/Manav2507/CricSheet/blob/main/test_das.png)
![Preview](https://github.com/Manav2507/CricSheet/blob/main/t20_des.png)
![Preview](https://github.com/Manav2507/CricSheet/blob/main/odi_des.png)

## 📌 Overview

- ⛏️ Extracted and processed real-world JSON cricket data using Python
- 🛢️ Built a SQL database to store normalized data efficiently
- 📈 Created SQL queries to uncover performance and match-based trends
- 📊 Developed interactive dashboards using Power BI for storytelling and decision-making

---

## 🎯 Problem Statement

> **How can raw cricket match data be transformed into structured insights for analysts, broadcasters, and fans?**

This project aims to bridge raw match JSON files and analytical dashboards by building a complete ETL + analysis + visualization pipeline.

---

## ⚙️ Approach

### 📥 1. Data Acquisition

- Downloaded JSON match files for:
  - Test Matches
  - One Day Internationals (ODIs)
  - T20 Internationals

### 🔄 2. Data Transformation (Python)

- Parsed nested JSONs using `json` and `pandas`
- Normalized key stats like:
  - Player performance (runs, wickets)
  - Match outcomes
  - Ball-by-ball details

### 🗃️ 3. SQL Database Design

- Created schema for storing:
  - Match Info
  - Player Stats
  - Team Summaries
- Inserted transformed data using `sqlite3` / `mysql.connector`

### 🔍 4. SQL Analysis

> Sample Queries:
- 🏏 Top 10 batsmen by ODI runs
- 🎯 Best T20 wicket-takers
- 🧮 Teams with highest win ratios
- 🔥 Closest victory margins
- ⏱️ Longest matches by duration

### 📊 5. Visualizations

#### a. Python EDA
- Used `Matplotlib`, `Seaborn`, `Plotly` for:
  - Run rate trends
  - Player performance over time
  - Format-based comparisons

#### b. Power BI Dashboard
- Connected to SQL database
- Built dashboard with:
  - Win/Loss Heatmaps
  - Player and Team Analytics
  - Format-wise performance trends

---

## 💡 Skills Demonstrated

- **Python**: JSON parsing, data wrangling
- **SQL**: Schema design, analytical queries
- **Power BI**: Dashboard development
- **EDA**: Visual storytelling, pattern recognition

---

## 🧰 Tools & Tech Stack

| Category         | Tools Used                             |
|------------------|-----------------------------------------|
| Programming      | Python (Pandas, JSON, Plotly, Seaborn)  |
| Database         | MySQL / SQLite                          |
| Visualization    | Power BI                                |
| Data Format      | JSON (from Cricsheet.org)               |

---

## 📦 Project Deliverables

- ✅ Python scripts for data transformation and insertion
- ✅ SQL schema and 20+ analysis queries
- ✅ EDA visuals (Python)
- ✅ Power BI `.pbix` dashboard
- ✅ Project documentation/report

---

## 📸 Screenshots / Demo

> Add 2–3 images of:
- The Power BI dashboard
- Sample SQL query results
- Python EDA visuals
