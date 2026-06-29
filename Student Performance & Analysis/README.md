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
![Star Schema](images/student_star_schema.png)

---

## 📋 Project Tables & Transformations

### Students Table
![Students Table](images/students_table.png)

### Attendance Table
![Attendance Table](images/attendance_table.png)

### Behavior Table
![Behavior Table](images/behavior_table.png)

### Scores Table
![Scores Table](images/scores_table.png)

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
![DAX Formulas](images/student_dax_formulas.png)

---

# 📄 Dashboard Pages

## 1️⃣ Executive Overview Dashboard
Provides a high-level summary of student performance.  
![Executive Overview](images/student_exec_dashboard.png)


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
