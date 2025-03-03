# Pramila store-Data-Analysis for Sales growth for the year 2022 using Excel.

This project analyzes Pramila Store's 2022 sales data to identify growth patterns and provide insights for future sales strategies. It utilizes data analysis techniques to visualize trends and inform decisions aimed at increasing sales.
## Business Problem Statements
Observations on the following are made:

1.During the first quarter store ended up with good sales

2.Which gender makes more purchases ?

3.What are the top 2 states with more total sales ?

4.Which age group contributed more to the sales ?

5.Which channels contributed the most to sales?


## Dataset

- **Data belongs to Pramila stores:** A leading online retailer in the Andhra Pradesh
- **Time Period :**  January 2022  -  December 2022
- **Total channels:**  07
- **Total Orders :**  8
- **Total Orders :**  31,047

- **KPI’s :** Total Sales.

## Data Analysis Using Excel

### Data Cleaning
1. Apply filters to each column individually to review the data.
2. Check for null values in each column systematically.
3. In the gender column, values were inconsistent (e.g., M, Men, W, Women). I standardized the data by converting all entries to 'M' for men and 'W' for women.
4. cleaned the quantity column by replacing text values like "one" and "two" with their corresponding numeric values, ensuring uniformity in the data.
3. Data handling for null values and junk data.


### Data processing
1. created an age group bucket in Excel using the IF condition to categorize ages, making it easier to segment and analyze the data.
2. Extracted the month from the date column using Excel functions, allowing for better segmentation and enabling more detailed analysis based on monthly trends.
3. Extracted the quarter from the date column using Excel functions, enabling the classification of data into Q1, Q2, Q3, and Q4. This helps in analyzing trends and performance across different quarters.

### Data Analysis

1. Created a pivot bar chart from the sales report to visualize the data effectively. Then, I copied and pasted the chart into a separate Excel worksheet to compile all key insights on a single page for better presentation and analysis.
2. created a pie chart to visualize gender-based shopping classification. Then, I copied and pasted the chart into a separate Excel worksheet to present all key insights on a single page for better clarity and analysis.
3. Created a pie chart to visually represent the distribution of order statuses across all sales transactions. This Pie chart helps in understanding the proportion of different order statuses, such as Delivered, Cancelled, refunded, and returned orders. By analyzing this, we can identify patterns in order fulfillment and potential issues in processing.
4. Created a pivot table to analyze the top 10 states based on total revenue. By sorting the data in descending order, I identified the highest-performing states in terms of sales. This analysis helps in understanding regional sales distribution, identifying key markets, and making data-driven decisions for business growth. The pivot table allows for easy filtering and further breakdowns to explore revenue trends across different time periods or product categories.
5. Designed a bar chart using data that includes age group, gender, and total revenue. This visualization helps in understanding revenue distribution across different demographics, showing which age groups and genders contribute the most to total sales. By comparing these segments, we can identify key customer groups and tailor marketing or sales strategies accordingly. 
6. Designed a pie chart representing different sales channels to understand customer preferences. This visualization helps in identifying which platforms, such as Amazon, Flipkart, or Myntra, contribute the most to total sales. By analyzing the proportion of sales from each channel, we can gain insights into customer buying behavior and optimize marketing strategies accordingly. 
7. Implemented slicers based on month, category, age group, quarter, and sales channel to enhance data filtering during stakeholder meetings. These interactive filters allow for quick and efficient data segmentation, making it easier to analyze trends and key insights dynamically. By using slicers, stakeholders can focus on specific time periods, customer segments, or sales channels, enabling more informed decision-making and a clearer understanding of business performance.


## Conclusion

We need to target women customers of age group (30- 49) years living in Maharashtra, Karnataka by showing ads/offers/coupons available on Amazon, Flipkart and Myntra.




