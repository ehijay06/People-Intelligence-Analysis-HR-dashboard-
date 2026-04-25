# People-Intelligence-Analysis-HR-dashboard-
# OVERVIEW
A complete data analytics workflow built around a synthetic HR dataset of 493 employees across 8 departments and 8 global cities. The goal was to simulate a real-world scenario starting with unusable raw data and ending with a professional, interactive dashboard that answers actual business questions.
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
# TOOLS USED
MICROSOFT EXCEL-POWER BI DASHBOARD-POWER QUERRY-DAX
# PROJECT FILES
Dataset (Excel): [Download Dataset](https://github.com/ehijay06/People-Intelligence-Analysis-HR-dashboard-//blob/main/Raw&cleaned.xlsx)
Star Schema: [Download Dataset](https://github.com/ehijay06/People-Intelligence-Analysis-HR-dashboard-//blob/main/hr_star_schema.xlsx)
# DASHBOARD
## People Intelligence dashboard
<img width="1435" height="799" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/55a5be8d-ccf9-48c3-8ee2-f20c16b40c34" />
<img width="1126" height="637" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/8ed761fe-317b-4a05-8729-a5bc0385c438" />



