# Retail-Sales-Analysis-Using-SQL

This Retail analysis is done using SQL to get the required data required for the stakeholders.

Project Title: Retail Sales Analysis 

Tools used: MySQL

Database: retail_sales

# Objectives
1. Set up a retail sales database: Create and populate a retail sales database with the provided sales data.
2. Data Cleaning: Identify and remove any records with missing or null values.
3. Exploratory Data Analysis (EDA): Perform basic exploratory data analysis to understand the dataset.
4. Business Analysis: Use SQL to answer specific business questions and derive insights from the sales data.

# Project Workflow

# 1. Database Setup

a. Database Creation
To start the Project Workflow, our first step would be to create a database

b. Table Creation
A table named `retail_sales` is created to store sales data. It includes columns for transaction ID, date, time, customer ID, gender, age, product category, quantity sold, price per unit, COGS, and total sale amount.

![image](https://github.com/user-attachments/assets/cb6cc0b0-d5a6-4c49-9bcf-ab82c7759ce8)

# 2. Data Exploration & Cleaning

Record Count: Determine the total number of records in the dataset.

Customer Count: Find out how many unique customers are in the dataset.

Category Count: Identify all unique product categories in the dataset.

Null Value Check: Check for any null values in the dataset and delete records with missing data.

![image](https://github.com/user-attachments/assets/b4b136b3-6523-4d54-944f-adbcf9723da7)

# 3. Data Analysis and Findings 

The following SQL queries were developed to answer specific business questions:

a. Write a SQL query to retrieve all columns for sales made on '2022-11-05:

![image](https://github.com/user-attachments/assets/f7b656b2-7b52-4239-bb53-173a38bb6514)


b. Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 4 in the month of Nov-2022

![image](https://github.com/user-attachments/assets/3d219618-1c91-4cd8-963f-614be4641f21)


c. Write a SQL query to calculate the total sales (total_sale) for each category.

![image](https://github.com/user-attachments/assets/e099f821-3712-460d-81cf-16a3014e996e)


d. Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.

![image](https://github.com/user-attachments/assets/4e1ab0f4-405a-4929-baf0-3c7d984aadf8)


e. Write a SQL query to find all transactions where the total_sale is greater than 1000.

![image](https://github.com/user-attachments/assets/1fa9f3bb-6a6f-4572-9dfd-7d9e924c0866)


f. Write a SQL query to find the total number of transactions (transaction_id) made by each gender in each category.

![image](https://github.com/user-attachments/assets/939dbc15-4cc9-455e-9e3f-4833b12c9535)


g. Write a SQL query to calculate the average sale for each month. Find out best selling month in each year.

![image](https://github.com/user-attachments/assets/5fa6cc71-c79c-4434-ad1d-9a4554230796)


h. Write a SQL query to find the top 5 customers based on the highest total sales.
![image](https://github.com/user-attachments/assets/2ebf30ee-7b47-40c3-a576-be281d484d86)


i. Write a SQL query to find the number of unique customers who purchased items from each category.

![image](https://github.com/user-attachments/assets/1d8049d1-203d-441f-9542-0d4fd00142aa)


j. Write a SQL query to create each shift and number of orders (Example Morning <12, Afternoon Between 12 & 17, Evening >17).

![image](https://github.com/user-attachments/assets/a22e67b6-3538-40bb-99e0-13d9ae6a870a)


# Findings: 

**Customer Demographics:** Customers belong to different age groups, and sales are spread across categories like Clothing and Beauty.

**High-Value Transactions:** Some sales exceeded 1000, showing significant purchases.

**Sales Trends:** Monthly sales vary, highlighting peak seasons.
  
**Customer Insights:** Top customers and popular product categories were identified.  


# Conclusion:  

This project provides a hands-on introduction to SQL for data analysis, including database setup, data cleaning, and analysis. The insights gained, like sales patterns, customer behavior, and product performance, can support better business decisions.













