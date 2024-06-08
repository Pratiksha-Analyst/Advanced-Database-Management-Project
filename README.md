# Advanced-Database-Management-Project
Advanced Database Management Project: Insights with Tableau
Project Overview
The "Orion's Sword" project was undertaken in collaboration with Orion Star: Sports & Outdoors, a global retail giant. The primary goal was to enhance Orion Star's data warehousing capabilities by developing a Sales Data Mart. This Sales Data Mart was designed to analyze sales data of Orion Star Club members from 1998 to early 2003, providing valuable business insights to improve strategic decision-making.

Problem Statement
Orion Star faced challenges in utilizing their extensive sales data effectively. The primary issues included:

Inconsistent and erroneous data across multiple sources.
Difficulty in integrating and analyzing sales data from different regions and product categories.
Lack of actionable insights for strategic decision-making.
Development Process
Data Cleansing: Errors and inconsistencies in the data were identified and rectified to ensure a solid foundation for analysis.
Data Integration: Using R Studio and Hive, the data was transformed from a relational normalized model into a dynamic sales data mart.
ETL Process:
Extract: Data was extracted from various text files.
Transform: Data cleansing and transformation were performed using R Studio.
Load: Cleaned data was loaded into Hive using ODBC for efficient storage and management.
Data Visualization: Tableau was used to create interactive visualizations that provide actionable insights into the sales data.
Key Business Questions and Insights
Top Ten Customers by Sales Value:

Question: Who were the last month's top ten customers by sales value?
Insight: Identified top customers, allowing for targeted engagement and personalized marketing strategies.
Metrics: Sum of total retail price.
Dimensions: Customer, Time Date.
Most Profitable Product of 2002:

Question: What was the most profitable product of 2002?
Insight: Helped in inventory management, production planning, and marketing focus by identifying the top-performing product.
Metrics: Unit sales price, unit cost price, quantity, discount.
Dimensions: Product, Price, Discount, Time Date.
Total Number of Products Purchased in 2002 by Customer Type:

Question: What was the total number of products purchased in 2002 by customer type?
Insight: Provided a nuanced understanding of consumer behavior, guiding inventory selection and marketing campaigns.
Metrics: Count of Product ID.
Dimensions: Customer Type, Product, Time Date.
Least Profitable Customer Type in 2002:

Question: Which customer type generated the least amount of income in 2002?
Insight: Assisted in resource optimization by identifying less profitable customer types.
Metrics: Unit cost price, unit sales price, quantity, discount.
Dimensions: Customer Type, Product, Price, Discount, Time Date.
Total Sales Over Time by Country and Product Group:

Question: What were the total sales over time by country and product group?
Insight: Analyzed sales trends and market dynamics, aiding in strategic decisions like market expansion and product diversification.
Metrics: Total sales.
Dimensions: Country, Product Group.
Visualization and Interpretation
Using Tableau, various dashboards were created to visualize the insights derived from the data. These visualizations provided a clear and interactive way to interpret the sales data, highlighting key trends and patterns.

Impact and Recommendations
The project significantly improved Orion Star's data utilization, leading to better strategic decision-making. Key recommendations included:

Focusing on retaining top customers through personalized marketing.
Expanding marketing efforts for the most profitable products.
Tailoring marketing strategies for different customer segments.
Reevaluating marketing strategies for less profitable customer types.
Considering market expansion and addressing challenges in specific regions based on sales trends.
By leveraging data warehousing and visualization tools effectively, the project empowered Orion Star with the insights needed to drive their business forward.
