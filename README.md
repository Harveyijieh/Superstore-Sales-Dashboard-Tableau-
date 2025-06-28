
# HR Data Analysis

### Project Overview 
This project aims to analyse HR data using PostgreSQL for querying and Tableau for visualisation. The goal is to uncover insights related to employee attrition and workforce distribution. The analysis will help organizations make data-driven decisions to improve employee retention and satisfaction.

### Project Objectives

- Understand employee demographics and workforce distribution

- Determine attrition rates and key influencing factors

- Create visual representations of findings using Tableau

### Data Source
The dataset used for this project consists of 1,470 employee records and contains various HR attributes. 
The data was sourced from a popular HR analytics dataset, which includes information on employee demographics, job roles, education, attrition, and others.

### Tools
- Excel - for exploring the dataset

- Postgres - for querying and data analysis [Download here](https://www.postgresql.org/)

- Tableau - for visualisation and interactive dashboards [Download here](https://www.tableau.com/products/public/download)

- GitHub - for version control and project sharing [Sign Up](https://github.com/)

### Findings 

- Attrition Rate: The overall attrition rate in the dataset is approximately 16%.

- Department-Wise Attrition: The Sales and R&D departments have the highest attrition rates.

- Age Factor: Younger employees (below 30) show higher attrition compared to older employees.

These insights help HR teams focus on retention strategies by improving job satisfaction, adjusting travel policies, and addressing department-specific concerns.

### SQL Queries and Insights
#### Employee Gender Distribution
```sql
SELECT 
    gender, COUNT(*) AS employees
FROM 
    hrdata
GROUP BY gender
ORDER BY employees;
```
#### Attrition By Department

```sql
SELECT department, 
       COUNT(*) AS total_employees, 
       ROUND(COUNT(CASE WHEN attrition ilike 'Yes' THEN 1 END) * 100.0 / COUNT(*),2) AS attrition_rate
FROM
    hrdata
GROUP BY department
ORDER BY attrition_rate DESC;
```

### Visualisation in Tableau
For the data visualization aspect of this project, I utilized Tableau. Tableau was used to create interactive and insightful visualizations that helped to better understand and analyze the HR data. Below is the dashbaord created using Tableau:
- [View Dashboard](https://public.tableau.com/app/profile/harvey.ijieh/viz/HRAnalyticsUpload/HRDASHBOARD)
### Conclusions

This project helps analyze HR data, identify attrition factors, and visualize workforce trends using PostgreSQL and Tableau.

💻

--- 


# Superstore-Sales-Dashboard-Tableau-
Superstore data analysis
🛍️ Superstore Sales Dashboard (Tableau Project)
📈 Turning Retail Data into Actionable Insights

Welcome to my Tableau visualization project built on the classic Superstore dataset — a powerful showcase of how data analytics can help businesses identify growth opportunities, optimize sales strategies, and understand customer behavior.

This repository contains all documentation, insights, and assets used in building the dashboard. The live dashboard is available on Tableau Public.
🗂️ Table of Contents

    🎯 Project Objectives

    🔍 Business Questions

    👤 User Personas

    📊 Dashboard Features

    📈 Key Insights

    📁 Dataset Information

    🛠️ Tools & Skills Used

    🖼️ Dashboard Preview

    🚀 Next Steps & Enhancements

    📬 Connect With Me

🎯 Project Objectives

    Create an interactive Tableau dashboard that delivers sales insights in a clear and engaging format.

    Enable stakeholders to explore trends across categories, regions, segments, and time.

    Demonstrate skills in data analysis, storytelling, and dashboard design.

🔍 Business Questions

This project seeks to answer key questions relevant to retail decision-makers:

    What regions and states drive the most profit or incur losses?

    Which product categories and sub-categories perform best?

    How does the customer segment affect sales and profitability?

    What impact does discounting have on overall profit margins?

    Are certain shipping methods more cost-effective?

👤 User Personas

    Sales Managers – monitor sales by region, category, and time period.

    Executives – track overall business performance via high-level KPIs.

    Marketing Teams – understand customer segments for targeting.

    Operations – evaluate shipping methods and fulfillment efficiency.

📊 Dashboard Features

✅ Dynamic Filters: View insights by Region, Category, Sub-category, and Time
✅ Key KPIs: Sales, Profit, Orders, Profit Ratio
✅ Regional Analysis: Map views showing profit/sales by state
✅ Trend Charts: Time-series line graphs for Sales & Profit
✅ Customer Segments: Sales distribution across segments
✅ Shipping Analysis: Compare shipping modes by sales and profit
✅ Drill-Downs: Zoom into underperforming products or states
📈 Key Insights

Some of the interesting findings include:

    📉 The Central region shows strong sales but low profitability due to heavy discounting.

    🛒 Technology category yields the highest profit margin despite fewer sales.

    ⚠️ Tables sub-category consistently results in negative profit across regions.

    🚚 Standard Class is the most used shipping mode but is not always the most profitable.

    These insights can help companies focus their efforts on profitable segments, optimize inventory, and review discount policies.

📁 Dataset Information

    Dataset: Superstore Sample Data (included in Tableau desktop)

    Time Range: 2015–2018

    Records: ~10,000+ rows

    Variables: Order Date, Product, Customer, Category, Sales, Profit, Discount, Region, Segment, Ship Mode

🛠️ Tools & Skills Used
Tool	Purpose
Tableau	Dashboard creation & data viz
Excel	Initial data exploration
GitHub	Documentation, version control
Storytelling	Insight communication
Analytical Thinking	Business insight generation
🖼️ Dashboard Preview

🔗 View Live Dashboard on Tableau Public


Interactive filters, drill-down analysis, and insightful KPIs in one place.
🚀 Next Steps & Enhancements

    Add forecasting models for sales using Tableau or Python integration.

    Segment customers using RFM analysis for deeper CRM insights.

    Build SQL version of this project using a database like PostgreSQL.

    Create a Power BI version for cross-platform comparison.

📬 Connect With Me

👨‍💻 Harvey Ijieh
Data Analyst | Business Intelligence | Tableau | SQL
🔗 LinkedIn
📧 Email Me
🌍 Portfolio
