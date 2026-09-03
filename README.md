# 📊 Online Retail Data Analysis

> **Module 2 -- Module-End Assignment \| Data Scientist (DS)**

## 📌 Project Overview

This project analyzes an **Online Retail Dataset** containing customer
transactions, product details, quantities, prices, and purchase dates.

The goal is to clean and preprocess the raw data, perform exploratory
data analysis (EDA), create useful features, analyze customer and
product behavior, visualize important patterns, and derive meaningful
business insights.

------------------------------------------------------------------------

## 🎯 Objectives

-   Clean and preprocess real-world retail data
-   Handle missing values, duplicates, and invalid values
-   Create meaningful derived features
-   Perform exploratory data analysis
-   Aggregate and analyze customer, country, and product data
-   Perform statistical analysis
-   Create clear and informative visualizations
-   Identify important business trends and insights
-   Maintain the project using Git and GitHub

------------------------------------------------------------------------

## 🗂️ Project Structure

``` text
Module-End Assignment/
│
├── data/
│   └── Online Retail.xlsx
│
├── notebooks/
│   └── Module_2_Module_End_Assignment.ipynb
│
├── README.md
│
└── requirements.txt
```

------------------------------------------------------------------------

## 🛠️ Technologies & Libraries

  Tool / Library     Purpose
  ------------------ ----------------------------
  Python             Programming and analysis
  NumPy              Numerical operations
  Pandas             Data cleaning and analysis
  Matplotlib         Data visualization
  Seaborn            Statistical visualization
  Jupyter Notebook   Interactive development
  Git                Version control
  GitHub             Project hosting

------------------------------------------------------------------------

# 🔄 Project Workflow

## 1. Data Import & Setup

The Online Retail dataset is loaded using Pandas.

Initial exploration includes:

-   `head()`
-   `tail()`
-   `shape`
-   `columns`
-   `info()`

`InvoiceDate` is converted into datetime format for time-based analysis.

------------------------------------------------------------------------

## 2. Data Cleaning

The raw dataset is cleaned to improve data quality.

The following operations are performed:

-   Handle missing `CustomerID` values
-   Remove duplicate records
-   Remove invalid negative quantities
-   Remove records with invalid/zero `UnitPrice`
-   Reset the dataframe index

------------------------------------------------------------------------

## 3. Feature Engineering

New features are created to support deeper analysis.

### Created Features

-   `TotalPrice` = `Quantity × UnitPrice`
-   `Year`
-   `Month`
-   `Day`
-   `Hour`
-   `DayName`
-   `CustomerSegment`
-   `OrderSize`
-   `DayType`

These features help analyze sales patterns, customer behavior, and
time-based trends.

------------------------------------------------------------------------

## 4. Data Exploration

Exploratory analysis is performed using:

-   `describe()`
-   `value_counts()`
-   `unique()`
-   `nunique()`
-   `groupby()`

The analysis covers:

-   Country-wise sales
-   Monthly sales
-   Product performance
-   Customer segments
-   Order sizes
-   Weekday vs weekend behavior

------------------------------------------------------------------------

## 5. Data Wrangling

Data is aggregated and sorted to identify high-performing areas.

### Analysis includes:

-   Country-wise total sales
-   Customer-wise total spending
-   Product-wise sales
-   Total quantity
-   Number of orders
-   Number of customers
-   Top customers
-   Top countries
-   Top products

Pivot tables are also used to restructure data where appropriate.

------------------------------------------------------------------------

## 6. Statistical Analysis

Statistical measures are calculated for:

-   `Quantity`
-   `UnitPrice`
-   `TotalPrice`

### Measures Used

-   Mean
-   Median
-   Mode
-   Standard deviation
-   Variance
-   25th percentile
-   50th percentile
-   75th percentile

These measures help understand the distribution and variability of the
retail data.

------------------------------------------------------------------------

# 📈 7. Data Visualization

A minimum of **8 visualizations** is created using Matplotlib and
Seaborn.

### Matplotlib

1.  📈 Line Chart -- Monthly Sales Trend
2.  📊 Bar Chart -- Top Countries by Sales
3.  📊 Histogram -- Quantity Distribution
4.  📦 Box Plot -- Total Price Distribution

### Seaborn

5.  📊 Count Plot -- Customer Segment Distribution
6.  🎻 Violin Plot -- Total Price by Day Type
7.  🔥 Heatmap -- Correlation Analysis
8.  🔵 Pair Plot -- Numerical Feature Relationships

All plots include appropriate titles, labels, and readable presentation.

------------------------------------------------------------------------

# 💡 8. Business Insights

The analysis is used to identify:

-   🌍 Top-performing country
-   📅 Best sales month
-   ⏰ Peak sales time
-   👥 Customer behavior
-   💰 High-value customers
-   🛍️ Top-performing products

### Key Results

> **Top Country:** *Add result after running the notebook*

> **Best Sales Month:** *Add result after running the notebook*

> **Peak Sales Time:** *Add result after running the notebook*

> **Top Product:** *Add result after running the notebook*

> **High-Value Customers:** *Add result after running the notebook*

These values should be updated using the actual outputs generated by the
notebook.

------------------------------------------------------------------------

# 📊 Expected Outcomes

This project provides an understanding of:

-   Retail sales trends
-   Customer purchasing behavior
-   Product performance
-   Country-wise sales performance
-   Order patterns
-   Revenue distribution
-   High-value customers

The analysis can help businesses understand sales patterns and identify
areas that require attention or further investigation.

------------------------------------------------------------------------

# 🚀 How to Run the Project

## 1. Clone the repository

``` bash
git clone <your-github-repository-link>
```

## 2. Open the project

``` bash
cd Module-End-Assignment
```

## 3. Install required libraries

``` bash
python -m pip install -r requirements.txt
```

## 4. Open the notebook

``` bash
jupyter notebook
```

Then open:

``` text
notebooks/Module_2_Module_End_Assignment.ipynb
```

## 5. Run the notebook

Run the cells in order from **Task 1 to Task 8**.

------------------------------------------------------------------------

# 🔧 Version Control

Git is used to maintain project history and version control.

Example commands:

``` bash
git init
git add .
git commit -m "Complete Module 2 assignment"
git branch -M main
git remote add origin <your-repository-link>
git push -u origin main
```

------------------------------------------------------------------------

# 📁 Assignment Deliverables

The repository contains:

-   ✅ Complete Python analysis code
-   ✅ Dataset (where applicable)
-   ✅ Data visualizations
-   ✅ README documentation
-   ✅ `requirements.txt`
-   ✅ Git/GitHub version control

------------------------------------------------------------------------

# 👨‍💻 Project Information

**Project:** Online Retail Data Analysis\
**Module:** Module 2 -- Data Scientist (DS)\
**Assignment:** Module-End Assignment\
**Language:** Python\
**Repository:** GitHub

------------------------------------------------------------------------

## ⭐ Conclusion

This project demonstrates a complete data analysis workflow starting
from **raw retail data** and progressing through **data cleaning,
feature engineering, exploration, wrangling, statistical analysis,
visualization, and business insight generation**.

The project also demonstrates the use of **Git and GitHub for structured
project management and version control**.
