# customer_behavior_analysis_and_segmentation

## Overview
This project analyzes customer purchasing behavior and marketing engagement to identify segments and guide targeted marketing strategies. The focus is on understanding who the best customers are, what they buy, and which channels drive the most value.

## Business Context
A retail company wants to:
- Reduce inefficient marketing spend.
- Identify high‑value customers and products.
- Understand the impact of demographics and channels (catalog, web, store) on revenue.

## Dataset
- Variables include:
  - Demographics: Income, education level, number of kids at home.
  - Product spend: Wines, Meat, Fish, Fruit, Sweets.
  - Channel usage: Catalog purchases, Web purchases, Store purchases.
  - Marketing: Campaign responses, enrollment recency, loyalty indicators.
- Size: ~ 2240 customers with 29 features.

## Objectives
- Perform EDA to understand spending patterns and channel behavior.
- Engineer features relevant for segmentation and marketing decisions.
- Use K‑Means clustering to group customers into meaningful segments.
- Provide actionable recommendations to improve revenue and customer lifetime value (CLV).

## Tools and Libraries Used
- Language: Python (Visual Studio Code)
- Libraries:
  - pandas and numpy for data handling
  - scikit-learn for model training, preprocessing, and evaluation
  - matplotlib and seaborn for exploratory data analysis and plots
- Techniques:
  - Data cleaning and feature engineering
  - Standardization of numeric variables
  - K‑Means clustering and cluster evaluation
  - Cluster profiling and visualization

## Key Insights
- Income is the strongest predictor of total spend.
- Wines and Meat drive the most spending among top customers.
- For each additional child in the household, total spending tends to decrease.
- Catalog purchasers have higher value per customer than web‑only purchasers.
- A small top tier of customers contributes a large share of revenue.

## Customer Segments
- **The Connoisseurs:** High income, no kids, heavy spend on wine and meat, strong catalog and store engagement.
- **The Budget Families:** Moderate income, multiple kids, high web traffic but lower basket size, price‑sensitive.
- **The New Loyalists:** Recently acquired customers with mid‑level spend and high engagement – key for growth.
