# Capstone-Project-Onni-Coffee

Author: Anne M
Date: 21 September 2026

This Capstone Project for the Google Data Analytics Certificate course follows the six step data analysis process: 

1.	Ask – define the business problem
2.	Prepare – gather data
3.	Process – clean the data
4.	Analyse – analyse to find the insights
5.	Share – share the results
6.	Act – turn insights into decisions

## ASK

**BUSINESS TASK:**  
1. Performance Comparison Across Locations: How sales performance, profitability and product mix differ across the three store locations (New York, Paris, Tokyo)
2. Product Category Profitability: Which product categories (coffee, tea, bakery, chocolate drinks and syrups) drive the most revenue, profit and margin across locations.
3. Growth Opportunities: Identify how customer purchasing patterns, product performance and location differences can be used to improve revenue and profitability.


**STAKEHOLDER:** Corporate Operations Manager who oversees performance across all store location

## PREPARE
- The Dataset contains coffee shop transaction data from three store locations: New York, Paris, and Tokyo, covering the period from 1 January 2023 to 30 June 2023. The dataset consists of 149,456 sales transactions and was sourced from Kaggle. The original dataset was modified slightly and separated into four Excel files to support relational data modelling and SQL analysis.
- Original dataset from Kaggle: https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales

Datasets should follow the **ROCCC** approach:
- **Reliable:** The dataset contains 149,456 transactions covering six months of operation across three coffee locations.
- **Original:** The dataset was obtained from Kaggle and is therefore secondary data source.
- **Comprehensive:** The dataset includes transaction data, product information, locations, payment methods and product costs, enabling revenue and profitability analysis.
- **Current:** The data covers January – June 2023 and reflects a specific historical period.
- **Cited:** https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales


## PROCESS

Data cleaning was performed to ensure data quality before analysis.

**Excel**

- Combined the datasets into a single analytical file for validation purposes (combining files, VLOOKUP, conditional formatting, changing data types).
- Applied filters to support data review and quality checks.
- Created pivot tables for preliminary data exploration and validation.
- Created charts based on pivot table data.

**SQL (BigQuery)**

- Imported the CSV files into BigQuery.
- Checked for duplicate records and missing values.
- Verified data types (date, quantity, revenue and cost).
- Validated relationships between tables.
- Created calculated fields for revenue, cost, profit and profit margin.
- Combined the tables into a final dataset for analysis.

## ANALYZE

The analysis focused on identifying differences in store performance, product profitability, customer purchasing behaviour and growth opportunities across the three coffee shop locations.

1. Store Performance Comparison: Compared revenue, profit, profit margin and transaction volume across New York, Paris and Tokyo.
2. Sales Trends: Analysed monthly sales performance to identify trends and differences between locations.
3. Product Category Performance: Evaluated revenue, profit and profit margin by product category (coffee, tea, bakery, chocolate drinks and syrups).
4. Top Products: Identified the best-selling and most profitable products across locations.
5. Customer Purchasing Patterns: Analysed sales by hour of day and day of week to identify purchasing behaviour and peak sales periods.
6. Product Mix by Location: Compared customer preferences and product category distribution across locations.
7. Payment Method Analysis: Analysed the distribution of payment methods and differences between locations.
8. Growth Opportunity Analysis: Identified products and categories with strong profitability potential and opportunities for revenue growth.

**Tools Used**
- SQL (BigQuery): Data preparation, KPI calculations and analysis.
- Excel: Preliminary data exploration and validation using Pivot Tables.
- Python: Visualisation of the monthly sales.
- Tableau: Interactive business dashboard.
- PowerPoint: Presentation of findings and recommendations.

## SHARE
- Storyline: https://github.com/Meriluoto-A/Capstone-Project-Onni-Coffee/blob/main/Onni_Coffee_Company_2.pdf
- Tableau: https://public.tableau.com/app/profile/ella.naakka/viz/OnniCoffeeSalesJan-June2023/OnniCoffeeSalesH12023
- Monthly sales figures in Python: https://github.com/Meriluoto-A/Capstone-Project-Onni-Coffee/blob/main/Onni-Coffee.ipynb
