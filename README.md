# Exploratory-Data-Analysis-of-Retail-Data
Portfolio Project: Online Retail Exploratory Data Analysis with Python
Overview
This project involves an exploratory data analysis (EDA) of a transactional dataset from an online retail store. The goal is to uncover insights into sales trends, customer behavior, and popular products to help the company make data-driven decisions.

Dataset
The dataset used is the "Online Retail" dataset, an Excel file (Online Retail.xlsx) containing transactional data from 2010 to 2011. It includes the following columns:

InvoiceNo: Invoice number of the transaction
StockCode: Unique code of the product
Description: Description of the product
Quantity: Quantity of the product in the transaction
InvoiceDate: Date and time of the transaction
UnitPrice: Unit price of the product
CustomerID: Unique identifier of the customer
Country: Country where the transaction occurred
Project Objectives
Describe data to answer key questions to uncover insights.
Gain valuable insights that will help improve online retail performance.
Provide analytic insights and data-driven recommendations.
Analysis Performed
The notebook performs the following steps:

Data Loading: Loads the Online Retail.xlsx dataset into a pandas DataFrame.
Data Cleaning: Handles missing values (by dropping rows with missing Description or CustomerID) and checks for and removes duplicate rows.
Basic Data Statistics: Explores basic statistics of the dataset, including measures of central tendency and dispersion for numerical columns like UnitPrice.
Data Visualization: Generates visualizations (e.g., histograms) to understand the distribution of key variables like UnitPrice.
Analyze Trends: Analyzes sales trends over time by extracting month, year, and day of the week from the InvoiceDate and calculating total sales by month and day.
Explore Top Selling Products and Countries: Identifies the top 10 selling products based on quantity and the top 10 selling countries based on total sales.
Identify Outliers and Anomalies: Uses box plots to visualize potential outliers in the Quantity and UnitPrice columns and discusses their potential impact.
Key Findings and Recommendations
Based on the analysis, key findings regarding sales trends, top products/countries, and outliers are discussed. Recommendations are provided based on these findings to optimize store operations, improve customer satisfaction, and drive strategic business decisions.

How to Run the Notebook
Ensure you have the Online Retail.xlsx file in the same directory as the notebook or provide the correct path to the file.
Make sure you have the necessary libraries installed (pandas, seaborn, matplotlib).
Run the cells sequentially to perform the data loading, cleaning, analysis, and visualization steps.
