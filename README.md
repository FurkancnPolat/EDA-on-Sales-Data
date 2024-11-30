# EDA-on-Sales-Data
This project demonstrates an Exploratory Data Analysis (EDA) on a synthetic sales dataset using Python. The analysis explores sales trends, product performance, and revenue insights to uncover valuable patterns and insights that can drive business decisions.

# Dataset Overview
The dataset consists of 500 rows and 5 columns:
Sale_Date: Date of the sale.
Product: Type of product sold.
Quantity: Number of units sold (may contain missing values).
Price: Unit price of the product (may contain missing values).
Region: Geographic region where the sale occurred.
Additionally, a derived column, Total_Sale, was created to calculate revenue for each transaction (Quantity * Price).

# Steps Performed
Data Loading and Exploration
Imported the dataset and explored its structure, including missing values.
Data Cleaning
Handled missing values using statistical imputation methods.
Feature Engineering
Created a new column, Total_Sale, for revenue analysis.
Descriptive Statistics and Visualization
Explored the distribution of products, prices, and sales trends over time.
Visualized key metrics using matplotlib and seaborn.
Insights Summary
Identified the most and least selling products, revenue trends, and more.

# Visualizations
The project includes the following visualizations:
Daily sales trends over time.
Product sales distribution.
Revenue contribution by product type.
Price distribution and outliers.
