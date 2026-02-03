# Customer Behavior Analysis and Segmentation

## Overview
This project analyzes customer purchasing behavior and marketing engagement data to identify distinct customer segments and support targeted marketing strategies.  
The goal was to understand customer value drivers, purchasing patterns, and channel effectiveness using exploratory data analysis and clustering techniques.

## Business Problem
A retail company aims to optimize marketing spend and improve customer lifetime value (CLV) by:
- Identifying high-value customers and products
- Understanding how demographics influence spending behavior
- Evaluating the effectiveness of different sales channels (catalog, web, store)

## Dataset
- Size: ~2,240 customers with 29 features
- Key Variables:
  - **Demographics:** Income, education level, number of children at home
  - **Product Spend:** Wines, meat, fish, fruits, sweets
  - **Channels:** Catalog, web, and store purchases
  - **Marketing Engagement:** Campaign responses, recency, loyalty indicators

## Objectives
- Perform exploratory data analysis (EDA) to uncover spending and channel patterns
- Engineer features relevant for customer segmentation
- Apply K-Means clustering to group customers into meaningful segments
- Interpret clusters and provide actionable business recommendations

## Key Tasks Performed
- Data cleaning and preprocessing
- Feature engineering and aggregation of spending variables
- Standardization of numerical features
- Determining optimal number of clusters using evaluation metrics
- K-Means clustering and cluster profiling
- Visualization of customer segments and key behaviors

## Key Insights
- Income is the strongest driver of total customer spending
- Wine and meat account for the highest share of revenue among top customers
- Household size negatively impacts total spending
- Catalog-based customers generate higher average revenue than web-only customers
- A small group of customers contributes a disproportionate share of total revenue

## Customer Segments Identified
- **Connoisseurs:**  
  High income, no children, heavy spend on wine and meat, strong catalog and store engagement

- **Budget Families:**  
  Moderate income, multiple children, frequent web activity but lower basket size, price-sensitive

- **New Loyalists:**  
  Recently acquired customers with mid-level spend and high engagement, strong growth potential

## Tools & Libraries Used
- **Programming Language:** Python
- **Libraries:** Pandas, Scikit-learn, Matplotlib
- **Techniques:**  
  EDA, feature engineering, standardization, K-Means clustering, cluster profiling

## What I Learned
- Applying clustering techniques for real-world customer segmentation
- Translating statistical patterns into business insights
- Evaluating and interpreting unsupervised learning models
- Connecting customer behavior data to marketing and revenue strategies

## Conclusion
This project demonstrates how data-driven customer segmentation can help businesses improve marketing efficiency, personalize engagement, and focus resources on high-value customer groups.
