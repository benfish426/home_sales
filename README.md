# home_sales

The objective for this challenge is to demonstrate our knowledge of SparkSQL to determine key metrics about home sales data. Then, use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Since running in Google Colab, the code from the first two cells in the challenge code were provided and used in order to install Spark and Java, as well as set up the environment variables and starting a SparkSession.

The rest of the code in inspired by similar examples from class files.


Questions to Answer in Challenge

1) What is the average price for a four bedroom house sold per year, rounded to two decimal places?

2) What is the average price of a home for each year the home was built, that have 3 bedrooms and 3 bathrooms, rounded to two decimal places?

3) What is the average price of a home for each year the home was built, that have 3 bedrooms, 3 bathrooms, with two floors, and are greater than or equal to 2,000 square feet, rounded to two decimal places?

4) What is the average price of a home per "view" rating, rounded to two decimal places, having an average home price greater than or equal to $350,000? Order by descending view rating.