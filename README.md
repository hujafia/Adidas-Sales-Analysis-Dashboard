# Adidas Sales Performance Analysis | Power BI Dashboard

An interactive Power BI dashboard built to analyze Adidas sales performance, profitability, product trends, retailer performance, and regional sales distribution.

## Table of Contents

- [Project Overview](#project-overview)
- [Dashboard Preview](#dashboard-preview)
- [Business Problem](#business-problem)
- [Dataset Description](#dataset-description)
- [Tools and Technologies](#tools-and-technologies)
- [Project Methodology](#project-methodology)
- [Key Business Insights](#key-business-insights)
- [Dashboard Features](#dashboard-features)
- [DAX Measures](#dax-measures)
- [How to Run the Project](#how-to-run-the-project)
- [Results and Conclusion](#results-and-conclusion)
- [Future Improvements](#future-improvements)
- [Author and Contact](#author-and-contact)

## Project Overview

Sales data can reveal valuable business insights, but identifying meaningful patterns in raw data is not always easy. This project transforms Adidas sales data into an interactive dashboard that makes business performance easier to understand.

Using Power BI, I developed a dashboard to monitor key performance indicators, analyze monthly sales trends, compare product and retailer performance, and explore sales across different regions and states.

The objective is to turn raw sales data into meaningful insights that support better business decisions.

## Dashboard Preview

![Adidas Sales Performance Dashboard](images/adidas-sales-dashboard.png)

## Business Problem

Businesses need to understand their sales performance, profitability, and product trends to make informed decisions.

This project explores the following business questions:

- What are the total sales, profit, and units sold?
- How does sales performance change throughout the year?
- Which product categories generate the highest sales?
- Which retailers contribute the most to total sales?
- Which regions and states perform best?
- What are the average price per unit and profit margin?

## Dataset Description

The dataset contains Adidas sales records with retailer information, product categories, invoice dates, geographical details, and sales metrics.

| Column | Description |
|---|---|
| Retailer | Name of the retailer |
| Retailer ID | Unique retailer identifier |
| Invoice Date | Date of the transaction |
| Region | Sales region |
| State | State where the sale occurred |
| City | City where the sale occurred |
| Product | Adidas product category |
| Price per Unit | Price of each unit |
| Units Sold | Number of units sold |
| Operating Profit | Profit generated from sales |
| Operating Margin | Operating profit margin |
| Sales Method | Sales channel |

### Dataset Preview

![Adidas Sales Dataset](images/adidas-dataset-preview.png)

## Tools and Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data Visualization
- GitHub

## Project Methodology

### Data Preparation
Imported and explored the dataset to understand its structure and identify the fields required for analysis.

### Data Cleaning and Transformation
Used Power Query to prepare the data, validate column data types, and check date and numeric fields.

### Data Analysis
Analyzed sales, profit, units sold, product performance, retailer contributions, and regional distribution.

### DAX Calculations
Created measures to calculate key performance indicators and support interactive reporting.

### Dashboard Development
Designed an interactive dashboard using KPI cards, line charts, bar charts, a doughnut chart, and a geographical map.

### Interactive Reporting
Added year and region filters to enable dynamic exploration of sales performance.

## Key Business Insights

The following figures are based on the dashboard displayed in this project.

| KPI | Result |
|---|---:|
| Total Sales | $899.90M |
| Total Profit | $332.13M |
| Units Sold | 18M |
| Average Price per Unit | $45.22 |
| Average Profit Margin | 42.30% |

### Product Performance
Men's Street Footwear leads the displayed product categories, with approximately $209M in sales.

### Retailer Performance
West Gear records the highest sales among the retailers shown, with approximately $243M.

### Monthly Sales Trends
July and August show strong sales performance in the displayed monthly trend chart.

### Regional Analysis
The dashboard compares sales contributions across West, Northeast, Southeast, South, and Midwest.

### Geographical Analysis
The state-level map provides a visual overview of sales distribution across the United States.

*Results may vary depending on the selected year and region filters.*

## Dashboard Features

- Executive KPI cards
- Monthly sales trend analysis
- Sales by region
- Sales by product category
- Sales by retailer
- State-wise sales map
- Interactive year filter
- Interactive region filter

## DAX Measures

The following are example DAX measures for the analysis. Replace `Sales` with your actual table name if necessary.

### Total Sales

```dax
Total Sales =
SUMX(
    Sales,
    Sales[Price per Unit] * Sales[Units Sold]
)
