# Walmart_Data_cleaning-Using-Pandas-Analysing-Using-SQL
This project is an end-to-end data analysis solution to extract critical business insights from Walmart sales data. We utilize Python for data processing and Analysis, SQL for advanced querying, and structured problem-solving techniques to solve key business questions
# Project Requirements
**1. Set Up the Environment**
Tools Used: Visual Studio Code (VS Code), Python, SQL (MySQL Work bench/My SQL command line)
Goal: Create a structured workspace within VS Code and organize project folders for smooth development and data handling.

**2. Set Up Kaggle API**
API Setup: Obtain your Kaggle API token from  [Kaggle](https://www.kaggle.com/) by navigating to your profile settings and downloading the JSON file.
Configure Kaggle:
Place the downloaded kaggle.json file in your local .kaggle folder.
Use the command kaggle datasets download -d <dataset-path> to pull datasets directly into your project.

**3. Download Walmart Sales Data**
Data Source: Use the Kaggle API to download the Walmart sales datasets from Kaggle.
Storage: Save the data in the data/ folder for easy reference and access.

**4. Install Required Libraries and Load Data**
Libraries: Install necessary Python libraries using:
pip install pandas numpy PYMYSQL 
Loading Data: Read the data into a Pandas DataFrame for initial analysis and transformations.

**5. Explore the Data**
Goal: Conduct an initial data exploration to understand data distribution, check column names and types, and identify potential issues.
Analysis: Use functions like .info(), .describe(), shape(), and .head(), tail() to get a quick overview of the data structure and statistics.

**6. Data Cleaning**
Remove Duplicates: Identify and remove duplicate entries to maintain data integrity.
Handle Missing Values: Drop rows or columns with missing values if they are insignificant; fill values where essential.
Fix Data Types: Ensure all columns have consistent data types (e.g., dates as datetime, prices as float).
Currency Formatting: Use .replace() to handle and format currency values for analysis.
Validation: Check for any remaining inconsistencies and verify the cleaned data.

 **7.Feature Engineering**
Create New Columns: Calculate the Total Amount for each transaction by multiplying unit_price by quantity and adding this as a new column.
Enhance Dataset: Adding this calculated field will streamline further SQL analysis and aggregation tasks

**8.Load Data into MySQL**
Set Up Connections: Connect to MySQL and using MYPYSql and load the cleaned data into each database.
Table Creation: Set up tables in both MySQL  using Python PYMYSQL to automate table creation and data insertion.
Verification: Run initial SQL queries to confirm that the data has been loaded accurately.

**9.SQL Analysis**: Complex Queries and Business Problem Solving
Business Problem-Solving: Write and execute complex SQL queries to answer critical business questions, such as:
Revenue trends across branches and categories.
Identifying best-selling product categories.
Sales performance by time, city, and payment method.
Analyzing peak sales periods and customer buying patterns.
Profit margin analysis by branch and category.


**REQUIREMENTS**
Python 3.8
SQL Databases: MySQL
Python Libraries:
pandas, numpy, pyMYSQL
Kaggle API Key (for data downloading)



**Results and Insights**:
Sales Insights: Key categories, branches with highest sales, and preferred payment methods.
Profitability: Insights into the most profitable product categories and locations.
Customer Behavior: Trends in ratings, payment preferences, and peak shopping hours.
