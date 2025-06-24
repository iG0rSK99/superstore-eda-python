📊 Superstore Sales EDA Project-
This project explores the Superstore sales dataset using Python (Pandas, Matplotlib, Seaborn) to extract key business insights, visualize patterns, and identify opportunities to improve profitability.

PROBLEM STATEMENT

The goal of analyzing the Superstore Sales Dataset is to explore the sales performance, understand customer purchasing behavior and identify factors that drive profitability.

The dataset typically contains information about:
Sales transactions (Order ID, Product, Category)
Customer details (Customer ID, Region, Segment)
Sales performance (Sales, Profit, Quantity, Discount)
Shipping details (Ship Mode, Order Date, Ship Date)

OBJECTIVE-
To generate actionable insights that can help optimize inventory, improve profitability, and enhance customer targeting strategies.

✅ Tools Used

Python (Pandas, Matplotlib, Seaborn)
Jupyter Notebook
Data Cleaning & Visualization
Outlier Detection (IQR)

We’ve explored Superstore sales performance and identified insights that can improve profitability, marketing strategies and inventory management.

Key Insights-

Sales & Profit Distribution:
Both Sales and Profit have extreme outliers, which were detected using the IQR method and boxplots.
The dataset is right-skewed, with a few transactions significantly larger than the rest.

Top-Performing Sub-Categories:
Sub-categories like Chairs and Furnishing are highly profitable.
Sub-categories such as Tables and Bookcases often result in losses, especially with high discounts.

Regional Insights:
The West region shows strong performance in both order volume and profitability.
The South and East regions have lower average profit margins and Central regions are unprofitable.
Top 3 states with contribution in sales and profit are California, New York, and Virginia.

Impact of Discounts:
Higher discounts generally lead to lower profits or losses.
Discounts do not have any significant impact on Sales.

Shipping Trends:
Standard Class is the most frequently used shipping mode across all regions.
Same Day shipping is less common and typically used for smaller, urgent orders.
Shipping mode choice does not directly impact profitability but may affect cost and delivery speed.

Visualization Highlights:
Boxplots were used for distribution analysis.
Bar plots helped compare metrics like Sales, Profit, and Discount across Sub-Categories.
Count plots and catplots provided clear views of Shipping Mode usage by Region.

Outlier Handling:
Outliers in Sales and Profit were identified using the IQR method and visualized using boxplots.

Conclusion:

This EDA provides actionable insights into product performance, discount strategies, and regional sales behavior. 
These findings can be used to:

Optimize pricing and discount strategies
Improve region-specific marketing
Focus on profitable product categories
Monitor and handle high-impact outliers
