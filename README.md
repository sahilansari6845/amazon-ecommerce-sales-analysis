# Amazon E-Commerce Sales Analysis

## Project Overview

This project analyzes Amazon e-commerce sales data to identify revenue trends, customer behavior, product performance, and order cancellation patterns.

The analysis covers sales data from 2020 to 2024 and uses Python-based data analysis and visualization techniques to generate actionable business insights.

## Objectives

- Analyze revenue trends over time
- Compare revenue performance across product categories
- Identify top-performing products
- Analyze customer purchase behavior
- Evaluate order cancellation rates
- Identify high-risk state and category combinations
- Understand payment method patterns

## Key Business Insights

- Electronics generated the highest category revenue at approximately **$15.58M**.
- Revenue fluctuated across the 2020–2024 period, with negative year-over-year growth in 2021 and 2024.
- Repeat customers contributed approximately **86.43% of total revenue**.
- **Memory Card 128GB** generated the highest revenue among the analyzed products at approximately **$1.94M**.
- **Gaming Mouse** had the highest cancellation rate among the top-revenue products at approximately **3.78%**.
- The overall order cancellation rate was approximately **3.03%**.
- Some State × Category combinations showed cancellation rates above **4%**.

## Analysis Performed

### 1. Category Revenue Analysis
Compared revenue and order volume across major product categories.

### 2. Monthly & Yearly Sales Trends
Analyzed monthly revenue patterns and yearly revenue growth from 2020 to 2024.

### 3. Customer Analysis
Segmented customers into:
- Repeat Customers
- One-Time Customers

and compared their order volume and revenue contribution.

### 4. Product Performance
Identified the highest-revenue products and analyzed their cancellation rates.

### 5. Payment Method Analysis
Compared cancellation rates across:
- Credit Card
- Debit Card
- UPI
- Amazon Pay
- Cash on Delivery
- Net Banking

### 6. Cancellation Risk Analysis
Analyzed cancellation rates across State × Category combinations to identify areas requiring further investigation.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization

## Project Structure

```text
Amazon-Ecommerce-Sales-Analysis/
│
├── Amazon_Ecommerce_Sales_Analysis.ipynb
├── Amazon.csv
├── README.md
└── .gitignore