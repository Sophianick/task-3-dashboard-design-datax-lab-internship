# Task 3: Dashboard Design – Global Superstore Sales Analysis

![Dashboard Preview](Task3%20dashboard.png)

## Overview
This project was completed as part of the **DataX Lab Internship – Task 3**. The objective was to design an interactive Power BI dashboard that enables business stakeholders to monitor sales performance and make data-driven decisions.

## Tools Used
- Microsoft Power BI
- Power Query
- DAX
- Microsoft PowerPoint

## Dataset
- **Dataset:** Global Superstore Dataset
- **Source:** Kaggle

## Data Cleaning
The following data preparation steps were carried out using Power Query:
- Removed duplicate records.
- Checked for missing values.
- Removed the **Postal Code** column due to null values and because it was not required for the analysis.
- Retained negative profit values as they represent legitimate business losses.
- Created a Date Table to support time-based analysis.
- Created DAX measures for key performance indicators.

## Dashboard Features
The dashboard includes:
- KPI Cards
  - Total Revenue
  - Total Profit
  - Total Orders
  - Profit Margin
- Monthly Revenue Trend
- Revenue by Category
- Profit by Region
- Orders by Customer Segment
- Top 10 Products by Revenue
- Interactive slicers (Year, Market, Region, Category, Segment)

## Key Insights
- Total Revenue reached **$12.64M**.
- Total Profit was **$1.47M** with a **Profit Margin of 11.6%**.
- Revenue peaked during **September, November, and December**.
- The **Central Region** generated the highest profit.
- **Technology** was the highest revenue-generating product category.
- The **Consumer** segment recorded the highest customer patronage.
- **Apple Smart Phone** generated the highest revenue among all products.

## Repository Contents
- `Dashboard.pbix` – Power BI dashboard
- `Global_Superstore.csv` – Dataset
- `Task_3_Dashboard_Summary_Presentation.pptx` – Project summary
- `Dashboard_Screenshot.png` – Dashboard preview
- `README.md`

## Outcome
This project strengthened my skills in:
- Data cleaning with Power Query
- Data modeling and DAX
- Interactive dashboard design
- Business intelligence and data storytelling
- Creating dashboards that support business decision-making
