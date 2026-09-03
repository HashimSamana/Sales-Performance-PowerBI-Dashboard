# Sales-Performance-PowerBI-Dashboard
A Power BI Sales Performance Dashboard project focused on data cleaning, visualization, KPI analysis, and business insights.
# Sales Performance Dashboard | Power BI
## Dashboard Preview

![Sales Performance Dashboard](Screenshots/Dashboard.png)

## Project Overview

This project is an interactive Sales Performance Dashboard developed using Microsoft Power BI. The dashboard transforms raw sales data into meaningful business insights by analyzing sales trends, profitability, product performance, and regional performance.

The objective of this project is to demonstrate data cleaning, data transformation, KPI development, and business intelligence reporting using Power BI.

---

## Objectives

- Analyze overall sales and profit performance
- Track monthly sales trends
- Identify top-performing products
- Compare category-wise performance
- Analyze regional sales distribution
- Create an interactive dashboard for business reporting

---

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Visualization

---

## Dataset Description

The dataset contains sales transaction records with the following information:

- Order ID
- Order Date
- Customer Name
- Region
- Segment
- Category
- Product Name
- Quantity
- Sales
- Discount
- Profit

---

## Data Preparation

Data preparation and cleaning were performed using Power Query.

Steps performed:

- Removed duplicate records
- Checked and handled missing values
- Changed data types
- Standardized date formats
- Prepared data model for analysis

---

## Dashboard Features

### Sales Overview

The dashboard includes key performance indicators:

- Total Sales
- Total Profit
- Total Orders
- Total Quantity Sold

### Sales Trend Analysis

- Monthly sales performance tracking
- Identification of sales patterns and fluctuations

### Product Analysis

- Top-selling products
- Product-wise sales comparison
- Performance analysis

### Category Analysis

- Sales comparison across different categories
- Profitability analysis

### Regional Analysis

- Region-wise sales distribution
- Comparison of performance across regions

### Interactive Filters

The dashboard includes slicers for:

- Region
- Category
- Segment

---

## DAX Measures Created

### Total Sales

```DAX
Total Sales =
SUM(Sales[Sales])
