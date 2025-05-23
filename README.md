# Retail Sales Dashboard

This Power BI project demonstrates a retail sales analytics dashboard built on a sample dataset. It highlights key sales metrics and trends for a fictional retail business, providing an interactive overview of performance. The dashboard is designed to help stakeholders quickly understand revenue drivers and customer distribution.

## Purpose

The purpose of this Retail Sales Dashboard is to provide insights into overall sales performance, trends over time, and customer distribution across product categories. It enables managers to track key performance indicators (KPIs) such as **Total Revenue** and **Customer Count**, identify sales trends by month, and analyze product-category and demographic (age group) breakdowns. By aggregating and visualizing these metrics, the dashboard supports data-driven decision-making for sales strategy and inventory planning.

## Data set

The dashboard is built using a **sample retail sales dataset** that mimics real-world transactional data. The dataset is self-contained and embedded within the Power BI report.

### Data set Overview

The dataset contains information about retail sales transactions across different months, products, and customer demographics. It is designed to support analysis of sales performance over time, product category performance, and customer segmentation.

### Key Columns in the Dataset:

| Column Name       | Description |
|-------------------|-------------|
| `Month`           | The month of the transaction (e.g., January, February). Used for time-series analysis. |
| `Product Category`| The type of product sold (e.g., Electronics, Clothing). Helps in comparing category-level sales. |
| `Age Group`       | The age segment of the customer (e.g., 18-25, 26-35). Useful for demographic insights. |
| `Customer ID`     | A unique identifier for each customer (anonymized). Used to count distinct customers. |
| `Revenue`         | The revenue generated from each transaction or customer group. A core metric used in KPI cards and charts. |

## Key Features

- **KPI Cards:** Highlights total revenue and customer count.
- **Sales Trend Analysis:** Combo and line charts visualize monthly revenue across product categories.
- **Demographics & Categories:** Pie charts show customer distribution by product category and age group.
- **Revenue Table:** Monthly sales figures listed for detailed analysis.
- **Month Slicer:** Enables filtering by month across the entire dashboard.

## Tools and Technologies

- Power BI Desktop
- Sample Retail Dataset
- DAX for Measures
- Power BI Visualizations (Cards, Charts, Tables, Slicer)

## How to View

Open the `Retail Sales Dashboard.pbix` file using Power BI Desktop to explore the interactive dashboard.

> 📁 This project is a part of my data analytics portfolio to showcase skills in Power BI, data visualization, and retail business insights.
