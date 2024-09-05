# About the dataset:
This dataset contains 9,994 rows and 16 columns. The columns are: Ship Mode, Order Date, Order ID, Segment, Country, City, State, Postal Code, Region, Category, Sub-Category, Product ID, Cost Price, List Price, Quantity, and Discount Percent.

# Problem Statement:
 Clean and analyse global mart sales data

# Problem Objectives:
The objective of this data analysis is to help Global Mart understand their data in order to achieve the following:
- Find the top 10 highest revenue generating products
- find top 5 highest selling products in each region
- find month over month growth comparison for 2022 and 2023
- for each category which month had highest sales?
- which sub category had highest grown by profit in 2023 compare to 2022?

# Data Transformation:
## Step 1: Created Kaggle API
- Go to kaggle and sign in or signup
- Navigate to settings
- Under API Option, create new token and click on continue.
- In your local disk,select user and create a folder called .kaggle, save the kaggle.json inside this folder

## Step 2: Install and import kaggle to download the dataset online
- !pip install kaggle
- follow by import kaggle
- download dataset using kaggle API
- Extract file from zip file

## Step 3: Data Cleaning
- import python libraries(pandas, numpy, seaborn, matplot library)
- read data from file and view the first 20 rows using head(20)
- check the unique ship mode values
- Read the CSV file and handle missing values
- rename columns names and change it to lowercase using (str, lower and replace)
- Drop rows with any missing values

## Step 4: Data Manipulation
- Calculate Discount which is (listprice * discount percent) / 100
- Calculate sale price which is (list price - discount)
- Calculate profit which is (sale price - costprice)
- Convert order date to date data type usinf pd.to_datetime
- Drop cost price, list price and discount percent columns
- Extract month, day and year from the order date

## Step 5: Data Analysis and visualization
- Get Top 10 highest revenue generating products
- Get Top 5 highest selling product in each region
- find month over month growth comparison for 2022 and 2023
- find which month had highest sales for each category
- find the sub category that had highest grown by profit in 2023 compare to 2022?
  
## Insights:

