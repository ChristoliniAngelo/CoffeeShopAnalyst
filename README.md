
# Coffee Shop Sales Analysis

This project aims to analyze sales data from a coffee shop to derive insights and suggest business strategies. The dataset used is sourced from Kaggle and contains transaction details over a period of several months, including information on sales quantities, times, product categories, and store locations.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Analysis](#analysis)
- [Insights](#insights)
- [Business Strategies](#business-strategies)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

## Project Overview
In this project, we analyze coffee shop sales to uncover trends in customer behavior, product popularity, and sales patterns across different times of day. The insights are intended to guide business strategy and improve the coffee shop's performance.

## Dataset
The data for this project is sourced from [Kaggle's Coffee Shop Sales dataset](https://www.kaggle.com/). It includes the following columns:
- `transaction_id`: Unique identifier for each transaction
- `transaction_date`: Date of the transaction
- `transaction_time`: Time of the transaction
- `transaction_qty`: Quantity of items sold
- `store_id`: Unique identifier for each store
- `store_location`: Location of the store
- `product_id`: Unique identifier for each product
- `unit_price`: Price per unit of product
- `product_category`: Category of the product (e.g., coffee, tea, bakery)
- `product_type`: Type of the product within a category
- `product_detail`: Specific details about the product

## Analysis
The analysis focuses on the following areas:
1. **Top-Selling Products**: Identifying the most popular product categories (e.g., coffee, tea, bakery).
2. **Monthly Sales Trends**: Analyzing sales trends over time to see how demand changes by month.
3. **Sales by Time of Day**: Exploring sales distribution by different time periods (morning, afternoon, evening, night).
4. **Product Revenue Contribution**: Analyzing the revenue contributions of the top three product categories vs. other products.

## Insights
From the analysis, we derived the following key insights:
1. **Coffee** is the most popular product, followed by **tea** and **bakery** items, indicating a strong preference for beverages.
2. Sales are steadily increasing month by month, suggesting a growing customer base or successful marketing efforts.
3. The highest sales volume occurs in the **morning**, followed by **afternoon** and **evening**, with lower sales in the **night**.
4. The top three product categories (coffee, tea, bakery) contribute significantly to total revenue, indicating that these categories are central to the coffee shop's offerings.

## Business Strategies
Based on these insights, we suggest the following business strategies:
1. **Morning Promotions**: Introduce breakfast bundles or discounts to capitalize on the high sales volume in the morning.
2. **Happy Hour in Afternoon and Evening**: Offer discounts or bundled products to boost sales during non-peak hours.
3. **Evening Events**: Organize special events like live music or trivia nights to attract more customers in the evening.
4. **Product Expansion**: Consider expanding product offerings in non-beverage categories to appeal to a broader customer base.
5. **Loyalty Programs**: Implement a rewards program to encourage repeat visits, especially in the high-sales morning period.

## Requirements
To run the analysis, you need the following Python packages:
- `pandas`
- `matplotlib`
- `seaborn`

You can install them using:
```bash
pip install pandas matplotlib seaborn
```

## Usage
1. Download the dataset from Kaggle and place it in the project directory.
2. Run the analysis notebook or script to generate visualizations and insights.
3. Review the output for key findings and recommendations.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
