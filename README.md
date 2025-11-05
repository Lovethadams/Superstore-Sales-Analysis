# Superstore-Sales-Analysis

A complete Excel-based analysis of the Superstore dataset including data cleaning, pivot analysis, and interactive dashboard visualization with actionable business insights.


## Table of Contents
- [Project Overview](#project-overview)
- [Tools & Technologies](#tools--technologies)
- [Dataset Overview](#dataset-overview)
- [Data Cleaning](#data-cleaning)
- [Exploratory Analysis](#exploratory-analysis)
- [KPIs](#kpis)
- [Charts](#charts)
- [Design Overview](#design-overview)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Dashboard Preview](#dashboard-preview)
- [Pivot Table Samples](#pivot-table-samples)
- [Project Files](#project-files)


---

## Project Overview
This project analyzes sales performance using the **Superstore Sales Dataset**.  
The goal was to uncover trends in sales, profit, and customer behavior, and visualize the findings through an interactive Excel dashboard.

The analysis highlights how regional performance, product categories, and order volumes impact overall profitability.

---

## Tools & Technologies

- Microsoft Excel
- Pivot Tables
- Charts (Line, Bar, Column)
- Basic Excel Formulas
- Dashboard Design using Shapes and Formatting


---

#### Dataset Overview

The dataset used for this project is the **Superstore Sales Dataset**, which contains records of sales transactions made by a retail store.  

It includes key business fields such as **Order Date, Ship Date, Product Category, Sub-Category, Sales, Quantity, Profit, Customer Name, Region, and Segment**.  
Each record represents an order placed by a customer, showing how sales and profits vary across regions, categories, and segments.  

**Key Columns:**
- **Order Date** – Date when the order was placed.  
- **Ship Date** – Date the order was shipped.  
- **Region** – The geographical area of the sale (East, West, Central, South).  
- **Category / Sub-Category** – Product classification (e.g., Furniture → Chairs, Tables).  
- **Sales** – Revenue from the order.  
- **Profit** – Net profit from the order.  
- **Quantity** – Number of units sold.  
- **Segment** – Type of customer (Consumer, Corporate, Home Office).  
- **Customer Name** – The buyer's name.  
- **Ship Mode** – Shipping method used.

This dataset provides a solid foundation for analyzing **sales performance, profitability, customer behavior, and regional trends**.


---
## Data Cleaning

Performed several cleaning and transformation steps to make the dataset analysis-ready:

- Removed duplicates and blank rows.  
- Standardized column headers for consistency.  
- Calculated **Shipping Days** = Ship Date – Order Date to measure delivery efficiency.  
- Created a **Region Manager** column by mapping each region to its assigned manager from the People table.  
- Verified data types for numerical columns such as **Sales**, **Profit**, and **Quantity**.  
- Calculated additional measures such as **Profit Margin** to support KPI analysis.  
- Ensured all date fields were correctly formatted for time-based analysis (e.g., extracting month and year for trend insights).


---

##  Exploratory Analysis

The dataset was explored using Pivot Tables to uncover sales and profitability trends across different dimensions.

**Analyses Conducted:**
- Sales and Profit by Category  
- Sales and Profit by Sub-Category  
- Region Analysis  
- Sales and Profit by Segment  
- Sales and Profit by Ship Mode  
- Top 10 Customers by Sales  
- Monthly Sales Trend  
- Sales, Profit, and Segment Relationship  
- Profit by Region and Segment  
- Quantity Sold by Category  

These analyses formed the foundation for the dashboard design.

---

###  KPIs
- Total Sales  
- Total Profit  
- Quantity Sold  
- Average Order Value (AOV)  
- Profit Margin (%)  

###  Charts
1. Customer by Sales  
2. Monthly Sales Trend  
3. Sales and Profit by Region  
4. Sales and Profit by Category  

---

##  Design Overview
A clean and simple dashboard layout was used, **KPIs positioned at the top** for quick performance overview, followed by charts showing **monthly trends** and **category-level insights**.  
The design emphasizes **clarity, readability, and data storytelling**, keeping visuals consistent and easy to interpret.



---

## Key Insights
- The **West Region** generated the highest sales and profit overall.  
- **Technology** category outperformed others in both revenue and profit margin.  
- **December** and **November** recorded the highest sales, indicating strong end-of-year demand.  
- Some categories had high sales but low profit, suggesting potential discounting or cost inefficiency.

---

## Recommendations
- Focus marketing and inventory on top-performing regions and categories.  
- Investigate low-profit but high-sales items to improve pricing strategy.  
- Optimize shipping time to enhance customer satisfaction and reduce delays.  
- Continue tracking performance monthly to spot emerging patterns early.

---

## Dashboard Preview

Below is the Excel dashboard created from the Superstore Sales Dataset.




<img width="986" height="692" alt="Screenshot (273)" src="https://github.com/user-attachments/assets/32aa9317-24cd-4bad-bf2d-23857cefeba1" />


###  Pivot Table Samples




<img width="1832" height="888" alt="Screenshot (293)" src="https://github.com/user-attachments/assets/3810feb5-0070-43fd-91f0-303bb0e198f6" />



---


### Project Files

You can download the complete Excel file used for this analysis below.  
It includes the cleaned dataset, Pivot Tables, charts, and dashboard.

[📂 **Superstore_Sales_Analysis.xlsx**][Excel-Superstore-Sales-Analysis.xlsx](https://github.com/user-attachments/files/23363287/Excel-Superstore-Sales-Analysis.xlsx)

