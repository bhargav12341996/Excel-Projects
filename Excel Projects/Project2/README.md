# Bike_Sales_Analysis_Using_Excel

In this project, we are using excel to analyze the bike sales across diffent countries, genders,age etc.

Bike_buyers sheet from excel file is where we have the original data. This is modified for data analysis in the working_sheet.

**Functions used:**
1. Ctrl + H : To find and replace values. (Modified marital status & gender columns)
   
2. Data > Remove Dupicates: to remove the duplicate values.
   
3. IF function to create a custom columns.
   
4. Created Custom column based on formula using Nested IF function:
   
    =IF(L2>54,"Old",IF(L2>=31,"Middle Aged", IF(L2<31,"Adolescent","Invalid")))

![1](https://github.com/user-attachments/assets/78e23a6d-67d9-4789-b708-9d1182b81f85)



Created Pivot tables and pivot charts to analyze the data.

![2](https://github.com/user-attachments/assets/38c5c5cc-9987-485a-9cb2-d7a2459ae57f)


Created dynamic dashboards using multiple pivot charts and dynamic slicers by establishing connections within the pivot tables using "Report Connections"


![3](https://github.com/user-attachments/assets/5973f6d6-6f45-4d12-aae2-38e765a9d364)


**Observations:**
1. Males have a higher income compared to females.
2. People with higher average income have purchased the bicycles.
3. Very few people are commuting by bike when distance is greater than 10 miles.
4. In Adolescent & Old Age groups, very few people are commuting by bikes. However, majority of middle ages people are commuting by bikes.

![4](https://github.com/user-attachments/assets/3e0392e3-547b-401a-aff5-523f45a9ee4f)




Resources:
<br>
Dataset File link: https://github.com/bhargav12341996/BIke_Sales_Analysis_Using_Excel/blob/main/Dataset.xlsx
Project File link: https://github.com/bhargav12341996/BIke_Sales_Analysis_Using_Excel/blob/main/Bike%20Sales%20Analysis.xlsx
