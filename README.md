# Cricsheet Match Data Analysis

## Overview
This project involves analyzing cricket match data from the [Cricsheet website](https://cricsheet.org/matches/), focusing on processing, storing, and visualizing data to uncover key insights. By utilizing tools such as Python, SQL, and Power BI, the project demonstrates the integration of data processing and visualization techniques for sports analytics.

---

## Skills Gained
- **Data Processing (Python):** Transform raw JSON files into structured formats using Pandas.
- **Database Management (SQL):** Design tables, insert data, and write optimized queries.
- **Data Analysis (SQL):** Extract insights with analytical queries.
- **Visualization (Power BI):** Build interactive dashboards for storytelling and decision-making.
- **Data Preprocessing:** Clean and organize raw JSON data into meaningful structures.

---

## Domain
**Sports Analytics / Data Analysis**

---

## Problem Statement
The goal is to process, analyze, and visualize cricket match data from Cricsheet. The project involves downloading match data in JSON format, processing it with Python, storing it in SQL databases, and building Power BI dashboards for analysis.

---

## Approach
1. **Data Downloading:**
   - Download JSON files for Test, ODI, and T20 match formats.

2. **Data Transformation:**
   - Parse and normalize JSON files using Python and Pandas.
   - Create structured DataFrames for each match format.

3. **Database Management:**
   - Create a SQL database (MySQL/SQLite) with tables for each match type.
   - Populate the tables with cleaned data using Python's database connectors.

4. **SQL Queries for Analysis:**
   - Write 10+ queries to extract insights:
     - Top 10 batsmen by total runs in ODI matches.
     - Leading wicket-takers in T20 matches.
     - Teams with the highest win percentages.
     - Matches with the narrowest victory margins.

5. **Exploratory Data Analysis (EDA):**
   - Visualize data trends using Python libraries like Matplotlib and Seaborn.

6. **Power BI Dashboard:**
   - Connect Power BI to the SQL database.
   - Build interactive dashboards showcasing:
     - Player performance trends.
     - Match outcomes by teams.
     - Win/loss analyses across formats.

---

## Project Deliverables
1. **Python Code:** JSON-to-DataFrame transformation and SQL operations.
2. **SQL Database:** A database schema with structured tables.
3. **SQL Query File:** A document containing 20 SQL queries.
4. **EDA Visualizations:** Graphs and insights created with Python libraries.
5. **Power BI Dashboard:** An interactive `.pbix` file.
6. **Documentation:** A detailed project report.

---

## Tools and Technologies
- **Programming:** Python (Pandas, Matplotlib, Seaborn, Plotly)
- **Web Scraping:** Selenium
- **Database:** MySQL/SQLite
- **Visualization:** Power BI
- **Data Format:** JSON

---

## Resources
- **CSV File and Database:** [Download here](https://drive.google.com/drive/folders/1AerrgbHzQ52Q8-RH3J0m17hsEFEaN2Zx?usp=sharing)

---

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
