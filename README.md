# Tableau-Walmart-Sales-Analysis
# Project Title: Analyzing Walmart Sales Performance Across Branches
## Dataset Overview
  * invoice_id: Unique identifier for each transaction.
  * branch: Branch code where the transaction occurred (e.g., "A", "B", "C").
  * city: City where the branch is located.
  * customer_type: Type of customer (e.g., "Normal", "Member").
  * gender: Gender of the customer.
  * product_line: Product category involved in the transaction.
  * unit_price: Price per unit of the product.
  * quantity: Number of units purchased.
  * tax_pct: Tax percentage applied.
  * total: Total amount including tax.
  * date: Date of the transaction.
  * time: Time of the transaction.
  * payment: Payment method used (e.g., "Credit card", "Ewallet", "Cash").
  * cogs: Cost of goods sold.
  * gross_margin_pct: Gross margin percentage.
  * gross_income: Gross income from the transaction.
  * rating: Customer rating of the service/product.
  * time_of_day: Time of day when the transaction occurred (e.g., "Morning", "Afternoon").
  * day_name: Day of the week.
  * month_name: Month of the transaction.

## 1. Problem Statement:
Walmart operates multiple branches across different cities, offering a diverse range of products. Understanding sales performance, customer behavior, and product trends is crucial for informed decision-making. The current dataset provides a detailed record of transactions, including product lines, customer demographics, and sales details. The challenge is to uncover actionable insights from this data to improve revenue, customer satisfaction, and operational efficiency.

## 2. Objectives:
   1. Sales Analysis: Identify top-performing branches, cities, and product lines based on revenue and sales volume.
   2.Customer Behavior: Analyze the customer demographics, including gender and customer type, and their purchasing patterns.
   3.Revenue Insights: Evaluate the impact of payment methods on sales and identify high-gross-margin products.
   4.Time-Based Trends: Examine sales trends by time of day, day of the week, and month to optimize staffing and promotions.
   5.Customer Feedback: Analyze customer ratings to assess satisfaction levels across branches and product lines.

# 3. Project Work flow:
## Data Preparation
  1. Load the dataset into Tableau.
  2. Clean and preprocess the data, ensuring date and time fields are properly formatted.
  3. Create calculated fields:
      * Net Sales (Cogs + Gross Income) for revenue analysis.
      * Profit Margin Percentage if additional insights on profitability are required.
      * Time-based segmentation fields (e.g., week number, hour buckets).

# Visualizations
  ## 1.Overview Dashboard:
    * Total revenue, total sales, average rating.
    * Branch and city performance comparison.

## 2.Product Line Analysis:
    * Sales by product line.
    * Top 3 product categories based on gross income.

## 3.Demographic Insights:
    * Gender-wise and customer-type-wise sales distribution.
    * Rating comparison across demographics.	

## 4.Payment Method Analysis:
    * Payment method popularity and its correlation with sales revenue.

## 5.Time-Based Sales Trends:
    * Hourly, daily, and monthly sales performance.
    * Heatmap showing peak sales periods across days and hours.

## Advanced Features
1. Implement filters for branch, city, product line, and customer type to enable dynamic exploration.
2. Add KPIs (Key Performance Indicators) for revenue, average basket size, and customer satisfaction.

## Final Dashboard

## Insights and Recommendations
1. High-performing branches is C which located in Naypyitaw in which Payment done by Cash Most.
2. Female members contribute the most revenue, with potential for further engagement.
3. Most of the revenue is generated in Saturday week day, which help Walmart management to increase staff focus on Saturday.
4. Afternoon and Evening are most contributing time in a day for Sales.

