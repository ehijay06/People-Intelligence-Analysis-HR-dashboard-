# People-Intelligence-Analysis-HR-dashboard
## OVERVIEW
This project presents an end-to-end HR Analytics Dashboard built in Power BI to analyze workforce trends, employee performance, compensation, and retention.

The goal of this analysis is to provide actionable insights that help organizations:
- Improve employee retention
- Identify top-performing talent
- Monitor workforce distribution across locations
- Optimize compensation strategies
## OBJECTIVES
- Analyze attrition and active workforce trends
- Evaluate employee performance distribution
- Assess salary structure and disparities
- Understand department and location workforce mix
- Track year-over-year (YoY) changes in key HR metrics
## KEY METRICS
The dashboard tracks the following metrics:
- Active Rate (%)
- Attrition Rate (%)
- Average Salary
- Total Salary (Compensation Spend)
- New Hires
- Top Performer Rate
- Needs Improvement Rate
- Headcount

## BUSINESS IMPACT
This dashboard enables HR teams to:
- Identify high-risk attrition areas early
- Make data-driven compensation decisions
- Improve workforce planning across locations
- Monitor employee performance trends effectively
Each KPI is enhanced with Year-over-Year (YoY) comparison to show trends over time.
## KEY INSIGHTS
- The Sales department recorded the highest attrition rate, suggesting retention challenges
- Employees with tenure below 2 years showed significantly higher exit rates
- Lagos has the highest salary concentration across all locations

## DATA MODEL (STAR SCHEMA) 
- DIM_Department   |
- DIM_Location     |
- DIM_Performance  | ───► FACT_Employee ◄── DIM_Date
- DIM_Status       |
- DIM_Employee     |

## TOOLS AND TECHNOLOGIES USED
- Power BI — Data visualization and dashboard creation
- DAX (Data Analysis Expressions) — Calculations and KPIs
- Microsoft Excel — Data storage and preprocessing

## PROJECT FILES
- Dataset (Excel): [Download Dataset](https://github.com/ehijay06/People-Intelligence-Analysis-HR-dashboard-//blob/main/Raw&cleaned.xlsx)
- Star Schema: [Download Dataset](https://github.com/ehijay06/People-Intelligence-Analysis-HR-dashboard-//blob/main/hr_star_schema.xlsx)
- Dashboard: [Download PBIX](https://github.com/ehijay06/People-Intelligence-Analysis-HR-dashboard-//blob/main/Peopleintelligence.pbix)

## DASHBOARD
### 📊 Dashboard Features
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
# 
<img width="1290" height="731" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/f9b8c076-48d7-44d0-825e-5a10e65795cf" />


<img width="1288" height="737" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/27d4be0b-33a5-4137-b36d-6114d049ce67" />



## HOW TO USE
- Download the dataset and PBIX file
- Open the .pbix file in Power BI Desktop
- Interact with slicers (Year, Department, Location) to explore insights

## 👤 AUTHOR
## Nosa-Jeffery
Data Analyst | Power BI Developer

### Skilled in:
- Data Analysis (DAX, Excel)
- Data Visualization (Power BI)
- Dashboard Design & Storytelling
