# 🪔 Diwali Sales Analysis (EDA using Python)

This project performs an Exploratory Data Analysis (EDA) on a **Diwali sales dataset** to understand customer purchasing behaviour, identify top-performing segments, and derive insights that can help improve marketing and sales strategies during the festive season.

The analysis is done in a Jupyter Notebook using Python libraries such as **pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

## 🎯 Objectives

The main goals of this analysis are to:

- Clean and preprocess the Diwali sales dataset.
- Understand customer demographics and purchasing patterns.
- Identify:
  - Top **age groups**, **genders**, and **marital status** contributing to sales.
  - Top **states** and **occupations** in terms of orders and revenue.
  - Best-selling **product categories** and **products**.
  - Derive **business insights** to help target the right customers with the right products.

 ## 🧾 Dataset Description

The dataset used is Diwali Sales Data.csv.
After cleaning, some of the key columns used in the analysis include:

- Gender – Male/Female
- Age Group – Age buckets (e.g., 18–25, 26–35, etc.)
- Age – Numeric age
- Marital_Status – Marital status of the customer
- State – State of the customer
- Occupation – Profession/industry of the customer
- Product_Category – Category of the purchased product
- Product_ID – Unique ID for each product
- Orders – Number of orders
- Amount – Total purchase amount

### During data cleaning, the following steps are performed:
- Dropping unrelated or blank columns: Status, unnamed1
- Handling missing values.

### 📊 Analysis & Visualizations

The notebook walks through several stages of EDA:

1. Data Understanding & Cleaning

Inspecting the shape, head, and info of the DataFrame.

Dropping unnecessary columns.

Handling null values.

Converting data types.

2. Univariate & Bivariate Analysis

Key visualizations (using Matplotlib and Seaborn):

Gender:

  Count of customers by gender.

  Total sales amount by gender.

Age Group:

  Distribution of customers by age group.

  Amount spent per age group (with gender comparisons).

- State:

  Top 10 states by number of orders.

  Top 10 states by total sales amount.

- Marital Status:

  Distribution of customers by marital status.

  Sales amount by marital status, further split by gender.

- Occupation:

  Count of customers by occupation.

  Sales amount by occupation.

- Product Category & Product ID:

  Number of orders by product category.

  Total sales amount by product category.

  Top 10 most sold products by Product_ID.

### All visualizations are plotted using bar charts and count plots to clearly present trends and comparisons.
