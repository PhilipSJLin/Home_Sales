# Home_Sales
## Module 22 Challenge Datavis Bootcamp
Using SparkSQL to determine key metrics about home sales data

## **Overview of the Analysis**
This analysis aims to SparkSQL to determine key metrics about home sales data. I used spark to create temporary views, partition the data, cache and uncache a temporary table, and then veribied that the table has been uncached. <br/>

<details><summary>Our Task</Summary>

1. Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb. <br/>
2. Import the necessary PySpark SQL functions for this assignment.<br/>
3. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.<br/>
4. Create a temporary table called home_sales.<br/>
5. Answer the following questions using SparkSQL:<br/>
    1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.<br/>
    2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.<br/>
    3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.<br/>
    4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.<br/>
6. Cache your temporary table home_sales.<br/>
7. Check if your temporary table is cached.<br/>
8. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.<br/>
9. Partition by the "date_built" field on the formatted parquet home sales data.<br/>
10. Create a temporary table for the parquet data.<br/>
11. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.<br/>
12. Uncache the home_sales temporary table.<br/>
13. Verify that the home_sales temporary table is uncached using PySpark.<br/>
14. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.<br/>
</details>

## **Data**
For my assignment, I have used data extracted automatically being loaded in the ipynb file. <br/>
   * home_sales_revised.csv<br/>

In this assignment, I receieved assistance through looking at previous activities, stackoverflow, and received some support through my partner who works in the data analyst field<br/>


