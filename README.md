# Sales Analysis

## Overview

Analysis of customer behavior, retention, and lifetime value for an e-commerce company to improve customer retention and maximize revenue.

## Business Questions


1. **Cohort Analysis:** How do different customer groups generate revenue?

2. **Customer Segmentation:** Who are our most valuable customers?

3. **Retention Analysis:** Which customers haven't purchased recently?

## Analysis Of Business Questions

### 1. Customer Revenue by Cohort
**🖥️ Query**: [1.Customer_Revenue_By_Cohort.sql](1.Customer_Revenue_By_Cohort.sql)


- Grouped customers into cohorts based on the year of their first purchase

- Calculated total revenue and customer count for each cohort

- Evaluated revenue trends and customer behavior over time within each cohort

### 2.Customer Segmentation Analysis
**🖥️ Query**: [2.Customer_Segmentation_Analysis.sql](2.Customer_Segmentation_Analysis.sql)

- Divided customers into groups based on their **lifetime Value**  
- Labeled each customer as **High**, **Medium**, or **Low value** 
- Calculated key metrics: **total revenue** 

### 3.Customer Retention Analysis
**🖥️ Query**: [3.Customer_Retention_Analysis.sql](3.Customer_Retention_Analysis.sql)

- Identified customers likely to **churn** 
- **Reviewed** recent purchase behaviors  
- Computed metrics tailored to **individual customers**  



## Technical Details

- **Analysis Tool** : PostgreSQL

- **Visualization** : Python , ChatGPT
