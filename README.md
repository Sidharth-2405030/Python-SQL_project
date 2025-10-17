# Python + SQL Data Analysis on Orders Dataset

📋 Overview

This project performs an end-to-end data analysis workflow using Python and SQL.
Starting from raw orders data, I cleaned and transformed the dataset in Python, added calculated fields such as discount, sale price, and profit, and then loaded the cleaned dataset into a SQL database using SQLAlchemy.
Further analysis was done in SQL to extract business insights such as sales by region, top products, and profit trends.  

🧰 Tools & Technologies
	•	Python (Pandas, SQLAlchemy)
	•	MSSQL
	•	Jupyter Notebook
	•	GitHub

⚙️ Steps Performed

  1. Data Cleaning
	  •	Removed invalid or missing entries and replaced them with NULL
	  •	Standardized column formats (e.g., date → datetime, cost/price → float)
	  •	Ensured consistent naming conventions

  2. Data Transformation
	  •	Created new columns:
	  •	Discount = List Price - Cost Price
	  •	Sale Price = List Price - Discount
	  •	Profit = Sale Price - Cost Price
	  •	Verified all calculated values and data types

  3. Database Integration
	  •	Established connection to SQL database using SQLAlchemy
	  •	Created a new table and inserted cleaned data
	  •	Verified table schema and integrity

  4. Data Analysis in SQL

  Performed SQL queries to answer key business questions:
	  •	Top 5 highest-selling products in each region
	  •	Compared month by month sales per year for each category of products
	  •	Found which product has highest growth in profit by year
	  •	For each category which month has the highest sale
