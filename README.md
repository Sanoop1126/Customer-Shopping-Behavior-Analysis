# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using retail transaction data to identify purchasing patterns, customer segments, and revenue trends. The goal of the analysis is to generate meaningful business insights that can help improve marketing strategies, customer engagement, and product positioning.

The project combines **Python for data exploration, SQL for business analysis, and Power BI for visualization** to transform raw transactional data into actionable insights.

---

## Dataset Information

The dataset contains customer transaction records along with demographic and shopping behavior information.

**Dataset Summary**

* Total Records: 3,900
* Total Columns: 18

**Key Features**

**Customer Information**

* Customer ID
* Age
* Gender
* Location
* Subscription Status

**Purchase Details**

* Item Purchased
* Category
* Purchase Amount
* Season
* Size
* Color

**Shopping Behavior**

* Discount Applied
* Previous Purchases
* Review Rating
* Shipping Type
* Frequency of Purchases

---

## Tools & Technologies Used

* **Python** – Data exploration and preprocessing
* **SQL** – Business analysis queries
* **Power BI** – Dashboard visualization
* **Jupyter Notebook** – Data analysis environment

---

## Project Workflow

### 1. Data Exploration using Python

* Loaded dataset using Pandas
* Checked dataset structure and summary statistics
* Identified missing values and data inconsistencies
* Prepared data for SQL analysis

### 2. Business Analysis using SQL

SQL queries were written to answer key business questions such as:

* Revenue comparison between male and female customers
* Identifying customers spending above average while using discounts
* Finding top-rated products based on review ratings
* Comparing purchase amounts between shipping types
* Analyzing subscriber vs non-subscriber spending behavior
* Identifying discount-dependent products
* Customer segmentation based on purchase history
* Top products within each category
* Relationship between repeat buyers and subscriptions
* Revenue contribution by different age groups

---

## Key Insights

* Male customers generated slightly higher total revenue.
* Customers using **Express Shipping** tend to spend more on average.
* **Young adult customers contribute the highest revenue share.**
* Loyal customers represent the largest segment of buyers.
* Several products are frequently purchased with discounts.
* Repeat buyers are more likely to be **non-subscribers**.

---

## Power BI Dashboard

An interactive Power BI dashboard was created to visualize key insights from the data.

The dashboard includes visualizations such as:

* Revenue by Gender
* Revenue by Age Group
* Customer Segmentation
* Top Products by Category
* Shipping Type Comparison
* Subscription Status Analysis


---

## Business Recommendations

Based on the analysis, the following strategies could improve business performance:

* Promote **subscription programs** to increase customer retention.
* Focus marketing campaigns on **high-revenue age groups**.
* Highlight **top-rated and best-selling products** in promotions.
* Optimize **discount strategies** to balance revenue and profit margins.
* Introduce **loyalty programs** to encourage repeat purchases.

---

## Repository Structure

```
Customer-Shopping-Behavior-Analysis
│
├── dashboard
│   └── customer_analysis_dashboard.pbix
│
├── sql
│   └── customer_queries.sql
│
├── notebooks
│   └── analysis.ipynb
│
├── images
│   └── dashboard_preview.png
│
├── .gitignore
├── .env.example
└── README.md
```

---

## Author

**Sanoop**

This project was developed as part of a **data analytics portfolio project** to demonstrate skills in **Python, SQL, and Power BI**.
