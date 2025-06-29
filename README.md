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
- Which ship mode drives the highest revenue?
- Which customer segments drive the highest revenue?

---

## Dashboard Features

- 📌 KPI Indicators: Total Sales, Total Profit, Orders, Profit Ratio  
- 📍 Regional Performance: Sales and Profit by Region & State  
- 🛍️ Product Analysis: Top-performing Categories and Sub-categories  
- 📦 Shipping Analysis: Profit by Ship Mode  
- 👥 Customer Segmentation: Sales by Segment  
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

