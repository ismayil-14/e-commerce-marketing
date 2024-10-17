# E-Commerce Marketing Optimization: README
## Project Overview
This project aims to optimize the marketing budget for an e-commerce company specializing in electronic products in Ontario, Canada. The firm experienced heavy marketing investments but has seen suboptimal returns. The task involves building machine learning (ML) and deep learning (DL) models to analyze product categories and uncover insights to improve revenue outcomes.

## Business Objective
To streamline or strategically reallocate the marketing budget to achieve higher ROI by understanding the impact of marketing strategies on revenue, customer behavior, and demand across three product subcategories:

Camera Accessory
Home Audio
Gaming Accessory
Our primary goal is to identify drivers of revenue and recommend actionable steps for marketing optimizations at the weekly level.

## Models Developed
1. Logarithmic & Multiplicative Models
Used for interpretability of marketing levers (log transformations).
2. Machine Learning Models
Random Forest Regression: To assess variable importance for GMV
XGBoost: For robust predictions across non-linear features

3. Deep Learning Models
ANN (Artificial Neural Networks): To capture complex relationships between climate, marketing, and GMV

## Key Insights and Recommendations

### Payment Preferences:

75% of customers prefer Cash on Delivery (COD) over prepaid orders, indicating a significant reliance on COD as a payment mode.
### Seasonal Order Trends:

Autumn sees the highest number of orders (648,203) followed by Winter (307,183), Spring (294,881), and Summer (232,034).
Customers tend to place more orders during colder months, especially early and mid-winter.
### Top Product Categories:

Entertainment products dominate with 899,294 orders, followed by Gaming Hardware (327,174 orders) and Camera Accessories (255,838 orders).
### Order Value Distribution:

Orders below ₹1,000 account for 634,829 transactions. As the price increases, order volume drops, with only 73,719 orders exceeding ₹5,000.
### Holiday Impact on Sales:

Sales on holidays are typically lower, but there is a spike in orders just before holidays.
### Pay Date Effect:

1st and 15th of the month account for only 6% of total orders, but the ranges of 1-3 and 14-17 together cover 28% of total orders.
### Weather Conditions and Delays:

Orders face delays when:
Rain exceeds 10mm
Snowfall exceeds 5mm
Snow on ground exceeds 5mm
