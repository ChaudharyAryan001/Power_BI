# Power BI Project - Sales & Customer Analytics

## Overview
This project demonstrates a complete **Business Intelligence workflow** using Microsoft Power BI.  
It integrates multiple fact and dimension tables to build a star schema model and deliver interactive dashboards for sales, customer, product, and regional analysis.

---

## Datasets
- **Sales_Fact.xlsx**: Transaction-level sales data (CustomerID, ProductID, RegionID, DateKey, Quantity, Revenue, Discount).
- **Returns_Fact.xlsx**: Product returns data with reasons and dates.
- **Customer_Dim.xlsx**: Customer demographics (Age, Gender, Segment).
- **Product_Dim.xlsx**: Product details (Category, Subcategory, Brand).
- **Region_Dim.xlsx**: Regional hierarchy (Country, State, City).
- **Date_Dim.xlsx**: Calendar table with fiscal year, month, quarter.
- **Dirty_Employee_Data.xlsx**: Employee details (Department, Region, Salary, Performance).
- **Dirty_Sales_Data.xlsx**: Raw sales transactions with cleaning requirements.

---

## Features
- **Data Cleaning & Transformation**
  - Standardized text formatting (uppercase, trimmed).
  - Replaced null/invalid values with `"not assign"`.
  - Corrected column names and data types.
  - Removed duplicates and inconsistent entries.
- **Data Modeling**
  - Built a **star schema** with Sales_Fact and Returns_Fact as fact tables.
  - Linked dimension tables (Customer, Product, Region, Date).
  - Established relationships for drill-down analysis.
- **Analytics**
  - Regional sales performance (Total Sales, Average Order Value, Transaction Count).
  - Customer segmentation by age, gender, and loyalty tier (Gold, Silver, Platinum).
  - Product category and brand distribution.
  - Return analysis by reason and frequency.
  - Employee performance vs. salary insights.
- **Visualization**
  - KPI cards for Revenue, Quantity, Discount, Returns.
  - Donut charts for revenue by gender and segment.
  - Bar charts for sales by country, product category, and brand.
  - Time-series analysis using Date_Dim.
  - Interactive slicers for region, category, and segment.

---

## Program Flow
1. **Data Import**  
   Load all Excel files into Power BI.

2. **Data Cleaning**  
   Apply transformations in Power Query:
   - Promoted headers  
   - Changed data types  
   - Replaced null values  
   - Renamed columns  

3. **Data Modeling**  
   - Create relationships between fact and dimension tables.  
   - Build star schema for efficient reporting.  

4. **Visualization**  
   - Design dashboards with KPIs, charts, and filters.  
   - Enable drill-down for detailed insights.  

---

## Concepts Used
- **Power Query Editor** for ETL (Extract, Transform, Load).  
- **Star Schema Modeling** for structured analytics.  
- **Data Profiling** to identify errors and missing values.  
- **Aggregation & Grouping** for regional and product analysis.  
- **Interactive Dashboards** using Power BI visuals.  

---

## How to Use
1. Open the `.pbix` file in Power BI Desktop.  
2. Review applied transformations in **Power Query Editor**.  
3. Explore dashboards for insights across sales, customers, products, and returns.  
4. Modify filters/slicers to customize analysis.  
