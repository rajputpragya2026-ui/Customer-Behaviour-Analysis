# Customer Shopping Behaviour Analysis

An end-to-end data analytics project that turns raw retail transaction data into actionable business insights — using Python, SQL, and Power BI.

# Overview

This project analyzes customer shopping behaviour to understand what drives revenue, which customers are most valuable, and how subscriptions, discounts, and loyalty affect sales. It covers the full analytics lifecycle: loading and cleaning raw data, exploring it in Python, answering business questions in SQL, and presenting the findings through an interactive Power BI dashboard, a written report, and a presentation.

# Dataset

Size: 3,900 customer transactions across 18 attributes
Fields include: Age, Gender, Location, Item Purchased, Category, Purchase Amount, Review Rating, Subscription Status, Discount Applied, Payment Method, and Frequency of Purchases
Total revenue represented: ₹21.4M
Average review rating: 3.75 / 5

# Tools

Python (Pandas) — data loading, cleaning, and feature engineering
MySQL / SQL — business question analysis
Power BI — interactive dashboard
Microsoft Word / PowerPoint — report and presentation

# Steps

Load the data — Imported the raw dataset into Python with Pandas.
Clean the data — Handled missing values in Age, Gender, Location, Review Rating, and Payment Method; standardised column names; removed a redundant field.
Explore the data (EDA) — Reviewed structure, distributions, and summary statistics; engineered new features (age_group, purchase_frequency_days) to support segmentation.
Run SQL queries — Loaded the cleaned data into MySQL and answered core business questions using joins, aggregations, and grouping.
Build the dashboard — Designed an interactive Power BI dashboard with KPI cards, slicers, and category/segment breakdowns.
Write the report — Documented the methodology, findings, and recommendations.
Create the presentation — Summarised the project as a stakeholder-ready PPT.

# Dashboards

The Power BI dashboard was built for self-serve exploration by non-technical business users:

KPI cards: total customers, average purchase value, average rating
Slicers: Subscription Status, Gender, Category, Shipping Type
Breakdowns: revenue by category, revenue by age group, sales by shipping type

# Results

Male customers generate the majority of revenue despite a similar transaction count, suggesting higher average order values.
The large majority of customers already sit in the "Loyal" tier — retention matters more than acquisition here.
Subscribers and non-subscribers show similar repeat-purchase rates, but there are far fewer subscribers — pointing to an untapped conversion opportunity.
A handful of product categories (accessories, outerwear) rely heavily on discounts to sell, while footwear and apparel earn the strongest ratings at full price.
How to Run

# Python

Install dependencies: pip install pandas sqlalchemy pymysql
Update the dataset file path in the notebook
Run the notebook cells in order to reproduce the cleaning and feature-engineering steps

# MySQL

Create a local MySQL database
Run the notebook's load step (or the SQL script) to populate the customer table
Run the SQL query file to reproduce the analysis

# Power BI

Open the .pbix file in Power BI Desktop
Refresh the data source to point to your local database or dataset

Author
Pragya Singh rajputpragya2026@gmail.com
