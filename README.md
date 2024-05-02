# Supply-Chain-Analytics-SQL-Assingment

## Project Report: SQL Analysis of Supply Chain Dataset

### Golf Products Analysis
**List of Golf Products**

To begin, we aimed to list all products within categories related to golf. This involved identifying categories containing the term "golf" and extracting the Product_ID and Product_Name for each product within these categories. The output was sorted by Product_ID.

**Most Sold Golf Products**

Following the initial analysis, we delved deeper to determine the top 10 most sold products within categories related to golf. Utilizing sales data, we extracted the Product_Name and Sales columns for these products, sorting the output in descending order of sales.

### Customer Segment Analysis
**Segment-wise Orders**

In this segment, our focus shifted to understanding the ordering behavior across different customer segments. We calculated the number of orders for each customer segment and sorted the results from highest to lowest order count.

**Percentage of Order Split**

Furthermore, we examined the percentage of split orders by each customer segment for orders with a shipping duration of six days. This analysis provided insights into how orders were distributed among different customer segments during this specific timeframe.

### Sales and Product Analysis
**Month-wise Nike Sales**

Next, we analyzed sales and quantities sold for Nike products on a month-by-month basis. By aggregating data from orders, ordered_items, and product_info tables, we formatted the output to display sales and quantities sold for each month, sorting the results chronologically.

**Costliest Products**

Additionally, we identified the top five costliest products in the catalogue, providing details such as Product_ID, Product_Name, Category_Name, Department_Name, and Product_Price. The results were sorted based on Product_Price in descending order.

### Order and Customer Insights
**Cash Customers**

Our analysis extended to identifying the top 10 most ordered items based on sales from 'CASH' type orders. We included product name, sales, and distinct order count for these items, sorting the table by order counts and, in cases of ties, by sales.

**Customers from Texas**

Moreover, we obtained details of customer orders from the state of Texas with addresses containing 'Plaza' but not 'Mountain'. The output was sorted by Order_ID.

### Advanced Analysis and Rankings
**Home Office Orders**

We computed the total count of orders for customers belonging to the "Home Office" segment and ordering items from the "Apparel" or "Outdoors" departments.

**Within State Ranking**

For orders from the "Home Office" segment with items from "Apparel" or "Outdoors" departments, we ranked each Order_City within each Order_State based on order count, ensuring alphabetical order in cases of ranking clashes.

**Underestimated Orders**
Finally, we ranked shipping modes for each year based on the number of orders where shipping days were underestimated. The analysis considered only 'COMPLETE' and 'CLOSED' orders from the 'Consumer' segment.

