# Blinkit Stock and Logistics Analysis

## Project Description
This project focuses on analyzing the stock and logistics management of Blinkit using Python in Google Colab. The primary goal is to explore inventory trends, product availability, and logistics efficiency using a dataset sourced from Kaggle.

## Business Problem
Effective stock and logistics management are critical for e-commerce platforms like Blinkit. The objective is to identify patterns in stock levels, optimize order fulfillment, and detect inefficiencies that could impact customer satisfaction and business operations.

## Data Sources
The dataset includes multiple tables related to orders, products, users, and inventory:
- `orders` – Information about placed orders
- `order_items` – Details of items within each order
- `users` – Customer demographics and data
- `products` – Product-related information
- `inventory_items` – Stock availability and levels

Dataset available on Kaggle: [Blinkit Sales Dataset](https://www.kaggle.com/datasets/akxiit/blinkit-sales-dataset/data)

## Data Processing & Methodology
1. **Data Cleaning**
   - Removed duplicates and handled missing values
   - Standardized column names and formats
2. **Data Merging**
   - Combined `orders`, `order_items`, and `users` for order insights
   - Merged `products` with `inventory_items` for stock analysis
   - Integrated both datasets to connect stock levels with order fulfillment trends
3. **Exploratory Data Analysis (EDA)**
   - Assessed stock trends and product availability
   - Identified frequent stock shortages and high-demand products
4. **Logistics Performance Evaluation**
   - Analyzed order processing and delivery times
   - Detected delays and inefficiencies in fulfillment operations
5. **Data Visualization & Insights**
   - Developed dashboards in Power BI for real-time tracking of key metrics
   - Highlighted bottlenecks and improvement areas in stock and logistics

## Key Findings
- Some products frequently run out of stock, suggesting forecasting issues.
- Order fulfillment speed varies significantly based on stock availability.
- Improvement opportunities include better demand prediction, streamlined stock replenishment, and logistics optimization.

## Future Enhancements
- Implement machine learning models for demand forecasting
- Develop an automated inventory monitoring system
- Optimize delivery routes and logistics operations

## Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Google Colab** (for data analysis)
- **Power BI** (for visualization and dashboard creation)

## Contact
For any inquiries or collaboration, feel free to reach out!

