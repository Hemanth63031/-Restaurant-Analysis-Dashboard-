# 🍽️ Restaurant Sales & Demand Analysis Dashboard (Power BI)

This project analyzes sales data for a local restaurant in Vishakapatnam to uncover insights related to customer demand, item performance, seasonal trends, and order behavior (Online vs Offline). The dashboard is built using Power BI, with data processing performed in Excel, SQL Server, and Power Query.
## 📷 Dashboard Preview
![image alt](https://github.com/Hemanth63031/-Restaurant-Analysis-Dashboard-/blob/72e7f98bab6b374e395070475a3a31eb4b219761/Screenshot%20(121).png)

## 📌 Project Overview

The client provided raw data in Excel format covering the period from January 2022 to August 2023.
The goal was to transform the data and build an interactive dashboard to answer key business questions such as:

Monthly sales trends
Top 5 and Bottom 5 performing items
Online vs Offline sales comparison
Year-wise and Season-wise performance
Average sales analysis
Total revenue and quantity-based insights
## 📂 Data Processing Workflow
* Excel → CSV Conversion
* Converted raw Excel file into CSV format for easier processing
* SQL Server (SSMS)
* Imported CSV into SQL Server Management Studio
* Cleaned data (handled nulls, formatting issues)
* Changed data types appropriately
* Created calculated fields:
* Revenue = Final Amount × Quantity
* Power BI
* Connected to SQL Server
* Used Power Query for additional transformations
* Built interactive dashboard and visuals
## 📊 Dataset Details
### Time Period: Jan 2022 – Aug 2023
### Location: Vishakapatnam (Local Restaurant)
* Key Columns:
 Date
 Item
* Season (Summer, Rainy, Winter)
* Order Type (Online / Offline)
* Amount
* Quantity
* Revenue
## 📈 Dashboard Features
#### KPIs
* Total Revenue
* Average Revenue per Item
#### Trend Analysis
* Monthly Sales Trend (Stacked Column Chart)
* Year-wise Sales Comparison (2022 vs 2023)
#### Item Performance
* Top 5 Items (by Month / Season / Overall)
* Bottom 5 Items
#### Sales Insights
* Online vs Offline Sales Comparison
* Season-wise Sales Distribution (Pie Chart)
#### Filters (Slicers)
* Order Type (Online / Offline)
* Year (2022, 2023)
## 📊 Visualizations Used
* Stacked Column Charts (Monthly Trends & Item Sales)
* Pie Chart (Season-wise Sales)
* KPI Cards (Revenue Metrics)
* Top N Filters (Top 5 / Bottom 5 Items)
## 🔍 Key Insights
* Identified top-performing and low-performing items
* Compared online vs offline sales contribution
* Analyzed seasonal impact on demand
* Observed monthly sales fluctuations and trends
* Measured average revenue performance
## 🛠️ Tools & Technologies
* Excel – Initial data handling
* SQL Server (SSMS) – Data cleaning & transformation
* Power Query – Data shaping in Power BI
* Power BI – Dashboard creation and visualization
## 🚀 How to Use
* Download the Power BI .pbix file
* Open in Power BI Desktop
* Use slicers to explore:
- Year-wise performance
- Online vs Offline comparison
* Item-level insights


