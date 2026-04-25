# People-Intelligence-Analysis-HR-dashboard-
# OVERVIEW
A complete data analytics workflow built around a synthetic HR dataset of 493 employees across 8 departments and 8 global cities. The goal was to simulate a real-world scenario starting with unusable raw data and ending with a professional, interactive dashboard that answers actual business questions.
# DATA SOURCE
The dataset was generated from scratch using Python — intentionally messy to simulate real-world data quality problems. Every common issue was baked in: mixed date formats, salaries written as 85k / $85,000 / 8.5e+04, duplicate records, broken emails, inconsistent department names like HR, H.R, and human resources all in the same column, blank cells, and numbers stored as text.
Once generated, the dataset was cleaned entirely in Excel using TRIM(), PROPER(), DATEVALUE(), Find & Replace, and custom formulas to validate emails and standardize salary formats. 6 duplicate rows were removed, leaving 494 clean records.
# DATA MODEL (STAR SCHEMA) 
DIM_Department ──┐
DIM_Location   ──┤
DIM_Performance──┼──► FACT_Employee ◄── DIM_Date
DIM_Status     ──┤
DIM_Employee   ──┘
# TOOLS USED
MICROSOFT EXCEL-POWER BI DASHBOARD-POWER QUERRY-DAX
# DASHBOARD
[People Intelligence dashboard](<img width="1126" height="637" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/cdf98cc1-e7ec-4b22-b2ea-8e262e2da385" />
