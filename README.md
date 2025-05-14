# Mobile_Data_Analysis
Data analysis of mobile brands using Python. Includes EDA, visualizations (Seaborn, Matplotlib), and business insights to determine market trends, brand performance, and customer satisfaction based on features like battery, storage, display, and ratings.
Mobile Data Analysis Project

Overview
This project analyzes a sample dataset of mobile brands to evaluate their market performance based on key features, sales data, and customer ratings. The goal is to determine which mobile brand offers the best value by combining technical specifications with customer satisfaction.

Technologies Used
Python
Pandas: Data manipulation
NumPy: Numerical operations
Matplotlib & Seaborn: Data visualization

Analysis Performed

Data Preparation
Filtered and cleaned the dataset.
Selected key features such as Battery Capacity, Processor, RAM, ROM, and Display Size.

Feature Compatibility
Used Pairplot and Heatmap to understand feature correlations.
Pairplot: Shows detailed relationships with count and density.
Heatmap: Provides a quick overview of feature compatibility.

Battery vs Feature Trade-offs
Visualized how battery capacity interacts with key mobile features using violin and line plots.
Key Insight: Samsung leads in offering high battery capacity alongside other strong features. Poco and Realme follow, while Apple offers the least variation in battery-feature combinations.

Sales & Market Share
Analyzed total units sold and revenue generated per brand using GroupBy aggregation, pie chart, and box plot.
Findings:
1) Realme leads in unit sales.
2) Xiaomi leads in revenue due to optimal pricing and features.
3) Samsung sold more but earned less.
4) Apple sold fewer units but at higher prices.

Customer Rating Analysis
Used Violin Plot to analyze the distribution and volume of customer ratings per brand.
Findings:
1) Xiaomi received the most ratings (broad user base).
2) Apple had the highest average ratings (~4.6) despite fewer sales.
3) Samsung showed the most variability in ratings.
4) Poco and Realme maintained moderate and consistent ratings.

Key Takeaways
1) Xiaomi (and its sub-brand Poco) dominates with approximately 45% of the market share.
2) Apple phones are highly rated but sold in fewer quantities.
3) Samsung shows the most variability in performance and customer satisfaction.
4) Realme excels in quantity but not in revenue.
Violin plots proved more informative than box plots for visualizing rating distributions.

Note: 
This analysis was performed on a sample dataset for educational and demonstration purposes.
