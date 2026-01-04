## Food-Delivery-Analytics-Dashboard

#### Project Overview

This project focuses on building an end-to-end Power BI analytics solution to analyze customer behavior, delivery performance, and restaurant efficiency for a food delivery business.
The dashboard is designed to support data-driven decision-making using interactive visuals, advanced DAX, and optimized data modeling.

#### 🎯Objective

- Analyze order trends and delivery performance

- Identify repeat and high-value customers

- Measure restaurant-level efficiency

- Track business growth using time-based metrics

#### 🗂 Dataset Structure
##### Fact Table

- Orders
- Order ID
- Order Date
- Customer ID
- Restaurant ID
- Food Item ID
- Quantity
- Delivery Status
- Payment Method

##### Dimension Tables

- Customers – Customer details & membership type
- Restaurants – Restaurant name & category
- Food Items – Food name & food type


Implemented Star Schema for optimal query performance and scalability.

#### 📊 Key KPIs & Metrics

- Total Orders
- Delivered Orders
- Month-to-Date (MTD) Orders
- Year-to-Date (YTD) Orders
- Month-over-Month (MoM) Growth %
- Repeat Customers
- Repeat Rate %
- Average Orders per Customer
- Delivery Performance Trends

#### ⚙️ Key Features

- Star Schema data modeling

- Advanced DAX measures using:
    - CALCULATE
    - RANKX
    - Time intelligence (MTD, YTD, MoM)
- Interactive slicers (Date, Restaurant, Customer Type)
- Drillthrough for detailed customer and restaurant analysis
- Optimized Power BI performance (reduced columns, efficient measures)

#### 📈 Insights Generated

- Identified high-value repeat customers contributing to major revenue share
- Analyzed monthly order growth patterns and seasonality
- Measured delivery efficiency across restaurants
- Highlighted top-performing restaurants and customer segments

#### 🛠 Tools & Technologies

- Power BI – Dashboard development & DAX
- Power Query – Data cleaning & transformation
- SQL concepts – Data modeling & relationships
- Excel – Initial data preparation

#### 🚀 Business Value

This dashboard helps stakeholders:
    - Improve customer retention strategies
    - Monitor delivery SLAs
    - Optimize restaurant partnerships
    - Make faster, data-backed business decisions

#### 📌 Future Enhancements
- Add churn prediction using Python
- Integrate real-time data using DirectQuery
- Implement Row-Level Security (RLS)
