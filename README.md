# Portfolio

### Project 1: Sales Performance Analysis for a Retail Store

### Project Overview
---
Objective: Analyze the sales performance of a retail store to uncover insights such as top-selling products, regional performance, and monthly sales trends. The final output is an interactive Power BI dashboard that visualizes these findings.

### Data Source 
---
The SalesData database is a collection of 50,000 records capturing transactional data for a retail store. Each record represents an individual order and contains information relevant to sales performance analysis. The database includes the following fields:

- OrderID: A unique identifier for each transaction, allowing for precise tracking of orders.
- Customer Id: An ID for the customer placing the order, useful for customer segmentation and behavior analysis.
- Product: The type of product purchased, such as apparel items like shirts, shoes, hats, and jackets, which enables product-level performance insights.
- Region: The geographical region (North, South, East, West) where the sale was made, supporting regional performance analysis.
- OrderDate: The date the order was placed, allowing for time-based analysis such as monthly trends and seasonal patterns.
- Quantity: The number of units of the product ordered, helping to measure demand
- UnitPrice: The price per unit of each product, which, in combination with quantity, determines revenue.
- Total sales: The calculated total revenue for each order (Quantity × UnitPrice), a critical metric for overall sales performance.
- Average sales: A field meant to represent average sales value but is mostly empty and may need cleaning or further calculation.

This dataset is well-suited for analyzing sales performance across different products, regions, and time periods, and provides a foundation for creating dashboards and visualizations to identify high-performing areas, top-selling products, and trends over time.

### Tools used
---

- Microsoft Excel
  1. For Data Cleaning
  2. For Analysis
  3. For Visualization

- SQL - Structured Query Language
- PowerBI
- Github

### Data Cleaning and preparation
---
Process used:
- In Excel, perform initial data exploration and clean the dataset by removing duplicates, handling missing values, and formatting columns.
- In SQL, load the data into a SQL Server environment and validate it, ensuring no null values in key fields.

Key Steps:
- Remove duplicates.
- Format date fields.
- Filter out records with null values in crucial fields.
### Exploratory Data Analysis
---
Excel Analysis:
- Use pivot tables to summarize sales by product, region, and month.
- Calculate metrics such as total revenue by region and average sales per product.
- Create basic visualizations (e.g., bar charts, line charts) to identify trends in the data.

### Data Analysis
---
![Annotation 2024-11-05 111809](https://github.com/user-attachments/assets/196d55e8-0445-48c2-8cdc-ce19e3b9bcc6)

![Annotation 2024-11-05 111739](https://github.com/user-attachments/assets/274d0d87-89b9-40cc-b1c3-96ef77034dcc)

### Data Visualization
---
### Recommendation
---
