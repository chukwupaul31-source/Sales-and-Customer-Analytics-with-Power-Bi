# 📊 Sales and Customer Analytics Using Power BI

## 📌Project Overview

This project focuses on analyzing sales and customer data to uncover key insights into business performance, customer behavior, and regional sales trends. The goal of the project was to transform raw transactional data into actionable business intelligence using Microsoft Power BI.
The analysis provides a holistic view of sales performance, profitability, customer churn, and product trends, empowering decision-makers to identify growth opportunities, improve retention, and optimize sales strategies.
The Power BI solution was designed as a two-part dashboard system — one focused on Sales Performance, and the other on Customer and Logistics Analytics.


## Dashboard
<img width="637" height="338" alt="power bi" src="https://github.com/user-attachments/assets/81a96f5c-2da3-4825-94d4-d3f2e20e8d40" />

This dashboard highlights the core financial and operational KPIs of the business. It offers an at-a-glance summary of sales performance and profitability across different regions and product categories.

## Dashboard 2: Customer and Logistics Analytics Dashboard
<img width="632" height="335" alt="POWERBI" src="https://github.com/user-attachments/assets/f5493f64-d573-4ab7-9558-4845e17fb19f" />
The second dashboard focuses on understanding customer behavior, churn patterns, and logistics performance to help the company improve customer retention and optimize delivery strategies.


## ⚠️Problem Statement

Businesses often face challenges in monitoring sales performance, understanding customer behavior, and identifying areas for improvement. This project aims to address these questions:

1. What are the major drivers of total sales and profit across regions and product categories?

2. Which regions and customer segments contribute the most to overall performance?

3. What factors influence customer churn, and how can retention be improved?

4. How do logistics and returns impact profitability?




## 🧱Data Structure

The dataset contains detailed information on sales transactions, customer profiles, products, and logistics. Key fields include:

- Sales Data: Order ID, Sales, Profit, Quantity, Discount, Category, Subcategory

- Customer Data: Customer ID, Customer Name, Region, Country, City

- Logistics Data: Ship Mode, Order Date, Ship Date, Delivery Time

- Churn Data: Customer Status (Active or Churned), Customer Lifetime Value

- A relational data model was built in Power BI, connecting all these tables to allow seamless cross-analysis.

## ✨Key Features

- Core Business KPIs: Displays Total Sales, Total Orders, Total Profit, and Profit Margin — providing a snapshot of overall business performance.

- Regional Sales Analysis: A bar chart visual shows total orders by region, helping identify top-performing geographical areas.

- Profitability Overview: A gauge chart tracks Total Profit to visualize whether the business is meeting its profit targets.

- Category Analysis: Charts show total orders and sales by product category to determine the most profitable product lines.

- Trend Analysis: A line chart visualizes sales over time to track year-over-year growth and seasonality.

## 🛠️Methodology

The entire analysis was conducted in Power BI, leveraging its data modeling and visualization capabilities.

- Data Cleaning and Preparation

- Imported raw data into Power BI using Power Query Editor.

- Cleaned and transformed data by removing duplicates, correcting data types, and handling missing values.


### Data Modeling

- Established relationships between tables (Sales, Customers, Products, Regions) to ensure accurate filtering and aggregation across dashboards.


### DAX Calculations

- Created custom DAX measures such as Total Sales, Total Profit, Profit Margin, Total Orders, Customer Lifetime Value, and Churned Customers for precise KPI tracking.


### Data Visualization and Dashboard Design

- Designed interactive dashboards using Power BI visuals such as bar charts, maps, gauges, and line graphs.

- Added slicers for dynamic filtering by region, category, and customer status.

- Ensured a clear, user-friendly design for effective storytelling and business decision-making.


## 📈Key Insights and Findings

1. Regional Performance: Certain regions consistently outperform others in total sales and profit, indicating strong market potential and customer base concentration.

2. ustomer Churn: Geographic analysis revealed cities and regions with higher churn rates, signaling areas needing customer relationship improvements.

3. Product Category Trends: Specific product categories drive a significant portion of total sales, highlighting areas for inventory and marketing focus.

4. Profitability Patterns: Profit margins vary across regions and categories, suggesting opportunities for pricing or cost-optimization strategies.

5. Logistics Impact: Delivery time and return frequency influence customer satisfaction and churn rates.



## 💡Recommendations

 - Strategic Regional Focus: Allocate more resources to high-performing regions and investigate reasons behind underperformance in low-sales areas.

- Churn Reduction Strategy: Identify and address customer pain points in high-churn locations to improve retention rates.

- Product Optimization: Prioritize top-performing product categories for marketing and stock availability to maximize sales potential.

- Logistics Efficiency: Streamline shipping and returns processes to improve delivery times and reduce costs.

- Customer Engagement: Introduce loyalty programs and targeted marketing campaigns to increase repeat purchases and lifetime value.

- Data-Driven Monitoring: Regularly update and review Power BI dashboards to track KPIs and adapt strategies proactively.

By leveraging Power BI for this analysis, the project successfully transformed raw sales and customer data into a comprehensive business intelligence solution. This allows stakeholders to make informed, data-driven decisions that enhance profitability, customer satisfaction, and long-term business growth.
