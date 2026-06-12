# Corporate Performance Analytics & Retail Operational Hub

## Overview
This project delivers an enterprise-grade Business Intelligence solution engineered in Microsoft Power BI. It transforms raw commercial transactions, regional distribution records, product lineups, customer tiers, and operational return datasets into actionable executive insights. The primary objective is to provide comprehensive data modeling and multi-dimensional analysis that empower stakeholders to evaluate velocity of revenue, customer lifetime touchpoints, logistics friction points, and gross profit dynamics.

## Dataset
The repository utilizes a centralized data warehousing structure modeled after a structured Star Schema, consisting of the following core data elements:
* **Sales_Fact**: Houses transactional granular data including invoice keys, item quantities, nominal revenue amounts, and applied customer discounts.
* **Returns_Fact**: Tracks point-of-sale reversals, operational return mappings, and specific reason codes like "Damaged", "Wrong Item", or "Not Needed".
* **Customer_Dim**: Contains demographic classifications such as customer full names, explicit age brackets, gender mapping, and premium status tiering (Gold, Silver, Platinum).
* **Product_Dim**: Stores operational item parameters including SKU descriptions, general categories (Electronics, Furniture, Clothing), sub-categories, and manufacturer brand identifiers.
* **Region_Dim**: Contains geographical entities detailing distribution networks, country boundaries, state designations, and regional branch cities.
* **Date_Dim**: Forms the temporal backbone of the analytical engine, containing continuous calendar mappings, custom month-year splits, quarter breakdowns, and unique Fiscal Year identifiers.

## Features

### 1. Data Cleaning & Transformation
* Developed robust extract-transform-load (ETL) routines inside Power Query Editor to isolate, cleanse, and eliminate null attributes or syntax discrepancies.
* Standardized date metrics, schema datatypes, key value relations, and customer identity strings across isolated transactional inputs.
* Engineered custom transformation columns to preserve transactional integrity and prevent logical calculation failures.

### 2. Data Modeling
* Designed and executed an optimized **Star Schema Architecture** within the Power BI relationship layer.
* Implemented strict One-to-Many ($1:\infty$) unidirectional logical relationships connecting the centralized fact entities (`Sales_Fact` and `Returns_Fact`) with supporting structural dimension definitions (`Customer_Dim`, `Product_Dim`, `Region_Dim`, `Date_Dim`).

### 3. Analytics
* Created structural metrics using customized Data Analysis Expressions (DAX) to diagnose business velocity.
* Analyzed average transaction size, net sales volumes, profit thresholds, and return frequencies to facilitate precise financial and asset auditing.

### 4. Visualization
* Rendered executive interactive dashboards using native key performance indicators (KPI) cards, categorical breakdown charts, and geo-spatial analytics maps.
* Implemented advanced matrix charts, trend timelines, and contextual tooltips to deliver cross-functional filtering and dynamic business auditing capabilities.

## Program Flow
[Raw Data Files (CSVs)]
│
▼ (Power Query Editor)
[Data Import & Cleansing] ──► (Null Removal, Data Type Formatting)
│
▼ (Power BI Relationship View)
[Data Modeling (Star Schema)] ──► (Connecting Fact & Dimension Tables)
│
▼ (DAX Measures)
[Advanced Analytics] ──► (Sales, Profit & Return Rate Calculations)
│
▼ (Report View)
[Visualization & Dashboards] ──► (Interactive Elements & Filters)


## Concept Used
* **Star Schema Modeling:** Facilitates efficient database indexing, sub-second visual query execution, and cleaner measure compilation.
* **DAX (Data Analysis Expressions):** Deployed for contextual evaluation, filter propagation overriding, and scalar calculations.
* **Time Intelligence:** Enables fiscal year comparison, seasonal trend mapping, and monthly commercial trajectory assessment.
* **Customer Segmentation:** Drives micro-targeting insights by examining transactional trends across consumer loyalty classifications.

## How to Use
1. **Prerequisites:** Ensure Microsoft Power BI Desktop (latest release) is fully configured on your workstation.
2. **Launch Application:** Download and access the consolidated `data.pbix` binary profile using Power BI Desktop.
3. **Data Refresh:** To update internal parameters against newer iterations of file imports, locate the Home ribbon and select the `Refresh` utility button.
4. **Interactive Discovery:** Utilize the canvas-level slicers (such as Year, Category, or Region) to manipulate data intersections and prompt instant visualization re-calculations.

## Formula

The analytical platform runs on the following explicitly defined DAX measures:

```dax
Average Sale per Transaction = 
DIVIDE(
    SUM(Sales[Total Sale Amount]),
    DISTINCTCOUNT(Sales[SalesID]),
    0
)



Return Rate = 
DIVIDE(
    CALCULATE(COUNT(Sales[SalesID]), Sales[ReturnFlag] = "Return"),
    COUNT(Sales[SalesID]),
    0
)


Total Cost = SUM(Sales[Cost])


Total Profit = [Total Sales] - [Total Cost]


Total Sales = SUM(Sales[Total Sale Amount])


```

## Files Included
- Power BI (.pbix)
- Dataset files
- Screenshots
- Project Report

## Deshboard.png

<img width="1378" height="771" alt="Deshboard" src="https://github.com/user-attachments/assets/abd6e184-b0e2-430a-8a77-f1b411e16b7b" /><br><br>


## Relationship.png

<img width="1465" height="795" alt="Relationship" src="https://github.com/user-attachments/assets/86242e8a-b74c-4088-b6e5-fe8c25c1c487" /><br><br>


## Sales.png

<img width="1918" height="955" alt="Sales" src="https://github.com/user-attachments/assets/c017527b-0349-4c23-97d7-fea81f606df3" /><br><br>


## Return.png

<img width="1916" height="952" alt="Return" src="https://github.com/user-attachments/assets/1185f13f-1a35-4ddd-880f-dba30408c7b0" /><br><br>


## Customer.png

<img width="1917" height="957" alt="Customer" src="https://github.com/user-attachments/assets/c221697e-298d-4aeb-baf4-d4beaa23aadb" /> <br><br>


## Product.png

<img width="1917" height="971" alt="Product" src="https://github.com/user-attachments/assets/665dcbdd-2c49-4153-bb78-e91888d08111" /><br><br>


## Region.png

<img width="1918" height="972" alt="Region" src="https://github.com/user-attachments/assets/d807dabc-cea7-434c-b314-c6803fb34863" /><br><br>


## Date.png

<img width="1918" height="947" alt="Date" src="https://github.com/user-attachments/assets/6b4086ac-1c8d-4f26-a36d-49a5ea202211" />






