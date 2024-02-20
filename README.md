# Home_Sales
Module 22 Challenge

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Instructions
- Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

- Import the necessary PySpark SQL functions for this assignment.

- Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

  <img width="998" alt="image" src="https://github.com/ranjini-rao/Home_Sales/assets/143301151/cd7637ff-5474-4a5a-a6fa-11c32295cd0e">


- Create a temporary table called home_sales.

- Answer the following questions using SparkSQL:

- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

  <img width="201" alt="image" src="https://github.com/ranjini-rao/Home_Sales/assets/143301151/546f344c-a5b6-48d6-9757-f0cda7515997">


- What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two 
  decimal places.

  <img width="247" alt="image" src="https://github.com/ranjini-rao/Home_Sales/assets/143301151/c9bc7368-e166-4d6b-939b-e714018a4956">


- What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 
 2,000 square feet? Round off your answer to two decimal places.

  <img width="248" alt="image" src="https://github.com/ranjini-rao/Home_Sales/assets/143301151/0786ed02-60ef-4ca4-ae78-4a7a33b7738c">


- What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your 
 answer to two decimal places.

<img width="214" alt="image" src="https://github.com/ranjini-rao/Home_Sales/assets/143301151/7b5edecb-f5d7-4a66-8643-81652aff1c29">


- Cache your temporary table home_sales.

- Check if your temporary table is cached.

- Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. 
 Determine the runtime and compare it to uncached runtime.

<img width="338" alt="image" src="https://github.com/ranjini-rao/Home_Sales/assets/143301151/ad53005f-46a7-420d-88f4-24343ca8b0f6">


- Partition by the "date_built" field on the formatted parquet home sales data.

- Create a temporary table for the parquet data.

- Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and 
 compare it to uncached runtime.

<img width="338" alt="image" src="https://github.com/ranjini-rao/Home_Sales/assets/143301151/5792263d-d549-4613-9626-4c2131dc28fe">


- Uncache the home_sales temporary table.

- Verify that the home_sales temporary table is uncached using PySpark.

- Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.


