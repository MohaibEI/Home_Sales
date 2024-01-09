# Home Sales Assignment

## Instructions:

1. **Notebook Renaming:**
   - Rename the provided Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

2. **PySpark SQL Functions:**
   - Import the necessary PySpark SQL functions for this assignment.

3. **Reading Data:**
   - Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

4. **Create Temporary Table:**
   - Create a temporary table called home_sales.

5. **SparkSQL Questions:**
   - Answer the following questions using SparkSQL:
     - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
     - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
     - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
     - What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query and round off your answer to two decimal places.

6. **Caching:**
   - Cache your temporary table home_sales.
   - Check if your temporary table is cached.

7. **Cached Query:**
   - Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to the uncached runtime.

8. **Parquet Data:**
   - Partition by the "date_built" field on the formatted parquet home sales data.
   - Create a temporary table for the parquet data.

9. **Parquet Query:**
   - Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to the uncached runtime.

10. **Uncaching:**
    - Uncache the home_sales temporary table.
    - Verify that the home_sales temporary table is uncached using PySpark.

11. **Download and Upload:**
    - Download your Home_Sales.ipynb file.
    - Upload it to your "Home_Sales" GitHub repository.
