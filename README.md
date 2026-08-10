# Customer Satisfaction Analysis — Olist

## Overview

This project analyzes customer satisfaction for Olist, a Brazilian e-commerce marketplace, with the goal of identifying the key factors associated with customer reviews and translating the findings into actionable business recommendations.

The analysis combines Python, statistical analysis, exploratory data analysis, and data visualization to investigate how factors such as delivery performance, order characteristics, product categories, and customer experience relate to satisfaction.

The project focuses not only on describing customer satisfaction, but also on identifying where improvements could have the greatest impact on the customer experience.

## Business Questions

The analysis aims to answer the following questions:

### What factors are most strongly associated with customer satisfaction?
### How does delivery performance affect customer reviews?
### Which product categories receive the highest and lowest ratings?
### How does the customer experience vary across different dimensions of the Olist marketplace?
### Where should the business prioritize improvements to increase customer satisfaction?

## Dataset
The project uses the Olist Brazilian E-Commerce Public Dataset, which contains information about orders placed between 2016 and 2018.
The dataset includes multiple related tables covering:

* Orders
* Customers
* Sellers
* Products
* Product categories
* Reviews
* Payments
* Geographical information

These datasets were combined and prepared for analysis to create a more comprehensive view of the customer journey — from purchase and delivery to the final customer review.

## Analysis Approach
1. Data Preparation

The analysis begins with data loading and preparation using Pandas.

Key steps include:

* Loading the individual Olist datasets
* Inspecting data structure and data quality
* Handling missing values
* Converting date fields into appropriate formats
* Merging related datasets
* Creating analytical features
* Preparing the final dataset for exploratory analysis
  
2. Exploratory Data Analysis

The project investigates customer satisfaction across several dimensions, including:

* Review scores
* Delivery performance
* Order and delivery times
* Product categories
* Customer and order characteristics
* Geographic distribution
* Payment and purchasing behavior

Visualizations are used to identify patterns, differences between groups, and potential relationships between operational performance and customer satisfaction.

3. Customer Satisfaction Analysis

The analysis then focuses on identifying the factors associated with customer review scores.

Particular attention is given to the relationship between delivery experience and customer satisfaction, as delivery is an important part of the overall e-commerce customer journey.

The analysis compares customer satisfaction across different operational and commercial segments to identify areas with stronger and weaker performance.

## Key Insights

The analysis highlights several important patterns in customer satisfaction:

Delivery experience is an important component of customer satisfaction. Customers experiencing delivery delays tend to provide less favorable reviews.
Customer satisfaction varies considerably across product categories, indicating that product-level and category-level performance can contribute to differences in the customer experience.
Operational performance and customer experience are closely connected, suggesting that improving fulfillment and delivery processes can have benefits beyond operational efficiency.
Low-rated orders can provide useful signals for identifying areas where the business should investigate underlying operational or product-related issues.

The detailed analysis, visualizations, and supporting calculations are available in the project notebook.

## Business Recommendations

Based on the analysis, Olist could focus on the following areas:

* Improve delivery performance

* Monitor delayed orders and identify the main causes of delivery issues, with particular attention to sellers, regions, and product categories with consistently weaker performance.

* Monitor customer satisfaction by category

* Use review scores as an additional performance indicator when evaluating product categories and sellers. Categories with persistently low ratings should be investigated for recurring customer experience problems.

* Identify operational risk areas

* Combine delivery performance with customer reviews to identify segments where operational issues are most likely to negatively affect customer satisfaction.

* Use customer feedback as a performance signal

* Customer reviews can complement traditional operational KPIs by providing direct feedback on the outcome experienced by the customer.

## Tools & Technologies

Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Scikit-learn

## Analysis

Data cleaning & preparation
Exploratory Data Analysis (EDA)
Feature engineering
Statistical analysis
Data visualization
Business-oriented interpretation


Rather than looking at review scores in isolation, the analysis connects customer experience with factors such as delivery performance, products, and marketplace operations, providing a more actionable perspective for business decision-making.
