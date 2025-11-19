# Power-BI-AdventureWorks-Project
📈 Power BI Project: Sales Analysis Dashboard

🎯 Overview

This repository contains the solution file (01-Solution-Sales Analysis.pbix) for a comprehensive sales performance dashboard. The report is designed to provide quick, actionable insights into revenue, profit margins, and customer behavior, allowing stakeholders to monitor key business health indicators and identify areas for growth or concern.

🛠️ Technical Details

Power BI File

File

Description

Solution-Sales Analysis.pbix

The main Power BI Desktop file containing the data model, Power Query steps, DAX measures, and all report visualizations.

Data Source & Preparation (Power Query / M)

The data model is typically sourced from a single sales database (similar to AdventureWorks or Northwind). Key data preparation steps implemented in Power Query (M language) include:

ETL (Extract, Transform, Load): Connecting to the raw data source.

Data Cleaning: Removing duplicates, handling null values, and enforcing consistent data types.

Table Joins: Merging disparate data tables (e.g., Sales, Products, Customers, Dates) to create a Star Schema for optimal performance.

Data Model

The model adheres to best practices, utilizing a Star Schema pattern:

Fact Table: Sales/Orders (containing quantitative data like quantity and amount).

Dimension Tables: Calendar (Date), Product, Customer, Geography (containing descriptive attributes).

Key DAX Measures

A robust set of DAX (Data Analysis Expressions) is used to define core business logic:

Measure

Purpose

Total Sales

Sum of net revenue/sales amount.

Total Profit

Calculated as Total Sales - Total Cost.

Profit Margin %

The ratio of Profit to Sales.

Quantity Sold

Total number of units sold.

New Customers

Count of customers whose first order occurred within the selected time period.

📊 Key Report Pages

The report is typically divided into several pages to guide the user through the analysis:

Executive Summary: High-level KPIs (Sales, Profit, Margin) displayed over time and against targets.

Product Deep Dive: Breakdown of sales by category, subcategory, and individual product performance.

Geographic Performance: Sales visualized on a map, ranked by region or country.

Customer Analysis: Insights into customer lifetime value, demographics, and purchasing frequency.

⚙️ How to Use

Prerequisite: Ensure you have Power BI Desktop installed.

Download: Clone this repository or download the 01-Solution-Sales Analysis.pbix file.

Open: Open the file using Power BI Desktop.

Interact: Use the slicers and filters on the right-hand pane to interactively explore sales data by date, region, or product.
