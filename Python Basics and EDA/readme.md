# FoodHub Data Analysis

This project conducts an in-depth analysis of FoodHub's customer orders and related metrics. The goal is to derive insights that can inform business decisions and improve operational efficiency. The analysis covers various aspects such as order volume, delivery times, popular cuisines, and customer behaviors.

## Project Context

FoodHub is experiencing rapid growth in New York's competitive food delivery market. This analysis explores data from FoodHub’s orders, aiming to understand customer behavior, restaurant performance, and operational efficiency.

## Dataset Information

The dataset includes information on:
- Order details (ID, customer ID, cost, etc.)
- Order preparation and delivery times
- Customer ratings
- Cuisine types

## Analysis Sections

### Data Exploration
1. **Dataset Overview**: Initial inspection, including row/column count and data types.
2. **Missing Values**: Identified and treated missing values.
3. **Statistical Summary**: Calculated key statistical metrics.

### Univariate Analysis
- Distribution and trends of individual variables, such as `cost_of_the_order`, `delivery_time`, and `customer_rating`.

### Key Business Questions
1. **Top Restaurants**: Identifying the most popular restaurants by order volume.
2. **Cuisine Popularity**: Determining the most ordered cuisines, especially on weekends.
3. **Order Costs**: Analyzing the proportion of orders exceeding $20.
4. **Delivery Time**: Average delivery times, with comparisons between weekends and weekdays.

### Multivariate Analysis
- Examines relationships between variables, including correlations and trends, with visualizations like heatmaps and box plots.

## Insights and Recommendations

1. **Encourage Customer Ratings**: Strategies to increase rating submissions.
2. **Optimize Delivery Time**: Suggestions for improving delivery efficiency on weekends.
3. **Promotions**: Potential discounts for high-value customers and top restaurants.

## Conclusion

The analysis provides actionable insights for FoodHub's growth and customer satisfaction enhancement. Recommendations focus on improving rating systems, delivery efficiency, and targeted promotions.

## Libraries and Tools Used

- `pandas`, `numpy`: Data manipulation
- `matplotlib`, `seaborn`: Data visualization
