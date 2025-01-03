# E-Commerce Sales Dashboard

## Overview

This project presents an E-Commerce Sales Dashboard designed to help online businesses analyze and visualize sales data. The dashboard provides insights into sales trends based on various product categories, regions, and months, along with profitability analysis. It allows users to interactively select product categories and view sales data accordingly.

## Objective

The objective of this project is to develop an interactive dashboard for an online E-commerce company. The dashboard is designed to track and display sales data across various product categories, with a user control panel for selecting product categories. Users can explore the sales trends, profitability, and shipping costs over time, segmented by different regions and product types.

## Dataset Description

The dataset used for this project includes detailed orders and sales data for various product categories. The dataset is represented in an Excel file, `E-Commerce Sales Dashboard.xlsx`, which contains the following fields:

- **Order ID**: Unique identifier for each product order.
- **Order Date**: The date the order was placed.
- **Ship Date**: The date the order was shipped.
- **Aging**: Used to create histogram bins for shipping duration analysis.
- **Ship Mode**: The shipping mode of the order (e.g., Standard, Express).
- **Product Category**: The category of the product (e.g., Electronics, Home & Furniture).
- **Product Name**: Name of the product.
- **Sales**: Sales amount for the product.
- **Quantity**: The number of items ordered.
- **Discount**: Discount applied to the product price.
- **Profit**: Profit earned from the sale.
- **Shipping Cost**: The cost incurred for shipping the order.
- **Order Priority**: The priority level of the order (e.g., Low, Medium, High).
- **Customer ID**: Unique identifier for the customer.
- **Customer Name**: Name of the customer.
- **Segment**: Customer segment (e.g., Corporate, Consumer).
- **City, State, Country, Region**: Geographic information related to the customer.
- **Months**: The month the order was placed.

## Analysis Tasks

### 1. Histogram Analysis

A histogram is created to analyze the number of shipping days (Aging), showing how long it takes to deliver orders. This helps identify bottlenecks in the shipping process.

### 2. Monthly and Region-wise Sales and Profit

Sales and profit tables are created for each month and region. Pivot tables link the sales data to user controls, allowing for dynamic updates based on user selections.

### 3. Combo Box for Product Category

A combo box control is implemented to allow users to select a product category. The data and charts update dynamically based on the selected category.

### 4. Column Charts for Sales and Profit

Sales and profit data are displayed in column charts, grouped by month and region. These charts help in identifying trends and areas for improvement.

### 5. Dashboard Creation

A comprehensive dashboard is created that aggregates and visualizes the most important metrics, such as total sales, profit, and shipping costs, across product categories and regions.

## Features

- **Dynamic Data Visualization**: Users can interact with the dashboard by selecting different product categories and viewing corresponding sales and profit trends.
- **Monthly and Regional Insights**: The dashboard allows businesses to explore sales data month-wise and region-wise to uncover important patterns.
- **Profitability Analysis**: A detailed analysis of sales profit over time and across various segments is provided.
- **Shipping Analysis**: Shipping times are analyzed with a histogram, providing insights into the shipping efficiency of the business.

## Installation and Usage

1. Download the dataset file `E-Commerce Sales Dashboard.xlsx` and ensure it is in the same directory as the dashboard workbook.
2. Open the Excel file and enable macros to use the interactive elements, such as combo boxes and linked tables.
3. Select the desired product category from the combo box to view updated sales data.
4. Use the monthly and region-based sales charts to analyze trends.

## Files Included

- **E-Commerce Sales Dashboard.xlsx**: The main Excel file containing the dataset, pivot tables, and dashboard.
- **E-Sales Working Explanation.pdf**: A detailed explanation of the steps taken to build the dashboard, including formulas, chart creation, and data analysis methods.

## Technologies Used

- **Microsoft Excel**: For data analysis, pivot tables, and dashboard creation.
- **Excel Macros and VBA**: For creating user controls like combo boxes and dynamic data updates.
- **Data Visualization**: Charts and graphs to present the sales data visually.

## License

This project is provided under the MIT License. Feel free to use, modify, and distribute it as needed.
