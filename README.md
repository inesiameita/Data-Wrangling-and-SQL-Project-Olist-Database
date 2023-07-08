# Data-Wrangling-and-SQL-Project-Olist-Database

# Introduction and Objectivity
Olist is the largest department store in the Brazilian marketplace, providing a platform for small businesses across Brazil to connect with various channels through a single contract. 
In this project, we will analyze the Olist Store database, the database contains information about thousands of orders placed between 2016 and 2018 in various markets across Brazil.

The objectives of the analysis are as follows:
1. Which products are the most popular or sold the most?
2. Which products have the highest total sales?
3, What types of payment are most frequently used by customers?
4. How is the trend of orders placed each month of the year?
5. How much is the total revenue of Olist during that period?
6. How is the trend of revenue for each quarter and each month of the year?

# Data Overview
The Olist database that we are using for this project is stored in the following relational database.
![image](https://github.com/inesiameita/Data-Wrangling-and-SQL-Project-Olist-Database/assets/128911434/11e360f7-a849-4545-86c1-e7c359bcb5dc)

# Exploration and Data Processing
The explanation of this project starts with some common steps:
1. Import Python libraries
2. Connect to SQLite database
3. Execute the SQL query
4. Convert to pandas dataframes
5. Merge multiple datasets
6. Drop unused columns in dataset
7. Drop or remove rows with missing values (NaN) from dataset
8. Identify and filter out duplicated rows, remove duplicated rows
9. Convert column in dataset to a datetime data
10. Check inconsitent value for each categorical data
11. Proceed with the data analysis process

# Data Analysis
- Question 1. Which products are the most popular or sold the most?
![image](https://github.com/inesiameita/Data-Wrangling-and-SQL-Project-Olist-Database/assets/128911434/f6fe8dd2-5d4b-42e6-b48f-05c41f0deb6f)

Based on the chart above, it can be observed that the most popular product or the best-selling item is bed bath table, with total sales quantity is 11,684 products. 

- Question 2. Which products have the highest total sales?
![image](https://github.com/inesiameita/Data-Wrangling-and-SQL-Project-Olist-Database/assets/128911434/5d0f04a0-2f86-403e-bbda-98f421213f2b)

Based on the chart above, it can be determined that the product with the highest total sales is health beauty, with a total sales is 1.267 in R$ million.

- Question 3. What types of payment are most frequently used by customers?
![image](https://github.com/inesiameita/Data-Wrangling-and-SQL-Project-Olist-Database/assets/128911434/9282c0f5-61c4-4c30-9d99-f3add4e7ab41)

Based on the chart above, it can be determined that the frequently used payment type is credit card, with number of transactions is 83,528.

- Question 4. How is the trend of orders placed each month of the year?
![image](https://github.com/inesiameita/Data-Wrangling-and-SQL-Project-Olist-Database/assets/128911434/460316b0-ca8c-4297-8298-9c0b288c5026)

Based on the trend chart, it can be observed that the orders for each month shows an increasing trend, reaching its peak in November of 2017 with 8692 product sales. 
However, in December of 2017, the total orders experiences a significant decline with 6261 product sales, and increase in January of 2018.

- Question 5. How much is the total revenue of Olist during that period?
![image](https://github.com/inesiameita/Data-Wrangling-and-SQL-Project-Olist-Database/assets/128911434/64d4696b-80c3-4f53-9351-c2cc1a97c4e2)

Olist generated a total revenue of R$ 19.4202M for the period from October 2017 to July 2018.

- Question 6. How is the trend of revenue for each quarter and each month of the year?
![image](https://github.com/inesiameita/Data-Wrangling-and-SQL-Project-Olist-Database/assets/128911434/d74af2f3-cb23-4855-b7f5-6f18f6d2cc9d)

Based on the trend chart, it can be observed that the revenue for each quarter shows an increasing trend, reaching its peak in the second quarter of 2018 with 4.1932 R$ Million. 
However, in the third quarter of 2018, the total revenue experiences a significant decline with 2.4889 R$ Million.

![image](https://github.com/inesiameita/Data-Wrangling-and-SQL-Project-Olist-Database/assets/128911434/27e631b9-18ce-4630-83db-13b275a91792)

Based on the trend chart, it can be observed that the revenue for each month shows an increasing trend, reaching its peak in November of 2017 with 1.5275 R$ Million. 
However, in December of 2017, the total revenue experiences a significant decline with 0.9910 R$ Million and increase in January of 2018.

# Summary and Conclusion
1. According to the provided chart, the product category bed bath table stands out as the most popular and best-selling item, with a total sales quantity of 11,684 products.
2. The provided chart shows that the product category health beauty has the highest total sales, amounting to 1.267 million R$. 
3. Based on the chart provided, it is evident that the most frequently used payment type is credit card, with a total of 83,528 transactions. 
4. These observations indicate that there are seasonal trends in customer behavior, with a higher inclination towards shopping and increased order numbers at the beginning of the year.
5. During the period from October 2017 to July 2018, Olist accumulated a total revenue of R$ 19.4202 million. 
6. The revenue figures show consistent patterns of increasing trends in both quarterly and monthly data, with the highest points occurring at the beginning of the year.
   These patterns can be attributed to factors such as holiday shopping, New Year’s resolutions, and increased customer purchasing power due to financial factors like bonuses and tax refunds.
   These observations suggest that there are seasonal variations in customer behavior and demand, with a greater inclination towards shopping and increased revenue at the start of the year.

In conclusion, there is still much more to explore from the Olist database. 
Moving forward, conducting analyses from various different perspectives can provide valuable insights and opportunities for further exploration. 
By exploring the dataset from different angles, such as customer segmentation, geographical analysis, product trend analysis, or supply chain analysis, we can gain a deeper understanding of Olist’s business dynamics and uncover new possibilities.

# Extended Report 
For a more detailed report, please refer to the following : https://inesiameita.medium.com/data-wrangling-and-sql-olist-brazilian-e-commerce-database-4253956dd0a9

