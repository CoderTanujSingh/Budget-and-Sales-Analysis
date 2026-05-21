# Budget-and-Sales-Analysis

✅ 📊 Power BI Project: Sales vs Budget Performance Dashboard

📌 Project Overview

This project focuses on building an end-to-end Sales vs Budget Performance Dashboard in Power BI using real-world retail data. The goal is to analyze how each product and product category is performing against its planned budget across different time periods (MTD, QTD, YTD, YoY).

The dashboard includes advanced time-intelligence calculations, category-level KPIs, and performance flags to help management identify trends, gaps, and growth opportunities.

📁 Dataset Description

This project uses four core tables:

Sales – Contains daily sales transactions

Budget – Monthly allocated budgets per product

Product Master – Product details including Category and Product Name

Date Table – Standard calendar used for all time-intelligence calculations

Measure Table – Contains all created KPIs

🎯 Project Objectives

The project aims to:

Build a clean and scalable data model connecting Sales, Budget, Product, and Calendar tables.

Develop custom DAX measures to evaluate performance at multiple time levels.

Provide insights into:

Sales vs Budget variances

Best and worst performing products

Category performance trends

Year-over-year growth

Create an interactive and user-friendly Power BI dashboard with drill-down capability.

🧩 Data Model Design

A star-schema data model was implemented:

Sales → linked to Product Master

Budget → linked to Product Master

Product Master → acts as product dimension

Date Table → primary date dimension for time intelligence

Relationships support full MTD, QTD, YTD, YoY analysis.

🧮 Key DAX Measures Implemented

Time Intelligence

MTD Sales / MTD Budget

QTD Sales / QTD Budget

YTD Sales / YTD Budget

YoY Sales / YoY Budget

Rolling 3 Months Sales

Rolling 12 Months Sales

Same Period Last Year (SPLY) Sales

YoY Growth %

YoY Variance

Category-Level Performance

Category Sales Total

Category Budget Total

Category Achievement %

Category MTD, QTD, YTD, YoY

Ranking & Contribution

Top 5 Products by Sales

Bottom 5 Products by Sales

Product Rank by Sales

KPI Indicators

Achievement Status Flag (Green/Red)

Dynamic variance calculations

KPI cards for Sales, Budget, Variance, Achievement %

📊 Dashboard Features

The final report contains:

📌 Page 1 — Executive Summary

KPI Cards: Sales, Budget, Variance, Achievement %

Monthly trend line: Sales vs Budget

Category-level Achievement % bar chart

📌 Page 2 — Product Performance

Table showing Sales, Budget, Achievement %, Variance

Top 5 and Bottom 5 product visuals

Scatter plot (Sales vs Budget)

📌 Page 3 — Trend Analysis

YoY charts

Rolling 3M / 12M visuals

Category trend comparison

📌 Interactivity

Slicers for Category, Product, Date

Drill-down on category → product

Cross-filter enabled across visuals

📈 Business Insights Generated

(Write your own insights after building your dashboard)

Examples include:

Identifying overperforming and underperforming categories

Products with the highest budget variance

Seasonality or trend changes through YoY and rolling metrics

Overall achievement performance and gaps

🛠️ Tools & Technologies

Power BI Desktop

DAX (Time Intelligence, Ranking, KPI Indicators)

Power Query / M Language

Data Modeling (Star Schema)

📦 GitHub Repository Includes

Power BI .pbix file

Dataset files (if allowed) or schema description

README with project summary

Screenshots of dashboard pages

Full list of custom DAX measures

<img width="1353" height="805" alt="Budget and Sales Analysis" src="https://github.com/user-attachments/assets/d8a64ac2-ddc4-41c6-91a8-999d29a0e2e7" />



