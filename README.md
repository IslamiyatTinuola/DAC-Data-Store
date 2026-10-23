DAC Data Store – Power BI Sales Analysis

Project Overview

This project analyses retail store sales data using Microsoft Power BI to understand sales performance, customer purchasing patterns, product profitability, discounts and geographical sales trends.

The goal is to transform raw sales data into meaningful insights through interactive dashboards and support better business decisions.

Tools Used

Microsoft Excel: Data source and initial data inspection.

Power BI: Data cleaning, modelling and dashboard development.

Power Query: Data transformation and preparation.

DAX: Calculated measures for sales, estimated profit and order analysis.

Project Objectives

The dashboard was designed to answer eight key business questions:

Identify the top and bottom five products by sales, profit and quantity sold.

Analyse daily, monthly, quarterly and yearly sales trends.

Examine the relationship between sales and profit.

Compare sales, profit and quantity sold between two selected periods.

Calculate the average discount offered across promotion categories.

Determine the total number of orders.

Display transaction details with filters for product, date, customer ID and promotion category.

Compare sales performance across different cities.

Dataset Description

The dataset contains 3,510 transaction records, alongside product, customer and promotion information.

Key information includes transaction dates, products, quantities sold, prices, customer details, cities and promotional discounts.

Data Cleaning and Preparation

The following activities were undertaken:

Inspected the dataset for missing values and inconsistent data types.

Reviewed transaction dates and numerical fields.

Organised product, customer, promotion and transaction tables.

Prepared relationships between relevant tables.

Created measures for sales, discounts, quantity sold and estimated profit.

Prepared the data for dashboard visualisation.

Assumptions and Calculations

The dataset did not contain actual product costs or profit figures. Therefore, a 10% profit margin on net sales was assumed for the analysis.

Gross Sales = Unit Price × Quantity Sold

Net Sales = Gross Sales − Discount Amount

Estimated Profit = Net Sales × 10%

Since no unique Order ID was available, each transaction row was treated as one order.

Estimated Total Orders = 3,510

These assumptions mean that profit and order figures are estimates rather than verified business results.

Key Findings

Sales Quantity: The dataset contains 3,510 transaction records and 7,125 units sold.

Product Performance: Apple iPhone 14 recorded the highest quantity sold at 281 units, followed by Raymond Suit with 274 units.

City Performance: Kanpur recorded the highest sales quantity with 875 units, followed by Bhopal with 820 units and Indore with 779 units.

These findings highlight differences in product demand and purchasing patterns across locations.

Business Recommendation

The store should prioritise inventory planning for high-demand products and locations.

Maintaining adequate stock levels of popular products in cities with strong sales activity could help reduce stock shortages, improve customer satisfaction and increase revenue opportunities.

Challenges and Limitations

The main challenges encountered during the project were:

Missing actual product costs and profit figures.

Lack of unique Order IDs.

Establishing relationships between multiple data tables.

Developing interactive dashboard filters and DAX calculations.

Validating period comparisons and transaction-level reporting.

Some dashboard features require further validation, particularly interactive period comparisons and detailed transaction filtering.

Conclusion

This project demonstrates how Power BI can be used to analyse retail sales performance, identify popular products, evaluate geographical demand and present business insights.

Despite limitations in the dataset, the analysis provides useful information for inventory management, sales monitoring and business decision-making.

Author

Bakre Tinuola - Data Analytics Capstone Project

Developed using Microsoft Power BI, Microsoft Excel, Power Query and DAX.
