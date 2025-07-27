# Walmart Data Analysis: End-to-End SQL + Python Project 
Project Steps:
Tools Used: Jupiter Notebook, Python, SQL (MySQL)
1. Install Required Libraries and Load Data
Libraries: Install necessary Python libraries using:
pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
Loading Data: Read the data into a Pandas DataFrame for initial analysis and transformations.
2. Explore the Data
Goal: Conduct an initial data exploration to understand data distribution, check column names, types, and identify potential issues.
Analysis: Use functions like .info(), .describe(), and .head() to get a quick overview of the data structure and statistics.
3. Data Cleaning
Remove Duplicates: Identify and remove duplicate entries to avoid skewed results.
Handle Missing Values: Drop rows or columns with missing values if they are insignificant; fill values where essential.
Fix Data Types: Ensure all columns have consistent data types (e.g., dates as datetime, prices as float).
Currency Formatting: Use .replace() to handle and format currency values for analysis.
Validation: Check for any remaining inconsistencies and verify the cleaned data.
4. Feature Engineering
Create New Columns: Calculate the Total Amount for each transaction by multiplying unit_price by quantity and adding this as a new column.
Enhance Dataset: Adding this calculated field will streamline further SQL analysis and aggregation tasks.
5. Load Data into MySQL
Set Up Connections: Connect to MySQL using sqlalchemy and load the cleaned data into each database.
Table Creation: Set up tables in both MySQL using Python SQLAlchemy to automate table creation and data insertion.
Verification: Run initial SQL queries to confirm that the data has been loaded accurately.
6. SQL Analysis: Complex Queries and Business Problem Solving
Business Problem-Solving: Write and execute complex SQL queries to answer critical business questions, such as:
Revenue trends across branches and categories.
Identifying best-selling product categories.
Sales performance by time, city, and payment method.
Analyzing peak sales periods and customer buying patterns.
Profit margin analysis by branch and category.
Documentation: Keep clear notes of each query's objective, approach, and results.

Results and Insights:
Sales Insights: Key categories, branches with highest sales, and preferred payment methods.
Profitability: Insights into the most profitable product categories and locations.
Customer Behavior: Trends in ratings, payment preferences, and peak shopping hours.

