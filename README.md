# Elevate-Lab-intern-task7

Amazon Sales Data Analysis - Project Summary
Project Objective
To analyze Amazon sales data by cleaning, transforming, storing, and visualizing it to gain insights into product performance and revenue generation.

Key Steps in the Project
Data Loading & Storage:

Loads data from a CSV file (amazon.csv).

Saves it into an SQLite database (sales_data.db).

Data Cleaning:

Removes unwanted symbols (₹, commas) from numeric columns.

Converts string values to numeric data types (float, int).

Drops rows with missing essential information.

Data Transformation:

Renames columns (product_name → product, discounted_price → price, etc.).

Calculates revenue using:
revenue = quantity × price.

Database Querying:

Executes SQL queries to summarize sales data.

Identifies the Top 10 products based on total revenue.

Visualization:

Bar Chart: Displays top 5 products by revenue.

Scatter Plot: Shows correlation between quantity sold and revenue.

Histogram: Reveals revenue distribution across products.

Pie Chart: Illustrates revenue share among the top 5 products.

Business Insight Goals
Identify best-selling and most profitable products.

Understand sales trends and product demand patterns.

Provide visual tools for interpreting revenue data.

Support strategic decisions in pricing, inventory, and marketing.
