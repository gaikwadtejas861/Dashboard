# 🛍️ Customer Shopping Behavior Analysis

An end-to-end **Data Analytics** project that analyzes customer shopping behavior using **Python, PostgreSQL, SQL, and Power BI**. The project focuses on data cleaning, exploratory data analysis (EDA), business query analysis, interactive dashboard creation, and business recommendations to support data-driven decision making.

---

## 📌 Overview

This project analyzes **3,900 customer purchase records** to understand shopping patterns, customer demographics, purchasing behavior, subscription trends, and product performance.

The workflow covers the complete data analytics pipeline:

- Data Loading & Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- PostgreSQL Database Integration
- SQL Business Analysis
- Interactive Power BI Dashboard
- Business Report
- Project Presentation

---

## 📂 Dataset

**Dataset:** Customer Shopping Behavior

**Dataset Information**

- **Rows:** 3,900
- **Columns:** 18
- Customer Demographics
- Purchase Details
- Shopping Behavior
- Subscription Information
- Product Categories
- Shipping Details
- Review Ratings

The dataset required handling missing values, standardizing column names, creating new features, and preparing data for SQL and Power BI analysis.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- PostgreSQL
- SQL
- SQLAlchemy
- Power BI
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading

- Imported dataset using Pandas
- Inspected data types and structure
- Generated summary statistics

### 2. Data Cleaning

- Handled missing values
- Imputed missing Review Ratings using category median
- Renamed columns to snake_case
- Removed redundant columns
- Checked data consistency

### 3. Feature Engineering

Created new analytical features including:

- Age Groups
- Purchase Frequency (Days)

### 4. Exploratory Data Analysis (EDA)

Performed analysis on:

- Customer demographics
- Purchase distribution
- Product categories
- Review ratings
- Spending patterns
- Subscription behavior

### 5. PostgreSQL & SQL Analysis

Loaded cleaned data into PostgreSQL and solved business problems using SQL.

Some analyses include:

- Revenue by Gender
- High Spending Discount Users
- Top Rated Products
- Shipping Type Comparison
- Subscribers vs Non-Subscribers
- Discount Dependency Analysis
- Customer Segmentation
- Top Products by Category
- Revenue by Age Group
- Repeat Buyer Analysis

### 6. Power BI Dashboard

Built an interactive dashboard containing:

- KPI Cards
- Revenue Analysis
- Category-wise Sales
- Age Group Analysis
- Subscription Insights
- Customer Segmentation
- Interactive Filters & Slicers

### 7. Documentation

Prepared:

- Detailed Project Report
- PowerPoint Presentation
- SQL Script
- Jupyter Notebook

---

## 📈 Dashboard Highlights

The Power BI dashboard provides interactive insights including:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Subscription Distribution
- Dynamic Filters for Gender, Category, Shipping Type, and Subscription Status

---

## 🔍 Key Results

- Identified customer purchasing trends across product categories.
- Segmented customers into New, Returning, and Loyal groups.
- Compared subscriber and non-subscriber purchasing behavior.
- Measured revenue contribution by gender and age group.
- Analyzed the impact of discounts on customer spending.
- Identified top-rated and best-selling products.
- Generated actionable business recommendations using SQL and Power BI insights. 

---

## 📁 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
├── cleaned_customer_shopping_behavior.csv
├── customer_shopping_behavior_analysis.ipynb
├── customer_shopping_behavior_analysis.sql
├── customer_shopping_behavior_dashboard.pbix
├── Customer Shopping Behavior Analysis Report.pdf
├── Customer_Shopping_Behavior_Analysis_Presentation.pptx
└── README.md
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/gaikwadtejas861/customer_shopping_behavior_analysis.git

cd customer_shopping_behavior_analysis
```

### Install Dependencies

```bash
pip install pandas sqlalchemy psycopg2
```

### Run Python Notebook

Open:

```
customer_shopping_behavior_analysis.ipynb
```

Run all cells to:

- Clean data
- Perform EDA
- Generate engineered features
- Load data into PostgreSQL

### Execute SQL Queries

Import the cleaned dataset into PostgreSQL and execute:

```
customer_shopping_behavior_analysis.sql
```

### Open Power BI Dashboard

Open:

```
customer_shopping_behavior_dashboard.pbix
```

using Microsoft Power BI Desktop.

---

## 📄 Project Deliverables

- ✅ Python EDA Notebook
- ✅ Cleaned Dataset
- ✅ PostgreSQL SQL Queries
- ✅ Interactive Power BI Dashboard
- ✅ Project Report
- ✅ PowerPoint Presentation

---

## 🎯 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- SQL Query Writing
- PostgreSQL
- Data Visualization
- Power BI Dashboarding
- Business Analytics
- Data Storytelling

---

## 👨‍💻 Author

**Tejas Gaikwad**

- LinkedIn: *www.linkedin.com/in/tejasgaikwad1608*
- GitHub: *https://github.com/gaikwadtejas861*
