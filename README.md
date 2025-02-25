# AmazonSalesAnalysis

## Project Description

Amazon is an American Tech Multi-National Company whose business interests include E-commerce, 
where they buy and store the inventory, and take care of everything from shipping and pricing to customer 
service and returns. 

This project explores Amazon product sales data to uncover key insights into pricing, discounts, ratings, and category performance. 

Using Power BI, I analyzed the relationship between product prices and customer ratings, evaluated discount patterns across categories, and identified trends in sales performance. Interactive dashboards provide a clear visualization of these insights, helping businesses understand consumer behavior and optimize pricing strategies.

## Dataset Breakdown

This dataset contains over 1,000 1K+ Amazon Product's Ratings and Reviews as per their details listed on the official website of Amazon.

![image]()
![Amazon dashboard](Dataset features.png)



## Approach
1. **Extract, Transform, and Load (ETL) Process**
   
*Extract*: The dataset was in a CSV file format.

*Transform*:
> * Imported the data into Power Query for cleaning and preparation.
> * Changed data types where necessary.
> * Split a column (specific column name if necessary).
> * Removed unnecessary columns.
> * Filtered out null values to ensure data integrity.
> * Added a conditional column to categorize products by category.

*Load*: After transformation, the cleaned dataset was loaded into Power BI for further analysis and visualization.

2. **DAX Measures for Analysis**
To enhance the analysis, the following DAX (Data Analysis Expressions) measures were created:

> * Total Sales = SUM of product prices after discounts.
> * Average Discount Percentage = (Discount Amount / Actual Price) * 100.
> * Average Rating per Category = AVERAGE of ratings grouped by product category.
> * Total Products Sold per Category = COUNT of products within each category.

*A complete list of the DAX measures can be found here*: 

3. **Interactive Features**
   To enhance user experience, I implemented interactive tooltips using the QUESTION Mark and RESET icons to provide contextual insights without overcrowding the dashboard.

4. **Conclusion**
## Business Questions Addressed
This analysis aimed to answer key business questions, including:

1. Does a higher product price correlate with better customer ratings?
2. Which product categories receive the highest and lowest customer ratings?
3. How do discounts vary across different product categories?
4. Do high-priced products receive higher discount percentages?
5. Which product category generates the highest revenue?




