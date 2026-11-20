# E-Commerce Sales Analysis Using Python

## Project Overview
This project performs Exploratory Data Analysis (EDA) on an online retail dataset to understand sales performance, revenue trends, popular products, customer purchasing behaviour, and country-wise sales distribution.

The analysis uses Python libraries to clean, process, analyse, and visualize e-commerce transaction data.

## Objectives
- Analyse overall sales and revenue performance.
- Identify the best-selling products.
- Examine monthly revenue trends.
- Analyse country-wise sales performance.
- Understand customer purchasing behaviour.
- Identify daily and hourly sales patterns.

## Dataset
- **Dataset Name:** Online Retail
- **Source:** UCI Machine Learning Repository
- **Original Records:** Approximately 541,909
- **Original Attributes:** 8
- **Period:** December 2010 – December 2011

**Dataset Link:** https://archive.ics.uci.edu/dataset/352/online+retail

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning and Preprocessing
The following preprocessing operations were performed:

- Removed duplicate records.
- Removed cancelled transactions.
- Removed records with invalid or non-positive quantities and prices.
- Handled missing values in essential transaction fields.
- Converted invoice dates into datetime format.
- Created additional time-based features.

## Exploratory Data Analysis
The project includes:

1. Overall Sales Performance Analysis
2. Monthly Revenue Analysis
3. Top 10 Best-Selling Products
4. Country-Wise Revenue Analysis
5. Top 10 Customers by Revenue
6. Day-Wise Sales Analysis
7. Hourly Sales Analysis
8. Sales Correlation Analysis

## Key Performance Indicators (KPIs)
- Total Revenue
- Total Orders
- Total Identified Customers
- Total Unique Products
- Total Quantity Sold
- Average Order Value

## Project Files
- `Ecommerce_Sales_Analysis.ipynb` – Jupyter Notebook containing data cleaning, analysis, visualizations, and findings.
- `cleaned_ecommerce_sales.csv.gz` – Compressed cleaned dataset.
- `README.md` – Project documentation.

## Conclusion
This project provides insights into e-commerce sales performance through data cleaning, exploratory analysis, and visualization. The findings help understand revenue patterns, product demand, customer purchasing behaviour, and sales distribution across countries.

## Future Enhancements
- Sales forecasting.
- Customer segmentation.
- Interactive sales dashboard.
- Advanced business performance analysis.
