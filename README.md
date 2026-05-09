# SALES-ANALYSIS-PERFORMANCE

# PROJECT OVERVIEW 
This project focuses on cleaning, transforming, and analyzing a dirty retail sales dataset using Python.
The project demonstrates a complete data analytics workflow from raw data preprocessing to business insight generation.

# Objectives
•	Clean and preprocess dirty sales data
•	Handle missing values
•	Correct inconsistent data types
•	Detect and handle outliers
•	Analyze sales performance
•	Identify revenue drivers
•	Visualize business insights

#  Dataset Features
The dataset contains:
•	Customer ID
•	Gender
•	Age
•	Product Category
•	Quantity
•	Price per Unit
•	Sales
•	Date

# Data Cleaning Steps
Missing Value Handling
•	Filled categorical missing values using ‘unknown’
•	Filled numeric missing values using median
Data Type Conversion
•	Converted numeric columns using pd.to_numeric()
•	Converted Date column using pd.to_datetime()
Inconsistency Fixes
•	Replaced invalid entries such as ‘one hundred’
Outlier Detection
•	Used IQR and box plots to identify outlier

# Key Insightss
•	Electronics generated the highest revenue
•	Price per unit has a stronger influence on sales than quantity
•	Month 5 produced the highest sales revenue
•	Clothing has strong transaction volume potential

# Visualizations
The project includes:
•	Bar charts
•	Pie charts
•	Box plots
•	Scatter plots
•	Interactive Plotly charts

# Sample Business Questions Answered
1.	Which product category generates the most revenue?
2.	Who are the most valuable customers?
3.	What drives sales: quantity or price?
4.	Which month generates the highest sales?
5.	Where should the company focus to improve revenue?

   # Recommendations
1. Focus on Electronics
The company should:
•	Promote premium electronics
•	Increase advertising for high-margin products
•	Introduce product bundles
•	Upsell complementary products
2. Grow Clothing Revenue
Because Clothing already has high customer demand, the company should:
•	Run seasonal campaigns
•	Increase average order value
•	Cross-sell products
•	Improve product recommendations
3. Replicate Month 5 Strategies
The company should investigate:
•	Promotions
•	Marketing campaigns
•	Product launches
•	Seasonal trends
that contributed to Month 5 success and apply them to weaker months.
4. Improve Low-Performing Months
Month 9 showed weak performance.
The company should introduce:
•	Discounts
•	Holiday campaigns
•	Flash sales
•	Email marketing promotions
5. Improve Data Quality
The company should:
•	Standardize data entry
•	Validate product categories
•	Automate missing value detection
•	Monitor outliers regularly

# Conclusion
This project demonstrates how proper data cleaning and exploratory analysis can uncover valuable business insights.
The analysis revealed that:
•	Electronics drives the most revenue
•	Revenue is influenced more by price than quantity
•	Certain months significantly outperform others
•	Data quality improvements are necessary for reliable reporting
By implementing the recommendations provided, the company can improve revenue generation, customer retention, and business decision-making.



