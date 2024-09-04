# Sales-Analysis-Project

Project Overview:

This project aims to analyze sales data from multiple CSV files to uncover trends and insights. By aggregating data from various months, we can identify patterns in sales, understand customer behavior, and provide actionable recommendations to improve business performance.

Data Collection:

The sales data is stored in multiple CSV files, each representing sales for a different month. These files were combined into a single DataFrame for comprehensive analysis.

- Data Source: Sales data collected from Sales_Data directory.
- Files: Multiple CSV files corresponding to different months.
- Data Format: Each file contains columns such as Order ID, Product, Quantity Ordered, Price Each, Order Date, Purchase Address, etc.

Data Cleaning:

To prepare the data for analysis, several preprocessing steps were performed:

- Removing NaN Values: Rows with missing values were dropped.
- Correcting Data Types: Ensured that columns such as Order Date were in the correct format.
- Handling Duplicates: Duplicated rows were identified and removed.
- Extracting Additional Features: Columns like Month, City, and Sales (calculated by multiplying Quantity Ordered by Price Each) were created to facilitate the analysis.

Analysis:
The analysis focused on answering several key questions:

- What was the best month for sales?
By aggregating the sales data by month, we identified the month with the highest revenue.

- Which city had the highest number of sales?
By extracting the city from the Purchase Address, we determined which city contributed the most to overall sales.

- What time should advertisements be displayed to maximize likelihood of purchases?
By analyzing the order times, we provided insights into the best time for marketing efforts.

- What products are most often sold together?
By examining orders with multiple products, we identified commonly purchased product combinations.

- Which product sold the most and why?
Analyzing the quantity sold and comparing it with the price revealed insights into product popularity.
