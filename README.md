# Home_saless
🏡 Home Sales Analysis with PySpark
📘 Overview
In this challenge, we used Apache Spark and SparkSQL to explore and analyze a dataset of home sales. The main goal was to answer specific business questions about home prices by applying PySpark DataFrame transformations, caching, partitioning, and performance optimization.

📂 Project Setup
Create a new repository named Home_Sales.

Clone the repository to your local machine.

Rename the provided Home_Sales_starter_code.ipynb file to Home_Sales.ipynb.

Upload the completed notebook to your GitHub repo when finished.

🧪 Technologies Used
Python 3

Apache Spark / PySpark

SparkSQL

AWS S3 (for reading the dataset)

Jupyter Notebook

📁 Data Source
Filename: home_sales_revised.csv

Location: AWS S3 (as provided in challenge instructions)

📊 Tasks Completed
Task	Description
✅	Loaded home sales data into a Spark DataFrame
✅	Created a temporary SQL table home_sales
✅	Ran SQL queries to answer business questions
✅	Cached and uncached data to compare performance
✅	Partitioned data by date_built and read Parquet
✅	Created a temporary table from Parquet data
✅	Measured query runtimes for performance comparison

🧠 Questions Answered Using SparkSQL
Average price of four-bedroom homes per year

Average price of homes with 3 bed / 3 bath per year built

Average price of 3 bed / 3 bath / 2 floor homes ≥ 2000 sqft per year

Average price per "view" rating where avg price ≥ $350,000

Runtime was tracked and compared across:

Uncached

Cached

Partitioned Parquet format

🚀 Performance Optimization
Step	Optimization
✅	Cached the home_sales table to speed up queries
✅	Measured query runtime with and without caching
✅	Partitioned data by date_built and read as Parquet
✅	Compared runtime of the same query on Parquet table
✅	Uncached the table and verified with Spark

✅ Verification
All queries return results rounded to two decimal places

All runtimes were tracked using Python's time module

Cache and uncache status were checked using Spark's API

💾 How to Run
Ensure Spark is installed and running

Open Home_Sales.ipynb in Jupyter

Run each cell in order

Modify the AWS S3 path if needed to access the CSV

📌 Submission
Final file: Home_Sales.ipynb

Submitted via GitHub to the Home_Sales repository
