# Coffee_Sales-Data_analysis
## Objective

The main objective of the dashboard is to offer a user-friendly interface for tracking coffee sales performance over time. By providing key metrics and interactive filters, the dashboard helps users to:

- Visualize the total sales trends over time.
- Compare sales performance across countries (United States, Ireland, and the United Kingdom).
- Identify the top 5 customers by sales volume.
- Filter the data by multiple criteria such as order date, coffee roast type, customer loyalty status, and product weight.

## Data Cleaning and Preparation

To build the dashboard, a thorough data cleaning process was required. The dataset was initially spread across multiple Excel sheets, which needed to be consolidated. Using the XLOOKUP function in Excel, relevant data from different sheets were merged into a single master dataset. This consolidation ensured that all the necessary information, including order details, product attributes, and customer data, was available in one location for further analysis.

The dataset was then cleaned to ensure consistency, eliminate any errors, and handle missing or inconsistent values. After cleaning, the data was structured to support the creation of pivot tables, which formed the foundation of the dashboard’s visualizations.

## Dashboard Components

The Coffee Sales Performance Dashboard consists of several key components:

- Line Chart of Total Sales Over Time: This visualization shows how total coffee sales have fluctuated over a specified period. Users can filter the data by order date, coffee roast type, customer loyalty status, and product weight to drill down into specific trends.

- Bar Chart of Sales by Country: This bar chart focuses on sales performance across three countries: the United States, Ireland, and the United Kingdom. It provides a comparative view of how these regions are performing in terms of sales volume. Similar to the line chart, this visualization is also interactive, allowing users to apply filters for order date, roast type, loyalty card status, and product weight.

- Bar Chart of Top 5 Customers: This chart highlights the top 5 customers by total sales, showing which customers are driving the most revenue. The filters applied to the dashboard (order date, coffee roast type, loyalty card status, and product weight) dynamically adjust the displayed top customers, giving an updated view based on the selected criteria.

## Filters and Interactivity

One of the most powerful aspects of the dashboard is its interactivity, which is driven by the following filters:

- Order Date: Users can select specific date ranges to analyze sales trends over time.
- Coffee Roast Type: The dashboard allows filtering by the roast type of the coffee product—Dark, Light, or Medium roast.
- Loyalty Card Status: Customers can be filtered based on whether they possess a loyalty card, providing insights into the purchasing behavior of loyal versus non-loyal customers.
- Product Weight (kg): This filter enables analysis based on the weight of the coffee products sold, offering insights into product size preferences.

These filters allow users to explore the data from different perspectives and gain a deeper understanding of specific segments of the sales data.

## Pivot Table Creation

The dashboard was built on top of a pivot table, which served as the backbone for the graphs and visualizations. The pivot table enabled the aggregation and summarization of the data by key variables such as order date, roast type, country, customer, and product weight. This allowed for easy generation of the required charts and facilitated quick data analysis.

## Key Insights

The dashboard provides several important insights into coffee sales:

- Total Sales Over Time: The line chart reveals how sales have evolved over the selected time range, allowing businesses to identify growth periods or sales declines.

- Regional Performance: The bar chart comparing sales across the United States, Ireland, and the United Kingdom highlights which regions are leading in terms of sales. This can help businesses prioritize marketing or distribution efforts.

- Top Customers: Identifying the top 5 customers offers valuable insights into which clients are contributing the most to sales, enabling better relationship management and targeted promotions.


- Impact of Filters: By applying filters, users can further refine their analysis to understand how different variables (e.g., roast type, loyalty status) impact sales performance, making it easier to identify actionable trends.

## Conclusion

The Coffee Sales Performance Dashboard provides a comprehensive and interactive view of coffee sales, helping businesses to track performance across time, regions, and customers. By leveraging Excel’s powerful pivot tables, XLOOKUP function, and dynamic filters, the dashboard offers a flexible and insightful tool for analyzing key sales metrics. Whether for tracking total sales, understanding customer preferences, or comparing regional performance, this dashboard delivers valuable insights to support data-driven decision-making.
## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

