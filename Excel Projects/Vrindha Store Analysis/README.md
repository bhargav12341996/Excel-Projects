
# Objective of the Project:
Store “Vrinda” wants to analyze the annual sales report of 2022 to understand their customer behavior to improve its sales strategy for 2023.

# Insights we are trying to find from the project:
•	Which month got the highest sales and orders?
•	Who purchased more, men or women?
•	What are the different order statuses?
•	Compare the sales and orders using single chart.
•	List of top 10 states contributing to the sales.
•	Which channel is contributing to maximum sales?
•	Higheset selling category?
•	Relation between age and gender based on number of orders.

# Steps involved in the project:
1.	Data Cleaning
2.	Data Processing
3.	Data Analysis
4.	Preparing Dynamic dashboards with slicers.
5.	Sharing the report/insights.

# Data Cleaning:
As part of data cleaning we check for any duplicate values, missing/null values, inconsistencies or anomalies in the data.
Findings:
Gender has M & Men for Men’s category, W & Women for Women’s category.

Using Ctrl+H, we replaced  the values and made the data consistent by having only Men & women.

 
Qty has One & two, so using Ctrl+H we place them with 1 & 2.

 


Data Processing:
As part of data processing, we are creating two new custom columns “Age group” and “Month”.

We are using Nested IF function to create the age group:
 

Using the text function, we are extracting the month.
 
Data Analysis: For data analysis, we used Pivot tables to analyze the data and created a dashboard with the help of slicers.

 

Dashboard:
 


Insights:
•	March got the highest sales of 1.92M and 2819 orders
•	Women made more purchases that is 64%, compared to Men who made 36% of purchases.
•	Adults (Age group 30-50) made most purchases and contributed around 50% of sales.
•	Top 5 States:

 

•	Amazon is contributing to the highest sales with 35% of sales.


