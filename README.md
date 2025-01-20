# Cricsheet Match Data Analysis

## Overview
This project involves analyzing cricket match data from Cricsheet, focusing on scraping, processing, storing, and visualizing data to uncover key insights. Using tools such as Selenium, SQL, Python, and Power BI, the project demonstrates the integration of data processing and visualization for sports analytics.

---

## Skills Gained
- **Web Scraping (Selenium):** Automate browsing and data extraction from dynamic websites.
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
The project aims to scrape, process, analyze, and visualize cricket match data available on [Cricsheet](https://cricsheet.org/matches/). The focus is on using Selenium to download match data in JSON format, processing it with Python, storing it in SQL databases, and building dashboards in Power BI for analysis.

---

## Business Use Cases
1. **Player Performance Analysis:** Evaluate players' performance across different formats (Test, ODI, T20).
2. **Team Insights:** Analyze team performance over time.
3. **Match Outcomes:** Understand win/loss patterns and margins of victory.
4. **Strategic Decision-Making:** Support analysts and management in making informed decisions.
5. **Fan Engagement:** Present interactive dashboards for fans to explore match data and statistics.

---

## Approach
1. **Data Scraping:**
   - Automate navigation to Cricsheet using Selenium.
   - Download JSON files for all match formats (Test, ODI, T20).

2. **Data Transformation:**
   - Parse and normalize JSON files using Python and Pandas.
   - Create structured DataFrames for each match format.

3. **Database Management:**
   - Create a SQL database (e.g., MySQL/SQLite) with tables for each match type.
   - Populate tables with cleaned data using Python's database connectors.

4. **SQL Queries for Analysis:**
   - Write 20 queries to extract insights, such as:
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

---

## Results
- JSON data successfully scraped from Cricsheet.
- Structured SQL database with Test, ODI, and T20 match tables.
- SQL queries to analyze player and team performance metrics.
- Dynamic Power BI dashboard for visual insights.

---

## Project Deliverables
1. **Python Code:** Scripts for Selenium scraping, JSON-to-DataFrame transformation, and SQL operations.
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

---

## Timeline
**1 Week**

---

## Evaluation Metrics
1. **Data Accuracy:** Validating scraped data and SQL transformations.
2. **SQL Query Quality:** Assessing efficiency and relevance.
3. **Dashboard Insights:** Reviewing completeness and visual appeal.
4. **Integration:** Evaluating seamless use of Selenium, SQL, and Power BI.
5. **Presentation:** Quality of insights and overall project execution.

---

## Additional Resources
- [Cricsheet Match Data](https://cricsheet.org/matches/)
- [Power BI Work Account Setup](https://docs.google.com/document/u/0/d/1QisLD2kqDWFZJG2oDknKn2eMGi-Xq8oFPgA7UWSbcIQ/edit)
