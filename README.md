HR Analytics – Employee Attrition

📌 Project Overview

This project analyzes workforce data to understand employee attrition patterns and identify the key drivers behind employee turnover.
The objective is to transform raw HR data into actionable business insights that help organizations improve employee retention and workforce planning.

The analysis combines Excel-based data engineering with Power BI dashboards to deliver an executive-ready HR analytics solution.

🎯 Business Objectives

Measure overall employee attrition rate

Identify departments and roles with high turnover risk

Analyze workload, overtime, and satisfaction as attrition drivers

Detect demographic and tenure-based flight-risk patterns

Provide data-driven HR strategy recommendations

📂 Dataset Description

Total records: 10,000 employees

Each record represents an individual employee profile

Key Attributes:

Demographics: Age, Gender, Marital Status, Distance from Home

Employment Details: Department, Job Role, Years at Company, Overtime

Performance & Sentiment: Job Satisfaction, Work-Life Balance, Project Count

Target Variable: Attrition (Yes / No) 

HR Analytics – Employee Attriti…

🛠 Tools & Technologies Used

Excel – Data preprocessing & feature engineering

Power BI – Dashboarding & interactive visual analytics

🧹 Data Preprocessing & Feature Engineering (Excel)

Key data engineering steps performed before Power BI import:

Converted Attrition (Yes/No) into binary values (1/0) for KPI calculations

Created Age Groups using binning to analyze generational turnover trends

Translated numerical ratings (1–4) into labels:

Poor, Average, Good, Excellent

Standardized Monthly Income into currency format for financial accuracy

Removed text noise using trimming logic to ensure clean filtering

Audited null values and replaced missing categories with “Unknown”

Deduplicated employee records to avoid inflated attrition counts

Engineered Tenure Aging to analyze exit timing patterns

These steps ensured a clean, reliable dataset ready for analytics 

HR Analytics – Employee Attriti…

.

📊 Key KPIs (Executive Summary)

Total Employees: 10,000

Attrition Count: 1,997

Attrition Rate: 19.97%

These KPIs provide a high-level view of workforce health and retention risk 

HR Analytics – Employee Attriti…

.

🔍 Key Analysis & Insights
🔥 Workload & Burnout Analysis

Attrition remains stable for employees handling 2–5 projects

Attrition rate spikes sharply beyond 6 projects

Employees with 7+ projects show ~35–38% attrition

Indicates a clear burnout tipping point 

HR Analytics – Employee Attriti…

⏱ Overtime Impact

Employees working overtime show significantly higher attrition

The effect is strongest in IT and Sales departments

Overtime is identified as a primary attrition driver, not salary alone 

HR Analytics – Employee Attriti…

🏢 Department-Level Risk

Sales and IT departments have the highest turnover

R&D department shows strong retention and stability

Highlights uneven workload and cultural differences across departments 

HR Analytics – Employee Attriti…

👥 Demographic Insights

Highest attrition observed in the 30–39 age group

Indicates a mid-career retention challenge

Early-career employees (20–29) also show early churn, linked to onboarding gaps 

HR Analytics – Employee Attriti…

🧠 Job Role & Satisfaction Matrix

Certain roles in IT and Sales show high attrition even at medium satisfaction

Heatmap analysis helps identify hidden risk zones

Enables targeted HR interventions rather than generic policies 

HR Analytics – Employee Attriti…

⏳ Tenure-Based Exit Patterns

Major attrition spike around 2 years of tenure

Secondary spike within the first 6 months

Suggests issues in career growth clarity and onboarding alignment 

HR Analytics – Employee Attriti…

🎛 Interactive Dashboard Features (Power BI)

Marital Status slicer

Overtime filter (key burnout indicator)

Work-Life Balance slicer

Department, Age Group, and Project Count drill-downs

These slicers allow HR teams to perform root-cause analysis dynamically 

HR Analytics – Employee Attriti…

.

📈 Strategic Recommendations

Enforce a maximum cap of 5 projects per employee in high-pressure roles

Shift budget from overtime pay to headcount expansion

Introduce career milestone reviews at 18 months

Launch leadership fast-track programs for mid-career talent (30–39)

Improve onboarding experience to reduce early-stage attrition

These actions directly address the root causes identified in the analysis 

HR Analytics – Employee Attriti…

.

✅ Conclusion

This project demonstrates how structured data preprocessing and interactive dashboards can uncover hidden attrition risks and support data-driven HR decision-making.
It highlights the importance of workload balance, career progression, and employee well-being in retaining top talent.

📚 Learning Outcomes

Practical HR analytics using real-world data

Excel-based data engineering for analytics readiness

KPI design and business-focused storytelling

Power BI dashboarding and stakeholder-oriented insights
