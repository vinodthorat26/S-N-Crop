
# S N Crop

A brief description of what this project does and who it's for


# S N Crop-Dashboard

### Dashboard Link : https://github.com/user-attachments/files/19719247/SN.Crop.Dashboard.2.pdf

## Problem Statement

S N Corp is currently leveraging a Power BI dashboard to visualize and track key sales metrics, including Sales, Cost, Profit, and Order data across multiple dimensions such as Customer, Sub-Category, Region, and Time (Year/Quarter). While the dashboard provides rich visual insights, there is a need to enhance the accuracy, usability, and decision-making value of the dashboard for various business stakeholders.

The primary challenge is to streamline the analysis of product performance, customer profitability, and regional trends to better inform strategic planning. Additionally, inconsistencies in data formatting (e.g., customer names) and limited interactivity with dynamic filters reduce the efficiency of business users trying to extract actionable insights.


### Steps followed 


-step 1 : Data Collection 
* Imported the sales dataset containing details such as Order   Date, Sales, Cost, Profit, Customer Name, Product Sub-Category, Region, and Ship Mode.
*Ensured the data covered the period from 2017 to 2020.


-step 2 : Data Cleaning and Transformation
*Removed duplicates and null values from key columns. *Standardized formats (e.g., date fields and customer names).
*Calculated new measures such as:  Sum of Profit = Sales – Cost,
 Year and Quarter extracted from the Order Date.
*Resolved inconsistencies like partial or incorrect customer names.

-step 3 : Data Modeling
*Built relationships between tables (e.g., Orders, Customers, Products).
*Created calculated columns and DAX measures to support dynamic reporting.

-step 4 : Visual Design and Layout
*Used Power BI Desktop to design an interactive and user-friendly dashboard.
*Created the following visuals:

1.KPI Cards for Sum of Sales, Sum of Cost, and Sum of Profit.
2.Table listing customers along with their sales, cost, and profit.
3.Bar Charts for sales and profit by product sub-category.
4.Stacked Column Chart showing count of orders by year and quarter.
5.Map Visual for Sales by Country.
6.Donut Chart or Bar Chart for Quantity by Region.
7.Date Range and Ship Mode Filters for interactivity.

-step 5 : Interactivity and Filtering
*Added slicers for Ship Mode and Order Date to allow users to filter the dashboard.
*Enabled drill-through and tooltip features for more detailed views.

-step 6: Testing and Validation
*Cross-verified totals with raw data to ensure accuracy.
*Tested filters and interactions to ensure they worked as expected.

-step 7: Final Touches
*Applied consistent themes and formatting.
*Added proper labels, legends, and tooltips for clarity.
*Published the dashboard to Power BI Service (if needed) for sharing and collaboration.





