# Power BI Superstore Analytics Dashboard

This project creates an end-to-end analytics dashboard using the sample Superstore dataset in Power BI Desktop. The dashboard addresses specific business questions with clean, data-driven visualizations using effective storytelling techniques and conditional formatting.

## Project Overview

This dashboard analyzes retail performance data from the Superstore dataset, focusing on sales performance, profitability, and return rates. The dashboard includes various visualizations designed to answer specific business questions.

## Business Questions Addressed

1. Display key metrics: sales, profit, percentage of returned orders with percentage change vs previous year
2. Compare sales performance versus previous year over time
3. Determine the most profitable products and most loss-making products
5. Show sales distribution by customer segment

## Technical Implementation

### Data Preparation
- Imported Superstore dataset (orders and returns tables)
- Used Power Query to clean and transform data
- Kept only necessary columns to optimize the model

### Data Modeling
- Created relationships between order and returns tables
- Built a custom date table using DAX functions
- Added calculated measures in a dedicated measure table

### Key DAX Measures Created
- Sales: `SUM(orders[Sales])`
- Profit: `SUM(orders[Profit])`
- Percentage of Returned Orders
- Previous Year (PY) measures
- Year-over-year percentage change calculations

### Visualizations
- KPI cards with conditional formatting
- Line chart comparing sales performance over time
- Bar chart showing profit by product categories
- Donut chart for sales by segment



## Techniques Used

- Data transformation and cleaning
- Data modeling with relationships
- Creating calculated measures and tables
- Applying conditional formatting
- Creating clean, clutter-free visualizations

## Setup Instructions

1. Download the Superstore sample dataset (provided in project files)
2. Open Power BI Desktop
3. Import the dataset and follow transformation steps
4. Create data model relationships
5. Add calculated measures
6. Build visualizations

## Screenshots

![WhatsApp Image 2025-04-22 at 21 46 30_cfa349ba](https://github.com/user-attachments/assets/b1c3eeef-ce79-41d6-94d5-754a968555b6)



