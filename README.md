CAR SALES DATA ANALYSIS

This project explores a dataset of car sales to uncover trends in sales volume, pricing, and manufacturer performance. Using Python and Exploratory Data Analysis (EDA), the study provides actionable insights to help manufacturers and dealerships improve sales strategies.

OBJECTIVE

1. Analyze sales volumes to identify top-performing manufacturers.  
2. Understand pricing trends and their correlation with attributes like horsepower and fuel efficiency.  
3. Explore relationships between variables such as price, resale value, and engine size.

DATASET

Source: Kaggle Car_sales.csv (157 rows, 16 columns).  
Key Attributes:  
1. Sales Volume (`Sales_in_thousands`)  
2. Price (`Price_in_thousands`)  
3. Horsepower (`Horsepower`)  
4. Fuel Efficiency (`Fuel_efficiency`)  
5. Resale Value (`Year resale value`)


METHODS

Data Preprocessing:  
1. Handled missing values by imputing averages.  
2. Cleaned column names and removed duplicates.

EDA Techniques:  
1. Grouped data by manufacturers to analyze trends.  
2. Created visualizations like bar charts and heatmaps to understand relationships.  
3. Performed descriptive statistics to summarize numerical columns.

KEY INSIGHTS
1. Top Performers: Certain manufacturers dominate sales, while others could improve with better pricing or efficiency strategies.  
2. Price Trends: Strong correlation between price and horsepower; higher-powered cars are generally more expensive.  
3. Fuel Efficiency: Identified the top 3 most fuel-efficient cars with engines above 2.5 liters.  
4. Popular Models: Ford’s F-Series is the most popular based on sales.

RECOMMENDATIONS

1. Manufacturers with low sales should focus on affordability and fuel efficiency.  
2. Marketing efforts should emphasize models balancing price, performance, and efficiency.  
3. Future analyses could incorporate demographic and regional data for deeper insights.

LIMITATIONS

1. Small dataset size; larger datasets would enhance findings.  
2. Lacks geographic and customer demographic data.  
3. No predictive modeling was applied.