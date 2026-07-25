# Supply-Chain-Analytics-Dashboard
An interactive Power BI dashboard for analyzing Sales, Inventory, Product Performance, and Delivery Operations to support supply chain decision-making.
Project Overview

This project demonstrates an end-to-end Supply Chain Analytics solution developed using Python, Excel, and Microsoft Power BI. The objective was to transform raw supply chain data into actionable business insights by performing data cleaning, integration, analysis, and interactive dashboard development.

Instead of directly building the dashboard, the project followed a complete data analytics workflow starting from data preprocessing in Python to final visualization in Power BI.

Business Problem

Supply chain managers need a centralized dashboard to monitor:

Sales Performance
Inventory Levels
Product Performance
Delivery Operations
Profitability
Stock Availability

The goal of this project is to help decision-makers identify trends, monitor KPIs, reduce stock issues, and improve operational efficiency.

Project Workflow
Step 1: Data Collection

Collected two datasets:

Inventory Dataset
Sales Dataset

Both datasets contained different information and required integration before analysis.

Step 2: Data Cleaning using Python

Used Python (Pandas) to clean the datasets by:

Removing duplicate records
Handling missing values
Correcting data types
Renaming inconsistent columns
Standardizing values
Creating new calculated columns
Step 3: Data Integration using Python

Merged the Inventory and Sales datasets using Product ID to create one unified dataset for analysis.

The merged dataset contains information related to:

Product
Sales
Inventory
Shipping
Orders
Profit
Delivery
Stock
Step 4: Feature Engineering

Created additional business metrics using Python, including:

Inventory Value
Delivery Delay
Stock Gap
Reorder Required
Inventory Status
Inventory Health Indicators
Step 5: Data Validation in Excel

Before importing into Power BI, the cleaned data was validated using Microsoft Excel.

Tasks performed:

Cross-checking totals
Data verification
Identifying inconsistencies
Basic data analysis
Ensuring data accuracy
Step 6: Data Modeling in Power BI

Imported the cleaned dataset into Power BI and created:

Relationships
Data Model
DAX Measures
KPIs
Step 7: DAX Measures

Developed several business measures including:

Total Sales
Total Profit
Total Orders
Quantity Sold
Inventory Value
Current Inventory
Average Order Value
Average Lead Time
Average Shipping Days
Average Delivery Delay
Reorder Required
On-Time Delivery %
Profit Margin %
Highest Selling Product
Lowest Selling Product
Highest Profit Product
Low Stock Products
Dashboard Pages
1. Executive Dashboard

Provides a high-level overview of business performance.

KPIs:

Total Sales
Total Profit
Total Orders
Quantity Sold
Inventory Value
Current Inventory

Visuals:

Monthly Sales Trend
Sales by Market
Profit by Market
2. Sales Analysis

Focuses on revenue and customer behavior.

Visuals:

Sales by Category
Sales by Product
Sales by Region
Customer Segment Analysis
Monthly Sales & Profit Trend
3. Inventory Analysis

Monitors inventory health and stock availability.

KPIs:

Current Inventory
Inventory Value
Reorder Required
Low Stock Products
Average Lead Time

Visuals:

Inventory Value by Category
Current Stock vs Reorder Point
Stock Status Distribution
Reorder Analysis
4. Delivery & Logistics Dashboard

Analyzes delivery efficiency.

KPIs:

Average Delivery Delay
Average Shipping Days
Total Orders
On-Time Delivery %

Visuals:

Delivery Status
Shipping Mode Analysis
Delivery Delay by Market
Actual vs Scheduled Shipping Days
5. Product & Profitability Dashboard

Analyzes product performance and profitability.

KPIs:

Highest Selling Product
Lowest Selling Product
Highest Profit Product
Average Order Value
Profit Margin %

Visuals:

Top Products
Profit Margin by Category
Average Profit per Order
Product Performance Table
Tools & Technologies
Tool	Purpose
Python	Data Cleaning, Merging, Feature Engineering
Pandas	Data Manipulation
Microsoft Excel	Data Validation & Verification
Microsoft Power BI	Dashboard Development
Power Query	Data Transformation
DAX	KPIs & Business Measures
Skills Demonstrated
Data Cleaning
Data Integration
Feature Engineering
Data Validation
Exploratory Data Analysis
Data Modeling
DAX
Power Query
KPI Development
Dashboard Design
Business Intelligence
Supply Chain Analytics
Inventory Analysis
Sales Analytics
Data Visualization
Key Business Insights
Monitored overall sales and profitability.
Identified high-performing and low-performing products.
Tracked inventory levels and reorder requirements.
Evaluated delivery performance across different markets.
Measured customer purchasing behavior.
Analyzed profit margins across product categories.
Improved supply chain visibility through interactive dashboards.
