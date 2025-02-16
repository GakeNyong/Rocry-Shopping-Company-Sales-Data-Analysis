# Project Overview
This project involves analyzing the sales data of Rocry Shopping Company, an e-commerce company based in Diwali, India. 
The data has been extracted from the company's website and requires cleaning, processing, and analysis to gain insights into customer behavior, sales trends, and product performance.

# Project Objectives
The primary objectives of this project are:
- To clean and preprocess the sales data
- To analyze the sales data to identify trends and patterns
- To extract insights from the data to inform business decisions

# Project Scope
The project scope includes:
- Data cleaning and preprocessing
- Data analysis and visualization
- Insight extraction and reporting

# Project Requirements
The project involves the following tasks:
1. Data cleaning: Delete empty columns and replace missing values in the Amount column with 0.
2. Data transformation: Replace M and F with Male and Female in the Gender column, and replace 0 and 1 with Single and Married in the Marital Status column.
3. Data analysis: Extract insights from the cleaned and transformed data, including:

- Total number of customers
- Occupation with the highest number of orders and sum of orders
- Top 10 product categories by sum of amount and percentage of total
- Age group of male and female customers with the highest number of orders
- Sales by state across gender

# Data Description
The sales data contains 11,251 rows and 14 columns:

1. User ID: Unique identifier for each customer.
2. Customer Name: Name of the customer.
3. Product ID: Unique identifier for each product.
4. Gender: Gender of the customer (Male/Female).
5. Age Group: Age group of the customer (e.g., 18-24, 25-34, etc.).
6. Age: Age of the customer.
7. Marital Status: Marital status of the customer (Single/Married).
8. State: State where the customer is located.
9. Zone: Zone where the customer is located.
10. Occupation: Occupation of the customer.
11. Product Category: Category of the product purchased.
12. Orders: Number of orders placed by the customer.
13. Amount: Total amount spent by the customer.

# Technologies Used
- Python 3.1: Programming language used for data analysis and visualization.
- Pandas: Library used for data manipulation and analysis.
- NumPy: Library used for numerical computations.
- Jupyter Notebook: Interactive environment used for data analysis and visualization.

# Repository Structure
The repository contains the following files and directories:
- Rocry Company Analysis.ipynb: Jupyter Notebook file containing the data analysis code.
- RSC.xlsx: Excel file containing the sales data.
