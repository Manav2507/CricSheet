# Cricsheet Match Data Analysis

## Overview
This project involves analyzing cricket match data from Cricsheet, focusing on processing, storing, and visualizing data to uncover key insights. Using tools such as SQL, Python, and Power BI, the project demonstrates the integration of data processing and visualization for sports analytics.

---

## Skills Gained
- **Data Processing (Python):** Work with JSON files and transform data into structured formats using Pandas.
- **Database Management (SQL):** Create tables, insert data, and write optimized SQL queries.
- **Data Analysis (SQL):** Derive insights using analytical queries.
- **Visualization (Power BI):** Build interactive dashboards for storytelling and decision-making.
- **Data Preprocessing:** Clean and organize raw JSON data into meaningful structures.
- **Automation:** Streamline data collection using Selenium for efficiency.

---

## Domain
**Sports Analytics / Data Analysis**

---

## Problem Statement
The project aims to process, analyze, and visualize cricket match data available on [Cricsheet](https://cricsheet.org/matches/). The focus is download match data in JSON format, processing it with Python, storing it in SQL databases, and building dashboards in Power BI for analysis.

## Approach
1. **Data Downloading:**
   - Download JSON files for all match formats (Test, ODI, T20).

2. **Data Transformation:**
   - Parse and normalize JSON files using Python and Pandas.
   - Create structured DataFrames for each match format.

3. **Database Management:**
   - Create a SQL database (e.g., MySQL/SQLite) with tables for each match type.
   - Populate tables with cleaned data using Python's database connectors.

4. **SQL Queries for Analysis:**
   - Write 10 queries to extract insights, such as:
     - Top 10 batsmen by total runs in ODI matches.
     - Leading wicket-takers in T20 matches.
     - Teams with the highest win percentages.
     - Matches with the narrowest victory margins.

5. **Exploratory Data Analysis (EDA):**
   - Create visualizations using libraries like Matplotlib, Seaborn, and Plotly.

6. **Power BI Dashboard:**
   - Connect Power BI to the SQL database.
   - Build interactive dashboards showcasing:
     - Player performance trends.
     - Match outcomes by teams.
     - Win/loss analyses across formats.

## Project Deliverables
1. **Python Code:** JSON-to-DataFrame transformation, and SQL operations.
2. **SQL Database:** A database schema with structured tables.
3. **SQL Query File:** Document containing 20 SQL queries.
4. **EDA Visualizations:** Graphs and insights using Python libraries.
5. **Power BI Dashboard:** Interactive `.pbix` file.
6. **Documentation:** A detailed project report.

---

## Tools and Technologies
- **Programming:** Python (Pandas, Matplotlib, Seaborn, Plotly)
- **Web Scraping:** Selenium
- **Database:** MySQL/SQLite
- **Visualization:** Power BI
- **Data Format:** JSON
