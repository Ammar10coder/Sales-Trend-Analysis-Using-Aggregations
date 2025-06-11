# Sales-Trend-Analysis-Using-Aggregations
task 6
	1.	This project performs a monthly sales trend analysis using SQL on an e-commerce dataset with SQLite.
	2.	The goal is to calculate monthly revenue and order volume by grouping data based on year and month.
	3.	The online_sales table contains fields such as order_id, order_date, product_id, and amount.
	4.	SQL aggregation functions like SUM() and COUNT(DISTINCT ...) are used to compute revenue and order volume respectively.
	5.	The strftime() function in SQLite is used to extract year and month from the order date.
	6.	A SQL VIEW named sales_monthly is created to store aggregated results for easier querying.
