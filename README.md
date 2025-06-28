# 🛍️ Superstore Sales Dashboard - Tableau Project

### 📈 Turning Retail Data into Actionable Insights

Welcome to my data visualization project using the popular **Superstore dataset**. This project showcases how Tableau can be used to extract meaningful business insights and drive better retail decisions through compelling visuals and analytics.

🔗 **Live Dashboard on Tableau Public:** [View Dashboard](https://public.tableau.com/your_dashboard_link)

---

## 🗂️ Table of Contents

- [Project Objectives](#project-objectives)
- [Business Questions](#business-questions)
- [Dashboard Features](#dashboard-features)
- [Key Insights](#key-insights)
- [Dataset Overview](#dataset-overview)
- [Tools & Skills Used](#tools--skills-used)
- [Dashboard Preview](#dashboard-preview)
- [Next Steps](#next-steps)
- [Connect with Me](#connect-with-me)

---

## Project Objectives

- Build an interactive dashboard that explores Superstore’s performance across multiple dimensions: region, category, customer segments, and time.
- Demonstrate skills in business analytics, data storytelling, and visualization design using Tableau.
- Help stakeholders understand key drivers of profitability, identify problem areas, and optimize decisions.

---

## Business Questions

- Which regions and states are the most profitable?
- What product categories contribute most to sales and profit?
- How do discount and shipping mode impact profitability?
- Which customer segments drive the highest revenue?

---

## Dashboard Features

- 📌 KPI Indicators: Total Sales, Total Profit, Orders, Profit Ratio  
- 📍 Regional Performance: Sales and Profit by Region & State  
- 🛍️ Product Analysis: Top-performing Categories and Sub-categories  
- 📦 Shipping Analysis: Profit by Ship Mode  
- 👥 Customer Segmentation: Sales by Segment  
- 📅 Sales Trends: Monthly trend lines for sales and profit  
- 🎛️ Filters: Interactive controls for Region, Category, and Date  

---

## Key Insights

- 📉 **Tables** sub-category consistently underperforms with low or negative profit.  
- 🌎 **West region** is a top performer in both sales and profit.  
- 🛒 **Technology** category, while not the highest in sales, delivers strong profitability.  
- 🚚 Excessive discounts often lead to reduced profit margins despite higher sales.

---

## Dataset Overview

- **Source:** Tableau Sample Superstore Dataset  
- **Size:** ~10,000 records  
- **Fields:** Order ID, Product, Category, Region, Sales, Profit, Customer Segment, Ship Mode, etc.  
- **Time Range:** 2015 – 2018  

---

## Tools & Skills Used

| Tool         | Purpose                            |
|--------------|------------------------------------|
| Tableau      | Data Visualization & Dashboard     |
| Excel        | Initial Data Exploration           |
| GitHub       | Version Control & Documentation    |
| Analytical Thinking | Business Insight Generation |

---

## Dashboard Preview

![Superstore Dashboard Preview](images/superstore_dashboard_preview.png)

🔗 **Explore the interactive version**: [View on Tableau Public](https://public.tableau.com/your_dashboard_link)

---

## Next Steps

- Add forecast models for monthly sales using Tableau forecasting tools  
- Segment customers using RFM (Recency, Frequency, Monetary) analysis  
- Build similar dashboards using Power BI and SQL for comparison  

---

## Connect with Me

**Harvey Ijieh**  
_Data Analyst | Business Intelligence | Tableau | SQL_  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)  
📧 [Email Me](mailto:your-email@example.com)

---

⭐️ If you found this project helpful or inspiring, feel free to give it a star and share!




---
# ANALYST AT WORK

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
