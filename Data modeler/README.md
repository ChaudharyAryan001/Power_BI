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


## Files Included
- Power BI (.pbix)
- Dataset files
- Screenshots
- Project Report


  ##Customer.png
  <img width="1902" height="940" alt="image" src="https://github.com/user-attachments/assets/93479d34-326c-47a3-b6ba-96f7d4404f91" />


  ##Date.png
  <img width="1910" height="952" alt="image" src="https://github.com/user-attachments/assets/40ff20b3-f368-4753-a002-13d90ec019ac" />


  ##Product.png
  <img width="1908" height="912" alt="image" src="https://github.com/user-attachments/assets/bcca410e-50de-4dc8-a3ce-ed8c5ee2a0f6" />


  ##Region.png
  <img width="1915" height="907" alt="image" src="https://github.com/user-attachments/assets/63c45d6d-41ee-4e8a-8b20-418eccc3bb80" />


  ##Return.png
  <img width="1913" height="967" alt="image" src="https://github.com/user-attachments/assets/cefac76d-5b0c-4e9b-a9c4-f681ab6ab67f" />


  ##Sales.png
  <img width="1912" height="935" alt="image" src="https://github.com/user-attachments/assets/f74fd994-e915-42d8-8940-a175a3503182" />


  ##Dashboard-1
  <img width="1656" height="875" alt="image" src="https://github.com/user-attachments/assets/47a02c68-9dfe-42e2-9b50-645c7900a311" />


  ##Dashboard-2
  <img width="1600" height="867" alt="image" src="https://github.com/user-attachments/assets/8038b00d-4e25-4e85-aef4-770a7142db1b" />


  ##Dashboard-3
  <img width="1601" height="865" alt="image" src="https://github.com/user-attachments/assets/53f9f5ae-c916-4515-82aa-d804314ec00b" />

  ##Relationship
  <img width="1312" height="737" alt="image" src="https://github.com/user-attachments/assets/b74246d5-5b81-4b97-979a-6be7fe3e182a" />


  



  
