# People-Intelligence-Analysis-HR-dashboard-
# OVERVIEW
This project presents an end-to-end HR Analytics Dashboard built in Power BI to analyze workforce trends, employee performance, compensation, and retention.

The goal of this analysis is to provide actionable insights that help organizations:
Improve employee retention
Identify top-performing talent
Monitor workforce distribution across locations
Optimize compensation strategies
# OBJECTIVES
Analyze attrition and active workforce trends
Evaluate employee performance distribution
Assess salary structure and disparities
Understand department and location workforce mix
Track year-over-year (YoY) changes in key HR metrics
# KEY METRICS
The dashboard tracks the following metrics:
Active Rate (%)
Attrition Rate (%)
Average Salary
Total Salary (Compensation Spend)
New Hires
Top Performer Rate
Needs Improvement Rate
Headcount

Each KPI is enhanced with Year-over-Year (YoY) comparison to show trends over time.
# KEY INSIGHTS
Departments with higher attrition rates indicate potential retention challenges
Employees with shorter tenure show a higher likelihood of leaving
Certain cities concentrate higher salary distributions
Workforce distribution varies significantly across departments and locations
Performance segmentation highlights both high-performing teams and areas needing improvement
# DATA SOURCE
The dataset was generated from scratch using Claude. It was intentionally messy to simulate real-world data quality problems. Every common issue was baked in: mixed date formats, salaries written as 85k / $85,000 / 8.5e+04, duplicate records, broken emails, inconsistent department names like HR, H.R, and human resources all in the same column, blank cells, and numbers stored as text.
Once generated, the dataset was cleaned entirely in Excel using TRIM(), PROPER(), DATEVALUE(), Find & Replace, and custom formulas to validate emails and standardize salary formats. 6 duplicate rows were removed, leaving 494 clean records.
[
# DATA MODEL (STAR SCHEMA) 
DIM_Department ──┐
DIM_Location   ──┤
DIM_Performance──┼──► FACT_Employee ◄── DIM_Date
DIM_Status     ──┤
DIM_Employee   ──┘

# TOOLS AND TECHNOLOGIES USED
Power BI — Data visualization and dashboard creation
DAX (Data Analysis Expressions) — Calculations and KPIs
Microsoft Excel — Data storage and preprocessing

# PROJECT FILES
Dataset (Excel): [Download Dataset](https://github.com/ehijay06/People-Intelligence-Analysis-HR-dashboard-//blob/main/Raw&cleaned.xlsx)
#
Star Schema: [Download Dataset](https://github.com/ehijay06/People-Intelligence-Analysis-HR-dashboard-//blob/main/hr_star_schema.xlsx)
#
Dashboard: [Download PBIX](https://github.com/ehijay06/People-Intelligence-Analysis-HR-dashboard-//blob/main/Peopleintelligence.pbix)

# DASHBOARD
## 📊 Dashboard Features
### 🔹 Workforce Overview
Active vs Attrition Rate
Headcount distribution
### 🔹 Compensation Analysis
Average Salary by Department and City
Salary range and distribution
### 🔹 Performance Analysis
Top Performers vs Needs Improvement
Performance trends over time
### 🔹 Geographic Insights
Employee distribution by city (Map visual)
Salary heatmap by location
### 🔹 Department & Location Breakdown
Department mix per city (Matrix view)
Office type distribution (Donut chart)

## DASHBOARD PREVIEW
<img width="1435" height="799" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/55a5be8d-ccf9-48c3-8ee2-f20c16b40c34" />
<img width="1126" height="637" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/8ed761fe-317b-4a05-8729-a5bc0385c438" />

# HOW TO USE
Download the dataset and PBIX file
Open the .pbix file in Power BI Desktop
Interact with slicers (Year, Department, Location) to explore insights

# 👤 AUTHOR
Nosa-Jeffery
Data Analyst | Power BI Developer


