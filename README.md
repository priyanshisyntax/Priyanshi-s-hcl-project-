# Priyanshi-s-hcl-project-
#Wholesale Customer Spending EDA

(Exploratory Data Analysis Project)

A beginner-friendly data analysis project for B.Tech 1st Year – Computer Science and Engineering students.

This project analyses wholesale customer spending patterns across different product categories, sales channels and regions using Python, Pandas, NumPy and Matplotlib.

Student Details

- Name: Priyanshi Mishra
- Roll Number: 2026B01010298
- Class/Section: CSE 11 (Batch 11)
- Course: B.Tech – Computer Science and Engineering
- Faculty/Guide: Faizan Khawar
- Submission Date: 21 November 2026

Business Problem

Wholesale businesses deal with customers from different sales channels and geographical regions. Understanding their purchasing patterns helps identify which product categories contribute most to overall spending.

The objective of this project is to analyse customer spending behaviour and discover useful patterns from the Wholesale Customers dataset.

Questions Answered

1. How many customers belong to each sales channel and region?
2. Which product category has the highest total spending?
3. What are the mean, median, minimum and maximum spending values for each product category?
4. Who are the top 10 customers with the highest total spending?
5. How does average product-category spending differ between Channel 1 and Channel 2?

Dataset

Dataset Name: Wholesale Customers Dataset

File Name: "Wholesale customers data.csv"

The dataset contains 440 rows and 8 columns.

Dataset Columns

Column| Description
Channel| Sales channel (Horeca or Retail)
Region| Customer's geographical region
Fresh| Spending on fresh products
Milk| Spending on milk products
Grocery| Spending on grocery products
Frozen| Spending on frozen products
Detergents_Paper| Spending on detergents and paper
Delicassen| Spending on delicatessen products

Dataset Categories

- Channel 1 – Horeca (Hotel, Restaurant and Café)
- Channel 2 – Retail
- Region 1 – Lisbon
- Region 2 – Oporto
- Region 3 – Other regions

Project Structure

Wholesale-Customer-Spending-EDA/
│
├── Wholesale_Customer_EDA.ipynb
│
├── Wholesale customers data.csv
│
├── Project_Documentation.pdf
│
├── README.md
│
└── INDEX.md

Steps Followed

1. Data Loading: Import the CSV dataset using Pandas.
2. Data Inspection: Examine the dataset using head(), tail(), info() and describe().
3. Data Cleaning Checks: Identify missing values and duplicate records.
4. Statistical Analysis: Calculate mean, median, minimum, maximum and total spending using NumPy and Pandas.
5. Data Analysis: Apply value_counts(), groupby() and sort_values().
6. Customer Analysis: Identify the top 10 highest-spending customers.
7. Data Visualisation: Create bar charts using Matplotlib.
8. Insights and Observations: Interpret the results and draw conclusions.

Key Findings

- The dataset contains 440 customer records and 8 columns.
- Channel 1 has 298 customers, while Channel 2 has 142 customers.
- Fresh products have the highest total spending of 5,280,131.
- Fresh products also have the highest average spending, approximately 12,000.30.
- Grocery is the second-highest category in terms of total spending.

Charts

The project includes the following visualisations:

1. Customer Count by Channel
2. Total Spending by Product Category

Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Git and GitHub

Conclusion

This project provides an understanding of wholesale customer spending patterns through Exploratory Data Analysis.

The analysis shows differences in customer distribution across sales channels and spending across product categories. It also identifies high-spending customers and presents useful insights through statistical calculations and visualisations.

Author

Priyanshi Mishra

B.Tech – Computer Science and Engineering
CSE 11 (Batch 11)
Roll Number: 2026B01010298

Faculty/Guide: Faizan Khawar
