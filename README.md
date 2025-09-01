# Power BI Dashboard / Project: Superstore Sales Data Analytics #

![Home Page](/Images/Our%20Superstore.jpg)

## Introduction ##

This dashboard was created for a **sales / Business development manager of a fictional superstore**. It focuses on analyzing sales data from a fictional superstore to **uncover actionable insights about sales performance, product categories, and consumer behavior**. The goal is to demonstrate how raw sales data can be transformed into meaningful information to support data-driven strategic decisions in sales and business development.

By using Power BI, I designed an interactive dashboard that provides:

1. 📈 Sales Insights – overall Sales growth and seasonal patterns
2. 🛍️ Product Insights – best and worst-performing categories , sub-categories, and products
3. 👥 Customer Analysis – consumer segments contributing most to sales
4. 🌍 Regional Performance – sales distribution across different regions or markets


## 🛠️ Skills Demonstrated ##

This project demonstrates the end-to-end Power BI workflow, covering data preparation, modeling, analysis, and dashboarding.

🔄 Data Preparation / ETL Process (Power Query)

- 📥 Extracted raw sales data from the web and created Fact (Sales) and Dimension (Customer, Product) tables.

- 🧹 Cleaned and transformed data: removed unnecessary columns, handled blanks/errors, ensured correct data types.

- 🔑 Removed duplicates from dimension tables to maintain integrity.

🗂️ Data Modeling

- 📅 Built separate Date Tables (Order & Shipping) for accurate time-series analysis (Year-over-Year, Month-over-Month).

- ⭐ Designed a Star Schema with fact (Sales Table) and dimension tables (Customer Table, Product Table, Order Date Table, Shipping Date Table).

- 🔗 Established 1-to-many relationships for consistent insights.

📊 Data Analysis (DAX)

- ➕ Created calculated columns and measures: Total Sales / Revenue, Total sales for a specific year / Region / category, Total Profit, Profit Margin, Total Orders, Distinct Categories.

- 🧮 Applied functions like CALCULATE, SUMX, DIVIDE, DISTINCTCOUNT, COUNTA.

- ⏳ Enabled time intelligence with CALENDAR, YEAR, MONTH, DAY.

📈 Data Visualization

- 📉 Line Charts → To show Sales & Profit trends (Year-over-Year, Month-over-Month, Quater-over-Quater).

- 🗂️ Cards → To demonstrate Key KPIs (Total No. of Orders, Total Sales, Total Profit, and Profit Margin).

- 📊 Bar/Column/Cluster Column/Stacked Bar Charts → To compare Total Sales / Overall Performance by category, Products, consumer segment, and region.

- 🥧 Pie Chart → To exhibit Shipping mode distribution.

🎛️ Interactive Dashboard

- 🎛️ Added slicers, drill-downs, tooltips, and navigation buttons for interactivity.

- 🎨 Delivered a business-friendly, interactive dashboard that supports strategic decision-making.


## Dashboard Overview ##

![Home Page](/Images/Home%20Page.jpg)

This is a Home Page of our dashboard. It contains a project name, project objective with a short project description. It also includes a dashboard page navigator and a help buttion to guide users on how to interact with the dashboard.

![Data Model](/Images/Data%20Model.jpg)

This is the model view of our dashboard. It shows which tables are exist in our data model and how they are relate to each other. This helps any reviewer or third party understand how the data model was designed.

![Overall Sales Insights](/Images/Sales%20Insights_Overall.jpg)

This is the overall sales insights dashboard. It highlights key KPIs like Total orders, Total Sales, Total Profit, and Profit Margin for complete dataset (meaning that it includes all years available in our data from 2014-2017 without applying any filter). This also shows year-over-year Total Sales or Revenue Growth as well as compare year-over-year profit growth. Users can drill down by year or region for more specific insights. 


![Sales Insights Drill-down for a specific year 2017](/Images/Sales%20Insights%20Drill-Down%20for%20a%20specific%20Year%20(2017).jpg)

This is the sales insights drill-down for the year 2017. It shows key KPIs like Total orders, Total Sales, Total Profit, and Profit Margin for the year 2017 (as you can see left top corner, filter has been applied for year slicer). This also shows Month-over-Month Total Sales or Revenue Growth / Decline as well as compare Month-over-Month Profit Growth / Decline for the year 2017.

![Overall Product Insights](/Images/Product%20Insights_Overall.jpg)

This is the overall product insights dashboard. It compares product categories and sub-categories as well as shows best and worst performing products in terms of total sales or revenue for complete data (means without applying any filter). Users can drill down by year or region for more specific insights. For Example, See the next image.

![Product Insights Drill-down for a specific year (2014) & for a specific region (south)](/Images/Product%20Insights%20Drill-Down%20for%20a%20specific%20year%20(2014)%20with%20a%20specific%20Region%20(South).jpg)

This is the product insights drill-down for the year 2014 and for the region south. Best- and worst-performing products differ significantly compared to the overall dataset, highlighting the importance of regional analysis.

![Overall Consumer Insights](/Images/Consumer%20Insights_Overall.jpg)

This is the overall consumer insights dashboard. It demonstrates which consumer segment, region, and states contributing most to our revenue (cover complete data, means without applying any filter). It also reveals product preferences by segment and geography. This page can also be drill-down by a specific year to see year specific details. For instance, see the next image.

![Consumer Insights Drill-down for a specific year 2014](/Images/Consumer%20Insights%20Drill-Down%20for%20a%20specific%20year%20(2014).jpg)

This is the consumer insights drill-down for the year 2014. Results vary significantly compared to the overall dataset, allowing deeper exploration of consumer behavior.

## Conclusion

The Superstore Sales Data Analytics project demonstrates how raw sales data can be transformed into actionable business insights using Power BI. Through structured data preparation, modeling, DAX calculations, and interactive visualization, the dashboard provides a 360° view of sales, products, and consumer behavior.

**Key Insights Delivered:**

- 📈 Identified overall and year-specific sales & profit growth trends.

- 🛍️ Highlighted best- and worst-performing products, product categories, and sub-categories across regions and time-frames.

- 👥 Analyzed customer segments and geographic markets contributing most to revenue.

- 🎛️ Delivered an interactive, user-friendly dashboard that supports data-driven decision-making for business development and sales strategy.

This project reflects my ability to design, build, and deliver BI solutions that not only visualize data but also provide meaningful insights for strategic decision making.

**Key Takeaways from this project**

- I understood the importance of proper data modeling (Star Schema) to ensure accurate and efficient analysis.

- I practiced writing DAX measures for KPIs such as profit margin, sales growth, and customer segmentation, which deepened my understanding of DAX functions.

- I learned how much value interactive features (slicers, drill-downs, tooltips, navigation) bring to a dashboard, making it easier for users to explore insights on their own.

- Most importantly, I realized that data visualization is not just about charts—it’s about telling a story that supports business planning.

Overall, this project improved both my technical Power BI skills and my ability to think from a business perspective. It reflects my ability to design, build, and deliver BI solutions that not only visualize data but also provide meaningful insights for strategic planning.