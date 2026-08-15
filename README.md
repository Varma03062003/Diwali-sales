🪔 Diwali Sales Data Analysis

📊 Project Overview

This project performs an Exploratory Data Analysis (EDA) on Diwali sales data to understand customer purchasing behavior, sales patterns, and product performance.

The analysis uses Python to clean, transform, analyze, and visualize the data. The goal is to identify meaningful business insights that can help businesses improve their marketing strategies, customer targeting, and product planning during the Diwali festive season.

🎯 Objectives

The main objectives of this project are:

Analyze customer purchasing behavior during Diwali.
Understand sales distribution based on gender.
Analyze customer age groups and their purchasing patterns.
Study the impact of marital status on purchasing behavior.
Analyze sales across different states and zones.
Understand purchasing behavior across different occupations.
Identify popular product categories.
Analyze the relationship between orders and sales amount.
Generate visual insights using Python.
Derive actionable business insights from the data.
📁 Dataset

The project uses a Diwali sales dataset stored in:

Diwali Sales Data.csv

The original dataset contains 11,251 rows and 15 columns. After removing unnecessary columns and rows containing missing values, 11,239 records remain for analysis.

Dataset Columns
Column	Description
User_ID	Unique customer identifier
Cust_name	Customer name
Product_ID	Unique product identifier
Gender	Customer gender
Age Group	Customer age group
Age	Customer age
Marital_Status	Customer marital status
State	Customer's state
Zone	Geographical zone
Occupation	Customer occupation
Product_Category	Product category
Orders	Number of orders
Amount	Purchase amount

The notebook initially also contains Status and unnamed1 columns, but both are empty and are removed during data cleaning.

🛠️ Technologies Used
Python
Pandas – Data manipulation and analysis
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical data visualization
Jupyter Notebook / Google Colab

The notebook imports NumPy, Pandas, Matplotlib, and Seaborn for the analysis.

🔄 Project Workflow

The analysis follows these major steps:

1. Import Libraries

The required Python libraries are imported:

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
2. Load the Dataset

The CSV dataset is loaded using Pandas:

df = pd.read_csv('Diwali Sales Data.csv', encoding='unicode_escape')
3. Understand the Dataset

Initial analysis includes:

Checking dataset shape
Viewing the first few records
Checking column information
Understanding data types
Generating descriptive statistics
4. Data Cleaning

The following preprocessing steps are performed:

Remove unnecessary empty columns.
Identify missing values.
Remove rows containing missing values.
Check data types.
Perform descriptive statistical analysis.

The notebook identifies 12 missing values in the Amount column and removes them before continuing with the analysis.

5. Exploratory Data Analysis

Different customer and sales characteristics are analyzed using visualizations.

The notebook includes analysis of:

Gender
Age
Age Group
Marital Status
Customer demographics
Product-related information
Sales and order patterns

For example, Seaborn countplot is used to visualize customer distribution by gender and marital status.

6. Data Visualization

Charts are created using Matplotlib and Seaborn to make customer and sales trends easier to understand.

📈 Key Analysis Areas
👩 Gender Analysis

The project analyzes the distribution of customers by gender and compares purchasing behavior between male and female customers.

This helps identify which gender represents a larger portion of the customer base.

👨‍👩‍👧 Age Group Analysis

Customers are categorized into different age groups to understand which segments contribute most to the sales.

This can help businesses design targeted marketing campaigns for specific age groups.

💍 Marital Status Analysis

The project analyzes customer purchasing behavior based on marital status.

This provides insights into whether married or unmarried customers contribute more significantly to the overall customer base.

🗺️ State & Zone Analysis

Customer data is analyzed according to:

State
Geographical zone

This helps identify regions with stronger customer participation and sales activity.

⭐ Conclusion

The Diwali Sales Data Analysis project demonstrates how Python can be used to transform raw sales data into meaningful business insights.

Through data cleaning, exploratory analysis, statistical summaries, and visualization, the project provides a better understanding of customer demographics, purchasing behavior, regional trends, occupations, and product categories.

These insights can help businesses make more informed decisions about marketing, inventory, product promotion, and customer targeting during the Diwali season.

👨‍💻 Author

Varma

GitHub:
Varma03062003 GitHub Profile

Project Repository:
Diwali Sales Analysis Repository
