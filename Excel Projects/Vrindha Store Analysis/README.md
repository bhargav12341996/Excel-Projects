
# Objective of the Project:
Store “Vrinda” wants to analyze the annual sales report of 2022 to understand their customer behavior to improve its sales strategy for 2023.

# Insights we are trying to find from the project:
•	Which month got the highest sales and orders? <br>
•	Who purchased more, men or women? <br>
•	What are the different order statuses? <br>
•	Compare the sales and orders using single chart. <br>
•	List of top 10 states contributing to the sales. <br>
•	Which channel is contributing to maximum sales? <br>
•	Highest selling category? <br>
•	Relation between age and gender based on number of orders.

# Steps involved in the project:
1.	Data Cleaning <br>
2.	Data Processing <br>
3.	Data Analysis <br>
4.	Preparing Dynamic dashboards with slicers. <br>
5.	Sharing the report/insights. <br>

# Data Cleaning:
As part of data cleaning we check for any duplicate values, missing/null values, inconsistencies or anomalies in the data.
<br>

# Findings:<br>
Gender has M & Men for Men’s category, W & Women for Women’s category. <br>

Using Ctrl+H, we replaced  the values and made the data consistent by having only Men & women. <br>

![image](https://github.com/user-attachments/assets/2c7f7b4a-c9f8-4a84-9bfb-0e962f438a85)

<br>
 
Qty has One & two, so using Ctrl+H we place them with 1 & 2.

 ![image](https://github.com/user-attachments/assets/5197435c-3ea5-41eb-aca4-0cf950b92bbc)



# Data Processing: <br>
As part of data processing, we are creating two new custom columns “Age group” and “Month”. <br>

We are using Nested IF function to create the age group:<br>
![image](https://github.com/user-attachments/assets/56be159d-a915-4d94-9d2c-7e7530904025)

 

Using the text function, we are extracting the month.<br>

![image](https://github.com/user-attachments/assets/5767e6c4-7567-462e-abe1-ecec31507076)

 
# Data Analysis: <br>

For data analysis, we used Pivot tables to analyze the data and created a dashboard with the help of slicers. <br>
![image](https://github.com/user-attachments/assets/7abfb815-7ac0-43b6-abfc-36404a1e7d19)

 

# Dashboard:<br>
![image](https://github.com/user-attachments/assets/9a6dfda5-6575-4bcb-9e4c-a7a391ebd9f5)

 


# Insights: <br>
•	March got the highest sales of 1.92M and 2819 orders <br>
•	Women made more purchases that is 64%, compared to Men who made 36% of purchases. <br>
•	Adults (Age group 30-50) made most purchases and contributed around 50% of sales. <br>
•	Top 5 States: <br>
![image](https://github.com/user-attachments/assets/ab84ee61-c7a8-4d3d-ac8e-20f555fb2a46)

 

•	Amazon is contributing to the highest sales with 35% of sales. <br>

Dataset : Click here[https://github.com/bhargav12341996/Excel-Projects/tree/main/Excel%20Projects/Vrindha%20Store%20Analysis/Dataset]



