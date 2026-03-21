# customer_behavior_analysis

This project analyzes customer shopping behavior using transactional data to uncover patterns in customer purchases, product preferences, and spending habits.
The workflow combines Python for data processing and exploratory data analysis (EDA), SQL for business analysis, and Power BI for data visualization. The goal is to transform raw data into meaningful insights that support business decision-making.

Dataset

The dataset contains customer transaction records including demographic information, purchase details, and shopping behavior.
Dataset Details
Total Records: 3,900
Total Columns: 18

Key Features

Customer Information: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency
Customer Feedback: Review Rating
Shipping Information: Shipping Type
Some missing values were identified in the dataset and handled during the data cleaning process.

Tools & Technologies      

Tool	Purpose
Python	Data loading, cleaning, and exploratory analysis
Pandas / NumPy	Data manipulation and preprocessing
Matplotlib / Seaborn	Data visualization during EDA
SQL (PostgreSQL / MySQL / SQL Server)	Business analysis queries
Power BI	Interactive dashboard and visualization
Gamma	Creating presentation slides
Jupyter Notebook	Analysis environment

Project Steps

1. Data Loading

Imported the dataset using Python (Pandas,Numpy)
Checked dataset structure using:
df.head()
df.info()
df.describe()

2. Data Cleaning

Identified and handled missing values
Standardized column names for consistency
Removed redundant or unnecessary columns
Ensured correct data types

3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand:
Customer demographics
Purchase distribution
Product category performance
Impact of discounts and subscriptions

4. SQL Business Analysis

The cleaned dataset was loaded into a database for deeper analysis using SQL.

Example analyses include:
Revenue by gender
Top products by rating
Customer segmentation
Comparison of subscription vs non-subscription spending
Revenue distribution by age group

5. Data Visualization

Built an interactive Power BI dashboard to visualize key metrics and trends for better decision-making.

6. Reporting

Insights from the analysis were documented in:
A business analysis report
A presentation created using Gamma
Dashboard
The Power BI dashboard provides visual insights into customer behavior and business performance.
Key Dashboard Metrics
Total Revenue
Revenue by Gender
Revenue by Age Group
Top Products
Customer Segmentation
Subscription vs Non-Subscription Analysis
Shipping Type Comparison

The dashboard allows users to quickly explore trends and identify opportunities for business growth.

Results & Insights

Key insights from the analysis include:
Subscription customers tend to spend more on average.
Repeat customers contribute significantly to overall revenue.
Discounts influence purchasing behavior but should be managed carefully to protect profit margins.
Certain products have high ratings but lower sales, indicating potential marketing opportunities.
