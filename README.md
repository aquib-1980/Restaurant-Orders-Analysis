# Restaurant-Orders-Analysis

Project Overview
This project analyzes a quarter’s worth of order data from a fictitious restaurant serving international cuisine. The analysis is performed using SQL to explore menu composition, pricing, order volume, item popularity, and customer spending behavior.
The project demonstrates practical SQL skills such as joins, aggregations, subqueries, filtering, and analytical reasoning using relational datasets.

Dataset Description
The dataset consists of two tables:

menu_items
Contains details about each dish offered by the restaurant.

Column Name	Description

menu_item_id	Unique identifier for each menu item
item_name	Name of the dish
category	Cuisine category (e.g., Italian, Asian)
price	Price of the dish

order_details
Contains transaction-level order information.

Column Name	Description

order_details_id	Unique identifier for each order record
order_id	Order number
order_date	Date the order was placed
order_time	Time the order was placed
item_id	Menu item ordered (foreign key)

Tools Used

SQL (joins, aggregations, subqueries)
Relational database querying
Data exploration and analysis

Analysis Performed

Menu Analysis

Counted the total number of items on the menu
Identified the least and most expensive menu items
Analyzed Italian cuisine:
Number of Italian dishes
Least and most expensive Italian items

Category Analysis

Counted the number of dishes in each category
Calculated the average price per category

Order Analysis

Determined the date range of the dataset
Calculated:
Total number of orders
Total number of items ordered
Identified orders with the highest number of items
Found orders containing more than 12 items

Order & Menu Integration

Joined menu and order tables for item-level analysis
Identified:
Least ordered items
Most ordered items
Categories of popular and unpopular items

Revenue Analysis

Calculated total spend per order
Identified the top 5 highest-spending orders
Analyzed item-level details for:
The highest-spending order
The top 5 highest-spending orders

Key Insights

Menu pricing varies significantly across categories
Italian dishes represent a major portion of the menu
A small number of orders account for a large share of total revenue
High order value is driven more by item price than item quantity
Popular items tend to cluster within specific categories
