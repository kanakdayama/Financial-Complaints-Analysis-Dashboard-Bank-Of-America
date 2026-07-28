# Bank of America Consumer Complaints Analysis (2017–2023)

## Overview
This project analyzes Bank of America consumer complaints (2017–2023) using Python, SQL, and Power BI. Key findings: Checking/savings accounts drive ~40% of all complaints (24,814 of 62,516) — nearly 4x the next highest product. Complaint volume grew from 5,394 in 2017 to a peak of 12,953 in 2022, before declining to 9,131 in 2023. Overall, 93.77% of complaints received a timely response. Student loan complaints had the slowest average response time (~2.1 days) — nearly 3x slower than Credit reporting complaints (~0.74 days), the fastest-resolved category.

## Tools Used
- Python (pandas, matplotlib, seaborn) — data cleaning & feature engineering
- SQL (SQLite) — business queries & KPI calculations
- Power BI — interactive dashboard

## Dataset
- Source: Maven Analytics (originally CFPB public complaint data)
- 62,516 records, 2017–2023
- Fields: Product, Issue, State, dates, response type, and more

## Project Workflow
1. **Data Cleaning (Python)** — checked for missing values/duplicates, handled nulls, verified data types
2. **Feature Engineering** — created Response Time (Days), Complaint Year/Month/Quarter, and a custom Priority Score/Level to flag high-risk complaints
3. **Exploratory Analysis** — visualized trends by product, issue, time, and resolution type
4. **SQL Queries** — business questions and KPIs (timely response rate, avg response time by product, seasonal trends)
5. **Power BI Dashboard** — single-page interactive dashboard with KPI cards, trend charts, top products, resolution breakdown, and a drill-down table

## Key Insights
- Checking/savings accounts account for ~40% of all complaints (24,814 of 62,516) — nearly 4x the next highest product
- Complaint volume grew from 5,394 in 2017 to a peak of 12,953 in 2022, before declining to 9,131 in 2023
- 93.77% of complaints received a timely response, providing a clear baseline KPI for company accountability
- Student loan complaints have the slowest average response time (~2.1 days) — nearly 3x slower than Credit reporting complaints (~0.74 days), the fastest-resolved category

## Files in this repo
- 01_Data_Profiling.ipynb` — full Python cleaning & analysis notebook
- dashboard_screenshot.png` — Power BI dashboard preview

