# Futon-Manufacturing-Analytics
SQL Server and Tableau project analyzing manufacturing sales performance, revenue trends, and product sales using synthetic data.
# Futon Manufacturing | Sales Performance Analytics

## Project Overview

For this project, I used SQL Server and Tableau Public to analyze sales data from a fictional furniture manufacturing company. I wanted to get more hands-on experience working with a database, writing SQL queries, and building a dashboard that makes sales performance easier to track.

The dashboard focuses on revenue, order volume, monthly sales trends, and top-selling products.

## Tools Used

- **SQL Server:** Writing queries, joining tables, creating views, and checking data accuracy
- **Docker:** Running SQL Server locally on my Mac
- **Visual Studio Code:** Writing and executing SQL queries
- **Tableau Public:** Building the dashboard and adding interactive filters
- **GitHub:** Organizing and sharing the project

## Data Preparation

I started with a sample manufacturing database that included sales orders, order details, product information, and production data.

Since the original dataset had a limited number of transactions, I added more sample sales and production records to have enough data to work with.

I then created a SQL view that joined the sales orders, order details, and product tables. The view included fields such as order date, product name, quantity, unit price, discounts, and net sales.

Once the data was ready, I exported the results to a CSV file and imported it into Tableau Public.

## Sales Dashboard

I built a dashboard to look at a few key sales metrics:

- **Total Revenue:** Sales from shipped and delivered orders
- **Total Orders:** Number of unique sales orders
- **Units Sold:** Total quantity of products sold
- **Monthly Revenue:** How sales changed over time
- **Top-Selling Products:** Which products generated the most revenue

I also added filters for order status and date range so users can explore the data.

## SQL Queries

I included the SQL scripts used for this project in the `SQL` folder.

- **Sales Performance View:** Joins the sales and product tables into one dataset for Tableau.
- **Sales Validation:** Checks revenue, order counts, and units sold against the dashboard.
- **Top Products:** Ranks products by revenue and quantity sold, including each product's share of total sales.

The queries use joins, aggregations, CTEs, and window functions.

## What I Learned

This project gave me more practice working with SQL Server and connecting SQL data to Tableau.

One of the things I focused on was making sure the numbers in Tableau matched the results from SQL. I also worked on organizing the dashboard so the main sales metrics were easy to find and the filters were simple to use.

## Dashboard

**Tableau Public:** https://public.tableau.com/views/FutonDashboard/FutonManufacturing?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**Dashboard Screenshot:** 

## Note About the Data

This project uses synthetic data created for practice and portfolio purposes. The sales figures do not represent a real company's performance.
