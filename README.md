# Retail Sales ETL Pipeline — Alteryx + Power BI

## Project Overview
End-to-end ETL pipeline built in Alteryx Designer Cloud to clean, 
transform, and aggregate raw retail sales data into KPI-ready output.

## Tools Used
Alteryx Designer Cloud | Power BI | DAX | CSV

## ETL Workflow Steps
1. Input Data — ingested 30-row retail_sales_raw.csv
2. Select — set data types (Float, Integer)
3. Filter — removed null Dates, Quantities, empty Regions (28 clean rows)
4. Formula — calculated Revenue, DiscountedRevenue, Profit
5. Summarize — aggregated KPIs by Region and Category
6. Output — exported final_output.csv

## Key Results
- Cleaned messy real-world data with null values and type mismatches
- Calculated Revenue, Discounted Revenue (with null-safe discount logic)
- Aggregated KPIs by Region and Category
- Connected output to Power BI for interactive dashboard

## Power BI Dashboard
- Bar chart: Revenue by Region
- Donut chart: Profit by Category  
- Card: Total Revenue
- Slicers: Region, Category filters
