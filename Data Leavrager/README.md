# Power BI Project - Employee & Sales Data Analysis

## Overview
This project demonstrates data cleaning, transformation, and visualization using **Microsoft Power BI**.  
Two datasets were used:
- **Dirty_Employee_Data.xlsx**: Employee details including department, region, salary, and performance.
- **Dirty_Sales_Data.xlsx**: Sales transactions including product category, revenue, cost, and customer details.

The project focuses on preparing raw data for analysis and building interactive dashboards.

---

## Features
- Data cleaning using **Power Query Editor**:
  - Standardized text (uppercase, trimmed).
  - Replaced null/invalid values with `"not assign"`.
  - Corrected column names and data types.
  - Removed duplicates and inconsistent entries.
- Data transformation:
  - Grouped sales by region to calculate **Total Sales**, **Average Order Value**, and **Transaction Count**.
  - Joined employee and sales data for enriched analysis.
- Visualization:
  - Regional sales performance.
  - Department-wise employee distribution.
  - Salary vs. performance comparison.
  - Customer demographics and purchase behavior.

---

## Program Flow
1. **Data Import**  
   Load Excel files into Power BI.

2. **Data Cleaning**  
   Apply transformations in Power Query:
   - Promoted headers  
   - Changed data types  
   - Replaced null values  
   - Renamed columns  

3. **Data Transformation**  
   - Grouped and aggregated sales data.  
   - Merged employee and sales datasets.  

4. **Visualization**  
   - Built dashboards with charts and KPIs.  
   - Enabled slicers for region, department, and product category.  

---

## Concepts Used
- **Power Query Editor** for ETL (Extract, Transform, Load).  
- **Data Profiling** to identify errors and missing values.  
- **Aggregation & Grouping** for regional analysis.  
- **Data Modeling** with relationships between tables.  
- **Interactive Dashboards** using Power BI visuals.  

---

## How to Use
1. Open the `.pbix` file in Power BI Desktop.  
2. Review applied transformations in **Power Query Editor**.  
3. Explore dashboards for insights.  
4. Modify filters/slicers to customize analysis.  


##Images
<img width="1918" height="1117" alt="sales" src="https://github.com/user-attachments/assets/61efe5f1-7925-41c2-9552-b0a81167c0b3" />
