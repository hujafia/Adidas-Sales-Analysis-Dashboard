# Adidas Sales Performance Analysis | Power BI Dashboard

An interactive Power BI dashboard built to analyze Adidas sales performance, profitability, product trends, retailer contributions, and regional sales distribution.

## Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Tools and Technologies](#tools-and-technologies)
- [Methods](#methods)
- [Key Insights](#key-insights)
- [Dashboard Features](#dashboard-features)
- [How to Run This Project](#how-to-run-this-project)
- [Results and Conclusion](#results-and-conclusion)
- [Future Work](#future-work)
- [Author and Contact](#author-and-contact)

---

## Project Overview

Sales data becomes valuable when it helps answer real business questions. In this project, I used Power BI to transform Adidas sales records into an interactive dashboard that makes business performance easier to explore and understand.

The dashboard brings together key performance indicators, monthly sales trends, product comparisons, retailer performance, regional analysis, and geographical sales distribution.

The goal was to build a clear and practical reporting solution that presents important sales metrics in one place and supports data-driven decision-making.

## Problem Statement

Analyzing large sales datasets manually can make it difficult to identify trends, compare performance, and understand which areas contribute most to business results.


This project addresses the following business questions:

- What are the total sales, operating profit, and units sold?
- How does sales performance change throughout the year?
- Which product categories generate the highest sales?
- Which retailers contribute the most to total sales?
- How do sales vary across regions and states?
- What are the average price per unit and average profit margin?
- How can interactive reporting make sales analysis easier?
  
## Dashboard Preview

![Adidas Sales Performance Dashboard](images/adidas-sales-dashboard.png)

## Dataset

The project uses an Adidas sales dataset containing transaction dates, retailer details, product categories, geographical information, and sales-related metrics.

### Dataset Fields

| Column | Description |
|---|---|
| Retailer | Name of the retailer |
| Retailer ID | Retailer identifier |
| Invoice Date | Date of the transaction |
| Region | Sales region |
| State | State where the sale occurred |
| City | City where the sale occurred |
| Product | Adidas product category |
| Price per Unit | Selling price per unit |
| Units Sold | Number of units sold |
| Operating Profit | Operating profit generated |
| Operating Margin | Operating margin percentage |
| Sales Method | Sales channel, such as In-store or Outlet |

## Tools and Technologies

- **Power BI Desktop** — Dashboard development and interactive reporting
- **Power Query** — Data cleaning and transformation
- **DAX** — KPI calculations and analytical measures
- **Data Modeling** — Organizing data for analysis
- **Data Visualization** — Presenting trends and comparisons
- **GitHub** — Project documentation and portfolio management

## Methods

### Data Preparation

Imported the dataset into Power BI and explored its structure to understand the available fields and business metrics.

### Data Cleaning and Transformation

Used Power Query to review data types, prepare date and numeric columns, and check data consistency before analysis.

### Data Analysis

Analyzed sales, profit, units sold, product categories, retailer contributions, monthly trends, and geographical performance.

### DAX Measures

Developed measures to calculate key performance indicators, including total sales, total profit, units sold, average price per unit, and average profit margin.

### Dashboard Development

Created interactive visualizations using KPI cards, a monthly sales trend chart, a regional doughnut chart, product and retailer comparison charts, and a state-level map.

### Interactive Reporting

Added year and region filters to allow users to explore sales performance across different reporting periods and locations.

## Key Insights

The following figures are based on the dashboard displayed in this project.

| KPI | Result |
|---|---:|
| Total Sales | $899.90M |
| Total Profit | $332.13M |
| Units Sold | 18M |
| Average Price per Unit | $45.22 |
| Average Profit Margin | 42.30% |

### Product Performance

Men's Street Footwear is the leading product category in the displayed chart, generating approximately $209M in sales.

### Retailer Performance

West Gear records the highest sales among the retailers displayed, with approximately $243M.

### Monthly Sales Trends

The monthly trend visualization shows fluctuations in sales throughout the year, with July and August demonstrating strong performance in the displayed results.

### Regional Performance

The dashboard compares sales contributions across West, Northeast, Southeast, South, and Midwest.

### Geographical Distribution

The state-level map provides a visual overview of sales distribution across the United States, helping users compare performance across locations.

*These observations reflect the displayed dashboard and may change when year or region filters are applied.*

## Dashboard Features

- **KPI Cards:** Total sales, total profit, units sold, average price per unit, and average profit margin.
- **Monthly Sales Trends:** Monthly performance analysis.
- **Sales by Region:** Comparison of regional sales contributions.
- **Sales by Product:** Identification of leading product categories.
- **Sales by Retailer:** Comparison of retailer performance.
- **Sales by State:** Geographical sales distribution.
- **Year Filter:** Analysis of 2020 and 2021.
- **Region Filter:** Interactive regional exploration.

## How to Run This Project

- Clone or download this GitHub repository.
- Install Power BI Desktop.
- Open the `.pbix` dashboard file included in the repository.
- Update the data source path if necessary.
- Refresh the dataset.
- Use the year and region filters to explore the dashboard.

**Note:** The dashboard file and dataset must be included in the repository, or their download locations must be provided, for other users to reproduce the project.

## Results and Conclusion

This project demonstrates how Power BI can transform raw sales data into an interactive business intelligence solution.

By combining data preparation, DAX calculations, KPI tracking, and data visualization, I developed a dashboard that makes it easier to monitor sales performance and compare results across products, retailers, months, regions, and states.

Working on this project helped demonstrate practical skills in data analytics, business intelligence, dashboard development, and analytical storytelling.

The project also highlights the value of presenting business information through clear, interactive visualizations rather than relying only on raw tables.

## Future Work

There are several opportunities to extend this project:

- Add year-over-year sales and profit growth analysis.
- Develop sales forecasting using historical data.
- Create drill-through pages for detailed product and retailer analysis.
- Introduce advanced profitability metrics.
- Add more detailed product and regional comparisons.
- Implement automated data refresh where supported.

These improvements could provide deeper insights and make the dashboard more useful for ongoing sales performance monitoring.

## Author and Contact

**MD Hujaifa**

Data Analyst | Power BI | SQL | Python | Excel

**Brand:** Hujaifa Data Lab

- LinkedIn: [Add your LinkedIn profile URL](https://www.linkedin.com/in/mdhujaifa/)
- GitHub: [Add your GitHub profile URL]([https://github.com/](https://github.com/hujafia))

I am passionate about data analytics, business intelligence, and building practical solutions that turn data into meaningful insights.

If you find this project useful, feel free to explore the repository and share your feedback.
