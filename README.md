# Data-Analysis-Projects
## MySQL Covide Analysis:

This code explores COVID-19 data from the Our World in Data website.
The code uses a variety of SQL techniques, including joins, CTEs, temp tables, windows functions, aggregate functions, creating views, and converting data types.
The code first selects all data from the CovidDeaths table where the continent is not null. This ensures that only data from countries are included in the analysis. The code then calculates the following metrics:

Total cases
Total deaths
Total cases vs. total deaths (death percentage)
Total cases vs. population (percentage of the population infected)
Countries with the highest infection rate compared to the population
Countries with the highest death count per population
Continents with the highest death count per population
Global numbers (total cases, total deaths, death percentage)
Total population vs. vaccinations (percentage of the population that has received at least one Covid vaccine)
The code then uses a CTE, a temp table, and a view to store the data for later visualizations.

This code is a good example of how SQL can be used to explore and analyze large datasets. The code is well-organized and easy to follow, and it uses a variety of SQL techniques to extract insights from the data.

## Walmart CLT:
The code reads the Walmart data from a CSV file and performs some basic data cleaning and exploration.
The code identifies some interesting insights from the data, such as:
The majority of purchases are made by males aged 26-35 who live in city category B.
City category B is more active in terms of purchasing, even though it has a smaller percentage of the total population.
There is a significant difference between the mean and median purchase amounts, suggesting that there are some outliers in the data.
The code is well-organized and easy to follow. It uses a variety of Python libraries, including NumPy, Pandas, and Matplotlib.

Here are some additional observations that could be made from the data:

The average purchase amount is higher for older customers.
Customers who have lived in their current city for longer tend to make larger purchases.
There is a slight difference in the types of products that are purchased by males and females.
Overall, the code provides a good overview of the Walmart data and identifies some interesting insights. It could be used to inform future marketing campaigns or product development decisions.

## RFM Analysis:
The code first imports the necessary libraries, such as pandas, numpy, matplotlib, and seaborn. It then loads the two datasets, Transactions_RFM.csv and Customer_RFM.csv, into two separate DataFrames.
The code then merges the two DataFrames based on the customer_id column. This creates a new DataFrame called merged_trans_cust.
The code then calculates the recency, frequency, and monetary values for each customer. It does this by finding the number of days since the last transaction, the total number of transactions, and the total amount spent by each customer.
The code then divides the recency, frequency, and monetary values into four quartiles. This creates four categories for each value: 1 (lowest) to 4 (highest).
The code then creates a new column called RFM_score for each customer. The RFM_score is calculated by adding up the quartile values for recency, frequency, and monetary.
The code then customers with the RFM score.
The code is well-organized and easy to follow. It uses a variety of Python libraries to perform the necessary tasks. The code also produces some interesting insights, such as the top 5 customers with the highest RFM score and others.

Here are some additional observations that could be made from the code:

The code could be modified to calculate the RFM score for each customer at different time intervals. This would allow businesses to track how the RFM score for each customer changes over time.
The code could also be modified to calculate the RFM score for different groups of customers. This would allow businesses to target their marketing campaigns more effectively.

## Aerofit:
The code performs graphical/non-graphical analysis of a dataset of treadmill users. 
The analysis includes the following:
Descriptive statistics for age, education, usage, fitness, income, and miles.
Percent share of each product, gender, and marital status.
Average miles walk/run on the treadmill and average fitness level of the product user.
Gender vs fitness level.
Age outliers and analyzing age by creating 6 bins.
Product in each age level and percent of product sold in each age level.

The code uses descriptive statistics to summarize the data. This is a common technique used in data analysis.
The code includes a section on the percent share of each product, gender, and marital status. This information is relevant to marketing and sales teams and could be used to target specific demographics.
The code includes a section on the average miles walked/run on the treadmill and the average fitness level of the product user. This information is relevant to product development teams and could be used to improve the product.
The code includes a section on gender vs fitness level. This information is relevant to research teams and could be used to understand the relationship between gender and fitness.
The code includes a section on age outliers and analyzing age by creating 6 bins. This information is relevant to quality assurance teams and could be used to identify and address potential data quality issues.
The code includes a section on products in each age level and percent of products sold in each age level. This information is relevant to marketing and sales teams and could be used to target specific age groups.

## DVD Rental Analysis:
The code performs a variety of queries on the sakila database. The queries are designed to provide insights into the rental activities of customers, the revenue generated by the stores, and the popularity of different movies and categories.

Here are some specific points that are relevant to the code:

The code queries the film table to determine the number of movies in each rating category. This information can be used to identify which categories are most popular with customers.
The code queries the rental table to determine the most rented movies. This information can be used to identify which movies are most popular with customers.
The code queries the customer table to determine the most active customers. This information can be used to identify which customers are most likely to rent movies in the future.
The code queries the store table to determine the stores that have generated the most revenue. This information can be used to identify which stores are most successful.
