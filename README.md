# 📊 eSuperMart Sales Analysis Dashboard (Power BI)

This Power BI project presents a detailed analysis of eSuperMart’s sales performance, segmented by **month**, **product category**, and **region**. The dashboard translates raw data into actionable business insights, empowering stakeholders to make informed decisions on marketing, inventory, and regional strategy.

---
## 🛠️ Tools Used
- **Power BI Desktop** – for building interactive dashboards  
- **Power Query** – initial data cleaning and transformation  
- **DAX** – calculated columns and measures for KPIs
- **Data Modelling** - Relationships established among tables to enable cross-filtering and aggregation.

---
## About Business
It is retail super store dealing in electronics, furniture and office supplies items.
It classifies its customer base into three categories: Normal Consumer which buys for personal use, corporates which buys for office uses and Home Office which are small businesses or working professionals from home who buys for both personal and business uses.

--- 
## 🎯 Project Objective
- It wants to Empower stakeholders with clear insights into monthly sales performance
- product-level contributions to optimize inventory management
- enhance customer targeting
- improve overall revenue
- regional trends—supported by a robust ETL pipeline to ensure data accuracy and freshness.

---
## Data and ETL Pipeline Summary:
- Extracted Sales, Product and Transaction Date Data from internal systems
- Transformed Data into a clean, usable format
- Loaded the Data in PowerBi for analysis and reporting

---
## 🖼️ Dashboard Preview

### Monthly Sales and Profit % Dashboard

![Month-wise Sales](https://github.com/Deepanshu985/ESupermart_Sales_Analysis_Dashboard/blob/64f34c17a14110b34b0e938835b53954d6dba07c/output/visuals/Analysis%20month%20%26%20yearly%20%20wise.png)

1. Kpi cards shows the total sales revenue,Number of orders, profit amount and %
2. Bar chart shows the amount of revenue generated each month for the selected year.
3. Line chart shows the profit% for each month and overall trend during the year

### 🧠 Key Insights

1. During last Year, Initial months showed a consistent dip which suggests promotional campaigns to boost engagement during this period.
2. although sales was more in the second half of the year but the profit % declined rapidly during this period which shows profit was minimised during this period to boost sales. Promotional Offers and Discounts have to be checked during this period to normalize profit
3. Consumers and Home Office customers bought more in the year as compared to corporate which suggests promotional offers to be given to corporates to boost sales.

--
### Product Hierarchy Dashboard

![Product-wise Sales](https://github.com/Deepanshu985/ESupermart_Sales_Analysis_Dashboard/blob/64f34c17a14110b34b0e938835b53954d6dba07c/output/visuals/Analysis%20Product%20wise.png)

1. Decomposition Tree shows the Sales by Category, sub-category and Product
2. Bar chart for least performing products by sales
3. Kpi cards to show important KPIs for the selected segment and region.

### 🧠 Key Insights

1. Phones under Technology Category performed well under all regions and segments 
2. Furniture items underperform across all segments-requires pricing or marketing review.
3. Some products under Binders sub-category have not performed well and generated least amount of revenue- requires attention and understand if the issue is marketing or product is outdated.

--
### Regional Sales Overview Dashboard

![Region-wise Sales](https://github.com/Deepanshu985/ESupermart_Sales_Analysis_Dashboard/blob/64f34c17a14110b34b0e938835b53954d6dba07c/output/visuals/Analysis%20Region%20wise.png)

1. Bar chart shows The Top Performing cities and underperforming cities
2. Pie chart shows the contribution of each Region in the total revenue
3. Cards shows KPIs for the selected cities from the Map showing our presence across the country

### 🧠 Key Insights

1. North Performed the best during the year but Faridabad City in North was the least underperforming city-requires targeting this city by understanding customer behaviour and giving promotional offers accordingly.

2. Prayagraj and Kolkata were the top performing cities bringing maximum revenue.

3. Central and East lag behind- opportunity for regional campaigns and marketing.

--
## Recommendations

1. Launch category-wise bundle offers during low-demand period
2. Run targeted campaigns in underperforming regions via digital channels
3. pricing and product outdatedness of underperforming product categories have to be checked.
4. Discounts should be given in Underperforming regions and cities to create presence and gain new customers.
5. Offers should be given to customers to attract them and convert them into loyal and repeating customers to maintain and grow existing revenue.



