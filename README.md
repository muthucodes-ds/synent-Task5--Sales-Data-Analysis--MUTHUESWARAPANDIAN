
🌐 GLOBAL SUPERSTORE SALES PERFORMANCE ANALYSIS:

Synent Technologies — Data Analytics Internship

Task 5: Sales Data Analysis

📌 PROJECT OVERVIEW:

This project focuses on analyzing the Global Superstore Sales Dataset to evaluate overall business performance and generate meaningful, data-driven business insights.
The analysis was performed using Python in Google Colab. The project covers data cleaning, feature engineering, sales trend analysis, product performance, profitability analysis, regional analysis, customer segment analysis, and visualization.
The final output includes a Business Insights Report supported by analytical charts and a Global Superstore Sales Performance Dashboard.

🎯 PROBLEM STATEMENT:

Businesses generate large volumes of sales data, but raw transactional data does not directly provide actionable information for decision-making.
The objective of this project is to analyze the Superstore Sales Dataset to:
Identify monthly sales/revenue trends.
Identify the top-selling products.
Analyze overall and category-level profitability.
Compare sales performance across regions and customer segments.
Examine the relationship between discount and profit.
Identify loss-making products.
Generate actionable business insights for better decision-making.

📂 DATASET DETAILS:

Dataset Information
Attribute
Details
Dataset
Global Superstore Sales Dataset
Original File
SuperStoreOrders.csv
Cleaned File
Superstore_Cleaned.csv
Records
51,290
Features
24
Environment
Google Colab
Important Columns
Column
Description
order_id
Unique order identifier
order_date
Date on which the order was placed
ship_date
Date on which the order was shipped
segment
Customer segment
region
Sales region
category
Product category
sub_category
Product sub-category
product_name
Product name
sales
Revenue generated from sales
quantity
Number of units ordered
discount
Discount provided
profit
Profit generated
shipping_cost
Shipping cost
order_priority
Priority of the order

🛠️ APPROACH:

1️⃣ DATA LOADING
Imported the required Python libraries.
Uploaded and loaded the Superstore dataset using Pandas.
Converted order and shipping date columns into datetime format.

2️⃣ DATA INSPECTION
The dataset was examined for:
Dataset dimensions
Column names
Data types
Missing values
Duplicate records
Basic statistical information

3️⃣ DATA CLEANING
The following preprocessing operations were performed:
Removed duplicate records.
Handled missing values in categorical columns using Unknown.
Handled missing values in numerical columns using 0.
Converted Sales, Quantity, Discount, Profit, and Shipping Cost into numeric data types.
Standardized column names using lowercase and underscores.

4️⃣ FEATURE ENGINEERING
New analytical features were created:
year
month
month_name
profit_margin_pct
Profit Margin Formula
Profit Margin (%) = (Profit / Sales) × 100
These features were created to support time-based sales analysis and profitability analysis.

5️⃣ SALES ANALYSIS
The following sales analyses were performed:
Monthly sales trend
Category-wise sales
Sub-category sales
Top 10 products by sales
Bottom 10 products by sales
Region-wise sales
State-wise sales
Customer segment-wise sales

6️⃣ PROFIT ANALYSIS
Profitability was analyzed through:
Total profit
Overall profit margin
Category-wise profit
Profit distribution by category
Loss-making products
Discount versus profit analysis
Profit correlation analysis

7️⃣ DATA VISUALIZATION
The project includes visualizations for:
📈 Monthly Sales Trend
📊 Top 10 Products by Sales
📊 Sales by Category
🥧 Sales by Customer Segment
🔥 Correlation Heatmap
📊 Sales Distribution
📦 Profit Distribution by Category
🔵 Discount vs Profit
📈 RESULTS
💰 OVERALL BUSINESS PERFORMANCE
KPI
Value
Total Sales
7,835,128.00
Total Profit
1,469,034.82
Total Orders
25,035
Overall Profit Margin
18.75%

📅 MONTHLY SALES PERFORMANCE:

Highest Sales Month: September 2014
Highest Monthly Sales: 130,067.00
Lowest Sales Month: February 2012
Lowest Monthly Sales: 25,181.00
Monthly sales analysis helps identify seasonal patterns and periods of stronger or weaker business performance.

🏆 CATEGORY & REGION PERFORMANCE
Analysis:

Best Performing
Highest Sales Category
Office Supplies
Highest Profit Category
Technology
Highest Sales Region
Central
Lowest Sales Region
Canada
🥇 TOP-SELLING PRODUCTS:

The analysis identifies the Top 10 products based on total sales by grouping sales at the product level and sorting the results in descending order.
Examples of high-performing products include:
Eldon File Cart, Single Width
Rogers File Cart, Single Width
Tenex File Cart, Single Width

📉 DISCOUNT & PROFIT ANALYSIS:

The relationship between discount and profit was analyzed using correlation analysis and a scatter plot.
The analysis indicates that higher discount levels are generally associated with lower profitability in the dataset.
This suggests that businesses should carefully evaluate discount strategies to maintain a healthy balance between sales growth and profit margins.

💡 BUSINESS INSIGHTS:

Based on the analysis, the following insights were identified:

1. 📈 Sales Performance
Monthly sales trends can help businesses identify high-performing periods and support inventory and sales planning.

2. 🏆 Product Performance
Top-selling products can be prioritized for inventory planning, marketing campaigns, and promotional activities.

3. 💰 Profitability
Technology generated the highest overall profit among the categories, making it an important category for profitability-focused strategies.

4. 🎯 Discount Strategy
Excessive discounting can negatively affect profitability. Discount policies should therefore be monitored carefully.

5. 🌎 Regional Performance
The difference in regional sales performance provides an opportunity to investigate successful sales strategies and improve weaker markets.

6. ⚠️ Loss-Making Products
Products generating negative profit should be reviewed for pricing, discounts, shipping costs, and other operational factors.

📊 DASHBOARD:

The project also includes a Global Superstore Sales Performance Dashboard containing:

Total Sales
Total Profit
Sales Count
Year Filter
Category Filter
Region Filter
Segment Filter
Monthly Sales Trend
Category Sales
State-wise Sales
Segment Sales
Top 10 Products
Discount vs Profit Analysis

🧰 TECHNOLOGIES USED:

Technology
Purpose
Python
Data analysis and programming
Pandas
Data cleaning and analysis
NumPy
Numerical calculations
Matplotlib
Data visualization
Seaborn
Statistical visualization
Google Colab
Development environment
GitHub
Project hosting and documentation

📁 REPOSITORY STRUCTURE:

synent-task5-sales-data-analysis-MUTHUESWARAPANDIAN/
│
├── SuperStoreOrders.csv
├── Superstore_Cleaned.csv
├── task5_sales_data_analysis.ipynb
├── dashboard.png
└── README.md

📌 PROJECT OUTCOME:

This project demonstrates practical knowledge of:
Data Cleaning
Data Preprocessing
Exploratory Data Analysis (EDA)
Sales Analysis
Profitability Analysis
Business Intelligence
Data Visualization
Business Insight Generation
The cleaned dataset and analytical outputs provide a strong foundation for further dashboard development, business reporting, sales forecasting, and predictive analytics.

👨‍💻 AUTHOR:

MUTHUESWARAPANDIAN K
B.Tech — Artificial Intelligence and Data Science
Data Analytics Intern — Synent Technologies

⭐ PROJECT STATUS:

Completed — Task 5: Sales Data Analysis
