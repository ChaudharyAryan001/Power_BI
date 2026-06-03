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

## Files Included
- Power BI (.pbix)
- Dataset files
- Screenshots
- Project Report
- Data Cleaning Steps
  

##Sales.Png
<img width="1918" height="1117" alt="sales" src="https://github.com/user-attachments/assets/9b2411e5-1d63-4405-903b-215e0a49b0f7" />


##Employee.Png
<img width="1917" height="1150" alt="image" src="https://github.com/user-attachments/assets/afb175d1-e826-49ec-9137-a1cad22867c3" />


##Sales_by_Region.Png
<img width="1918" height="1140" alt="image" src="https://github.com/user-attachments/assets/50dea546-d5ed-4779-9701-49c75f4a8d1b" />


##Reltionship
<img width="1168" height="831" alt="Relationship" src="https://github.com/user-attachments/assets/5274c0f2-b3fc-477a-9447-156292c2885f" />


##Sales Data Cleaning Steps <br>
<img width="364" height="1024" alt="Sales_Data_Applied Steps" src="https://github.com/user-attachments/assets/4b24a236-3518-41a3-b53e-8471eba86fe3" />


##Employee Data Cleaning Steps <br>
<img width="327" height="545" alt="Employee_Data - Applied_Steps" src="https://github.com/user-attachments/assets/a73be599-d0d4-4cbe-b28e-d03604a11f28" />


##Sales_by_Region Data Cleaning Steps <br>
<img width="332" height="405" alt="Sales_By_Region - Applied Steps" src="https://github.com/user-attachments/assets/e001edf8-00b2-4457-9a98-681261d98608" />
