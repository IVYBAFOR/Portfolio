# **Project 1: Sales Performance Analysis for a Retail Store**

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
**Excel**
![Annotation 2024-11-05 111809](https://github.com/user-attachments/assets/196d55e8-0445-48c2-8cdc-ce19e3b9bcc6)

![Annotation 2024-11-05 111739](https://github.com/user-attachments/assets/274d0d87-89b9-40cc-b1c3-96ef77034dcc)

**SQL**
![Annotation 2024-11-05 130002](https://github.com/user-attachments/assets/882f90d1-a84d-4577-9b6a-5429b120e060)

![Annotation 2024-11-05 125934](https://github.com/user-attachments/assets/7020bfa9-8c88-402c-a97d-ebc0e2052aeb)

![Annotation 2024-11-05 125906](https://github.com/user-attachments/assets/85fc09f5-2a4b-4f2a-9598-974b21b1688e)

![Annotation 2024-11-05 125843](https://github.com/user-attachments/assets/bd2a036a-5724-47a1-b958-1a114e3c8db7)



### Data Visualization
---
### Recommendation
---



# **Project 2: Customer Segmentation for a Subscription Service**

###  Project Overview
---
Objective: Analyze customer data for a subscription service to understand customer behavior, identify key trends in cancellations and renewals, and segment customers by subscription type and duration. The end goal is to deliver a Power BI dashboard that visualizes the insights.

### Data Source
---
The SalesData database is a collection of 50,000 records capturing transactional data for a retail store. Each record represents an individual order and contains information relevant to sales performance analysis. The database includes the following fields:
- CustomerID: A unique identifier for each customer, allowing tracking and segmentation of individual users.
- Region: The geographical location of the customer, useful for analyzing regional trends and preferences.
- SubscriptionType: The type of subscription each customer holds (e.g., Basic, Premium, Annual, Monthly), helping to identify the popularity of different subscription levels.
- StartDate: The date when the customer’s subscription began, allowing analysis of subscription longevity and retention.
- EndDate: The date when the subscription ended (or is blank if still active), which aids in tracking cancellations and active subscriptions.
- Revenue: The total revenue generated from each customer’s subscription, useful for calculating lifetime value and revenue by subscription type.

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
- In Excel, clean the data by removing duplicates, handling null values in key columns (e.g., Start Date, Subscription Type), and formatting dates.
- In SQL, load the data into a SQL Server environment for further analysis and validation.

Key Steps:
- Remove duplicates and format data types.
- Fill or drop rows with missing values in essential columns.
- Filter out records where the subscription data is inconsistent

### Exploratory Data Analysis
---
Excel Analysis:
- Use pivot tables to identify trends in subscription patterns by region and type.
- Calculate the average subscription duration and analyze which subscription types are the most popular.

### Data Analysis
---
**Excel**
![Annotation 2024-11-05 131303](https://github.com/user-attachments/assets/e54527bb-98c4-46d7-b8c5-ad87414d8513)

![Annotation 2024-11-05 131336](https://github.com/user-attachments/assets/71346305-e17a-43c5-8f6f-33723f186b7c)

**SQL**
![WhatsApp Image 2024-11-05 at 13 07 14](https://github.com/user-attachments/assets/3fc3c123-7f24-4c62-8bc1-51cd218f3204)

![WhatsApp Image 2024-11-05 at 13 07 14 (1)](https://github.com/user-attachments/assets/70f3bddf-b954-424d-b7c3-fb145bee1241)



### Data Visulaization 
---
### Recommendation
---
