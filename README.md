**# ```python
# Home_Sales
```
**
**# Introduction **
This repository uses SparkSQL to determine key metrics about home sales data and creating temporary views, partitioning the data, cache and uncache a temporary table, and verifying that the table has been uncached, using Spark.
# 
**Download the files to get started **
https://static.bc-edx.com/data/dl-1-2/m22/lms/starter/Starter_Code.zip

**# Instructions for the Analysis**
1 - Create a Spark DataFrame from the dataset.

2 - Create a temporary table of the original DataFrame.

3 - Write as query that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year. 

4 - Write a query that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms for each year the home was built. 

5 - Write a query that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year the home was built rounded to two decimal places. 

6 - Write a query that returns the average price of a home per "view" rating having an average home price greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.) 

7 - Create and validate a cache of the temporary "home_sales" table.

8 - The query from step 6 is run on the cached temporary table, and the run time is computed. 

9 - A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read. 

10 - Create a temporary table of the parquet data. 

11 - The query from step 6 is run on the parquet temporary table, and the run time is computed.

12- Uncache and verify the "home_sales" temporary table.