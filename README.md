sa# HR Analytics Project

## 📌 Project Overview
This project demonstrates **end-to-end HR Analytics** by integrating data between Python, MySQL, and Power BI.  
The objective is to analyze HR data to understand **workforce composition, attendance & leave patterns, and the hiring funnel**, and to present actionable insights through dashboards.  

---
## 📌 Business Problem
The HR team of a mid-sized organization (~100 employees) is facing challenges in:
- Tracking overall **employee headcount, active workforce, and distribution**
- Understanding **employee tenure patterns** for retention insights
- Monitoring **attendance trends** (absenteeism, sick leave, work-from-home)
- Evaluating **hiring funnel performance** (stage-wise dropouts & conversions)
- Measuring the **effectiveness of recruitment sources** (referrals, job portals, career fairs)

## 🎯 Project Objectives
This project was carried out to:
- Provide **real-time workforce visibility** through interactive dashboards
- Identify **attendance and absenteeism trends** across departments
- Analyze **attrition risks & tenure distribution**
- Optimize the **recruitment funnel** by highlighting bottlenecks and dropout reasons
- Enable **data-driven HR decision-making** for workforce planning & hiring strategies
  
## 🛠️ Tools & Technologies
- **Python** → Imported raw data into MySQL, automated loading  
- **MySQL** → Data profiling, querying, and transformation using SQL  
  - Used **CASE statements** for conditional analysis  
  - Applied **CTEs** (Common Table Expressions) for complex queries  
  - Performed **aggregate functions** (SUM, AVG, COUNT, etc.) for metrics  
- **Power BI** → Built interactive dashboards for visual insights  

## ⚙️ Tech Stack  

The dashboard was built using the following tools and technologies:  

- **Power BI Desktop** → Main data visualization platform used for creating the report.  
- **Power Query** → Data transformation and cleaning layer for reshaping and preparing raw data.  
- **DAX (Data Analysis Expressions)** → Used for calculated measures, dynamic visuals, and conditional logic.  
- **Data Modeling** → Relationships established among tables (e.g., sales, customers, products) to enable cross-functional insights.  
- **Bookmarks** → Implemented to enable dynamic navigation and visibility (e.g., switching between different dashboard views such as *Product Analysis* or *Geographical Analysis*).  
- **File Formats** → `.pbix` (development file) and `.png` (dashboard preview images).  

---

## 📊 Key Analyses
- **Workforce Composition** → Employee distribution by department, role, gender, and salary  
- **Attendance & Leave Analysis** → Trends in leaves, absenteeism, and productivity  
- **Hiring Funnel** → Applicants → Interviews → Offers → Joinees  

---

## 📂 Project Workflow
1. **Data Import** → Loaded HR dataset into MySQL using Python scripts  
2. **Data Profiling** → Explored data quality and structure  
3. **SQL Queries** → Performed analysis using CASE, CTEs, and aggregate functions  
4. **Data Visualization** → Connected database to Power BI and built dashboards  

---

## 📸 Dashboard Samples
* OverAll View -- https://github.com/gracytriyar/HR-Analytics/blob/main/HR%20Overview.png 

---

## 🚀 How to Run
1. Clone this repository  
2. Import the dataset into MySQL using the Python script provided  
3. Run SQL scripts for analysis  
4. Open the `.pbix` file in Power BI to view dashboards  

---

## 📈 Results
- Clear picture of workforce distribution and demographics  
- Attendance insights that highlight leave trends  
- End-to-end hiring funnel performance with conversion ratios  

---

## 🤝 Contributions
Contributions and suggestions are welcome! Fork the repo and submit a PR.
