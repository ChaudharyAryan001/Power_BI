# 📊 Student Performance & Analysis Dashboard

## 🎯 Project Overview
The Student Performance & Analysis Dashboard is an end-to-end Power BI project designed to transform raw student data (attendance, behavior, and exam scores) into actionable academic insights.

This project demonstrates the complete Business Intelligence workflow, including:
- Data Cleaning & Transformation using Power Query
- Star Schema Data Modeling
- Relationship Management
- DAX Measures & Calculated Columns
- Time Intelligence Analysis
- Attendance & Behavior Monitoring
- Academic Performance Evaluation
- Interactive Dashboard Design

---

## 🛠 Tools & Technologies Used
- Power BI Desktop  
- Power Query  
- DAX (Data Analysis Expressions)  
- Star Schema Modeling  
- Data Visualization  
- Time Intelligence Functions  

---

## 📂 Data Model Architecture
A Star Schema model was implemented to improve performance and simplify analytical reporting.

### Fact Tables
- **Scores_Fact**
- **Attendance_Fact**
- **Behavior_Fact**

### Dimension Tables
- **Students_Dim**
- **Date_Dim**

---

## ⭐ Star Schema Design
The data model follows a centralized fact table structure connected to multiple dimension tables.

### Model Benefits
- Faster query performance  
- Better scalability  
- Simplified relationships  
- Efficient DAX calculations  

### Screenshot
<img width="1152" height="835" alt="Relationship" src="https://github.com/user-attachments/assets/aa840d9b-4b0b-4af4-aca3-b20137bcb034" /><br><br>


---

## 📋 Project Tables & Transformations

### Students Table
<img width="1916" height="952" alt="student " src="https://github.com/user-attachments/assets/fd488656-cb0f-4a83-97da-fa6af285d95d" /><br><br>


### Attendance Table
<img width="1917" height="966" alt="Attendance" src="https://github.com/user-attachments/assets/24fe94a8-004f-4a9d-859c-948e15749a35" /><br><br>


### Behavior Table
<img width="1907" height="947" alt="Behavior" src="https://github.com/user-attachments/assets/2e79ddda-0126-4c04-9e07-9156753a9cc4" /><br><br>


### Scores Table
<img width="1917" height="947" alt="Scores" src="https://github.com/user-attachments/assets/18d73c93-2d71-4b52-93ea-a08acd46c21d" /><br><br>

---

## 📈 DAX Calculations Implemented

### Measures
- Total Students  
- Average Score per Subject  
- Pass Rate %  
- Student Rank  
- Max Subject Score  
- Behavior Count  
- Attendance Status Count  

### Time Intelligence Functions
- TOTALYTD()  
- TOTALMTD()  
- SAMEPERIODLASTYEAR()  

### Calculated Columns
- Year  
- Month Name  
- Quarter  
- Attendance Reason Classification  
- Behavior Category  

### Screenshot
<img width="605" height="871" alt="dax formulas all" src="https://github.com/user-attachments/assets/2552646a-6951-41d3-91cf-1a4963f4b2ad" /><br><br>


---

# 📄 Dashboard Pages

## 1️⃣ Executive Overview Dashboard
Provides a high-level summary of student performance.  
<img width="1172" height="852" alt="deshboard" src="https://github.com/user-attachments/assets/b7d212fe-210f-47d8-8e60-87864321e5b5" /><br><br>



---

## 🔍 Key Insights Generated
- Average score per subject: **54.32**  
- Overall pass rate: **80%**  
- Behavior records: **300+ entries** with majority being **Good/Helpful**.  
- Attendance analysis shows **Family Function, Sick Leave, Transportation Issues** as top absence reasons.  
- Gender distribution: **56% Male, 44% Female**.  
- Identified top-performing students and subjects.  
- Applied Time Intelligence functions for performance tracking.  

---

## 🚀 Skills Demonstrated
- **Power Query** → Data Cleaning, Transformation, Preparation  
- **Data Modeling** → Star Schema, Relationship Management  
- **DAX** → Measures, Calculated Columns, Time Intelligence  
- **Visualization** → KPI Cards, Donut Charts, Treemaps, Waterfall Charts, Decomposition Trees  
- **Business Intelligence** → Attendance Analytics, Behavior Monitoring, Academic Performance Analysis  

---

## 📌 Project Outcome
This dashboard transforms raw student data into meaningful academic intelligence, enabling data-driven decision making through interactive reporting, advanced DAX calculations, and professional dashboard design.
-Aryan 
