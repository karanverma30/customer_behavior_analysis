Customer Shopping Behavior Analysis
Overview
This project focuses on analyzing customer shopping behavior using Python, SQL, and Power BI. The goal of the project is to extract meaningful insights from customer purchase data by performing data cleaning, exploratory data analysis (EDA), SQL-based analysis, and interactive dashboard visualization.

The project demonstrates end-to-end data analytics workflow including:

Data loading and preprocessing

Exploratory Data Analysis (EDA)

SQL query execution using multiple database systems

Dashboard creation in Power BI

Report and presentation preparation

This project is designed to showcase practical data analytics skills and business insight generation.

Dataset
The dataset contains customer shopping behavior information such as:

Customer demographics

Product categories

Purchase amounts

Payment methods

Discount usage

Shopping frequency

Gender and age details

The dataset was analyzed to identify purchasing trends, customer patterns, and revenue insights.

Tools & Technologies Used
Programming & Analysis
Python

Pandas

NumPy

Matplotlib

Seaborn

Database Technologies
PostgreSQL

MySQL

SQL Server

Visualization & Reporting
Power BI

Gamma AI (PPT Creation)

Development Environment
Jupyter Notebook

VS Code

Project Workflow
1. Data Loading
Imported dataset using Python

Loaded data into Pandas DataFrame

Inspected rows, columns, and data types

2. Data Cleaning
Removed duplicate records

Handled missing values

Corrected inconsistent data

Converted data types where required

3. Exploratory Data Analysis (EDA)
Performed analysis to understand:

Customer purchase trends

Revenue by gender

Product category performance

Discount impact on sales

Shopping frequency patterns

Created visualizations using:

Bar Charts

Pie Charts

Histograms

Heatmaps

SQL Analysis
The cleaned dataset was imported into:

PostgreSQL

MySQL

SQL Server

SQL queries were written to perform:

Revenue analysis

Customer segmentation

Top-selling product analysis

Average purchase calculations

Discount usage insights

Gender-wise spending analysis

Example SQL operations:

SELECT gender, SUM(purchase_amount) AS revenue
FROM customer
GROUP BY gender;
Power BI Dashboard
An interactive Power BI dashboard was created to visualize:

Total Revenue

Customer Distribution

Product Category Performance

Purchase Trends

Discount Analysis

Payment Method Insights

Dashboard features:

Interactive filters

KPI cards

Dynamic charts

Business insights visualization

Results & Insights
Key insights generated from the analysis include:

Identification of top-performing product categories

Customer spending patterns by gender

Impact of discounts on customer purchases

Popular payment methods among customers

Trends in shopping frequency and purchasing behavior

The project helps businesses make data-driven decisions to improve customer engagement and sales performance.
