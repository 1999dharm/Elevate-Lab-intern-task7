Amazon Sales Data Analysis - Project Summary
Project Objective
To analyze Amazon sales data by cleaning, transforming, storing, and visualizing it to gain insights into product performance and revenue generation.
________________________________________
Key Steps in the Project
1.	Data Loading & Storage:
o	Loads data from a CSV file (amazon.csv).
o	Saves it into an SQLite database (sales_data.db).

3.	Data Cleaning:
o	Removes unwanted symbols (₹, commas) from numeric columns.
o	Converts string values to numeric data types (float, int).
o	Drops rows with missing essential information.

5.	Data Transformation:
o	Renames columns (product_name → product, discounted_price → price, etc.).
o	Calculates revenue using:
revenue = quantity × price.

6.	Database Querying:
o	Executes SQL queries to summarize sales data.
o	Identifies the Top 10 products based on total revenue.

7.	Visualization:
o	Bar Chart: Displays top 5 products by revenue.
o	Scatter Plot: Shows correlation between quantity sold and revenue.
o	Histogram: Reveals revenue distribution across products.
o	Pie Chart: Illustrates revenue share among the top 5 products.
________________________________________
Business Insight Goals
•	Identify best-selling and most profitable products.
•	Understand sales trends and product demand patterns.
•	Provide visual tools for interpreting revenue data.
•	Support strategic decisions in pricing, inventory, and marketing.

