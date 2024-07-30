# Home_Sales_challeng
---
**For this assignment , we completed the following tasks.**
- Imported the necessary PySpark SQL functions for this assignment.
- Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.
<img width="805" alt="Screenshot 2024-07-30 at 2 58 52 PM" src="https://github.com/user-attachments/assets/bd73fa0a-7742-435b-833f-e0552bb18ff4">

- Created a temporary table called home_sales and answered the following questions using SparkSQL:
* What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
* What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? 
* What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
* What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
  
<img width="698" alt="Screenshot 2024-07-30 at 3 13 28 PM" src="https://github.com/user-attachments/assets/c5219db3-c165-40fe-ab4c-1cfc5631135e">

- Cached our temporary table home_sales.
- Checked if our temporary table is cached.
- then using the cached data, ran the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000 and determined the runtime and compared it to uncached runtime.
  <img width="487" alt="Screenshot 2024-07-30 at 3 37 10 PM" src="https://github.com/user-attachments/assets/e94dd0e1-9c0e-42b8-b9be-1a92df058c9f">

- Partitioned by the "date_built" field on the formatted parquet home sales data.
- Created a temporary table for the parquet data.
- Ran the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

    <img width="468" alt="Screenshot 2024-07-30 at 3 14 46 PM" src="https://github.com/user-attachments/assets/453d7b22-5344-41cd-881b-dec2a52c266e">

- Uncached the home_sales temporary table.
- Verified that the home_sales temporary table is uncached using PySpark.
 
