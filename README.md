🏥 Healthcare Analytics Dashboard | Power BI Project

📌 Project Overview:

This is an end-to-end Healthcare Analytics project built using Power BI, Power Query, and DAX to analyse hospital operational performance, patient trends, and financial metrics.
The dashboard is designed to help hospital management monitor key performance indicators and identify operational inefficiencies.

🎯 Business Objectives:

Analyse patient admission trends over time
Monitor average length of stay (LOS)
Evaluate readmission rates
Assess department-level risk & efficiency
Compare revenue by payment type
Evaluate doctor-level performance

🛠 Tools & Technologies Used:

Power BI Desktop
Power Query (Data Cleaning & Transformation)
DAX (Advanced Measures & Time Intelligence)
Star Schema Data Modeling

🧠 Data Modeling:

The project follows a Star/Snowflake schema approach:
Fact Tables:
Fact_Admissions
Fact_Billing
Dimension Tables:
Dim_Patient
Dim_Doctor
Dim_Department
Dim_Date
Key modeling practices:
Removed ambiguous relationships
Established proper one-to-many relationships
Marked Date table for time intelligence

📊 Key DAX Measures Implemented:

Total Admissions
Total Revenue
Average Length of Stay (Days)
Readmission Rate %
Admissions YoY %
Department Revenue
Risk classification using conditional logic
Top N doctor performance ranking

Advanced DAX functions used:
CALCULATE
AVERAGEX
RANKX
SAMEPERIODLASTYEAR
DIVIDE
IF

📈 Dashboard Highlights:

Executive Overview
KPI cards (Admissions, Revenue, LOS, Readmission Rate)
Monthly admission trend analysis
Revenue distribution by payment type
Department performance comparison
Key insights summary
Doctor & Department Analysis
Risk & Efficiency Matrix (Scatter Plot)
Top 5 doctors by admissions
Conditional formatting for readmission risk
Revenue breakdown by payment status

🔎 Key Insights:

Readmission rate indicates potential quality improvement areas
Certain departments show higher average length of stay
Insurance contributes majority revenue share
Doctor performance varies significantly across departments


