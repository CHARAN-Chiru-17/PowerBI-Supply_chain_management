# PowerBI-Supply_chain_management

## Project Overview
AtliQ Mart's Supply Chain Analytics project aims to address the service issues related to on-time and in-full deliveries. The goal is to track and improve the on-time delivery percentage (%), in-full delivery percentage (%), and OnTime in Full (OTIF) percentage for customer orders on a daily basis.

##  Data Preparation in Power BI

1.Load your daily delivery data into Power BI.

2.Transform the data as needed using Power Query Editor.

3.Extract the month, week, and day information from the date column.

## Data Sources
  The primary dataset used for this analysis "dim_customers.csv","dim_date.csv", "dim_products.csv","dim_targets_orders" , "fact_order_lines.csv","fact_orders_aggregate.csv".

## Visualization

1.Stacked Bar Chart: Order Quantity by Product Name

Drag and drop a stacked bar chart visual onto the report canvas.
Place "Product Name" on the axis and "Order Quantity" in the Values field.
Customize colors or legends as needed.

2.Stacked Column Chart: Order Quantity by Customer Name

Add a stacked column chart to the report canvas.
Place "Customer Name" on the axis and "Order Quantity" in the Values field.
Customize colors or legends as needed.

3.Line Chart: Order Quantity by Month

Insert a line chart visual.
Place "Month" on the axis and "Order Quantity" in the Values field.
Format the line chart to display months in chronological order.

4.Slicer: Display Cities

Drag and drop a slicer visual onto the canvas.
Connect it to the "City" field in your data.
Use this slicer to filter other visuals based on selected cities.

5.Metrics with Sparkline: VOF%, LOFR%

Add a card visual for VOF% and LOFR%.
Use DAX (Data Analysis Expressions) measures for calculating these percentages.
Add a sparkline in each card to show trends over time.

6.Pie Chart: Not Delivered Orders by Cities

Include a pie chart visual.
Use "City" for the Legend and "Not Delivered Orders" for the Values.
Customize colors and labels as needed.

7.Clustered Chart: Order Quantity vs. Delivered Quantity by Category

Insert a clustered bar chart.
Place "Category" on the axis and add two data series for "Order Quantity" and "Delivered Quantity."
Customize colors and labels as needed.

8.Metrics: Display Split by Customer

Create DAX measures for relevant metrics like on-time percentage, in-full percentage, etc., by customer.
Add cards to display these metrics, and use the slicer to filter by customer.

9.Metric: Display Split by City

Create DAX measures for metrics like order quantity, delivery performance, etc., by city.
Add cards to display these metrics, and use the slicer to filter by city.
