# **Olist-E-Commerce-Analytics-Project-Microsoft-Fabric**

📌 **Project Overview**

This project presents an end-to-end data analytics solution built on the Olist e-commerce dataset using Microsoft Fabric.
It covers the complete workflow from data ingestion and transformation to modeling and dashboard visualization, enabling business insights into revenue, customers, products, and payments.

🎯 **Objectives**

1. Analyze overall business performance
2. Identify top-performing states and product categories
3. Understand customer purchasing behavior
4. Evaluate payment preferences
5. Provide actionable business recommendations

🏗️ **Data Engineering Workflow**

🔹 **Lakehouse**
a. Created a Lakehouse to store and manage structured data
b. Organized datasets for analysis
🔹 **Data Pipeline**
a.  Built pipelines to ingest and process data
b.   Managed data flow within Microsoft Fabric
🔹 **SQL Transformations**
a.  Cleaned and prepared data using SQL
b.  Extracted date components and handled formatting
c.  Addressed Fabric limitations (e.g., unsupported functions, column restrictions)

🧹 **Data Preparation**
a. Handled missing values and inconsistencies
b. Removed duplicates where necessary
c. Standardized categorical fields (e.g., order status)

🧠 **Data Modeling**

a. Designed a star-schema-like model

   Customers → Orders → Order Items → Products
   ↓
   Payments

b. Configured relationships for proper filter propagation
c. Applied bidirectional filtering where required

📊 **Dashboard Features**

🔹 **KPIs**
1. Total Revenue
2. Total Orders
3. Total Customers
4. Average Order Value (AOV)

🔹 **Visualizations**

   📈 Revenue Trend Over Time
   🌍 Top States by Revenue
   🛍️ Top Product Categories by Order Volume
   💳 Payment Method Distribution

🔹 **Slicers (Filters)**

1. Order Status
2. Customer State
3. Payment Method
4. Order Date

⚙️ **Tools & Technologies**

a. Microsoft Fabric (Lakehouse, Pipeline, Power BI)
b. SQL (Data Transformation)
c. DAX (Measures)
d. Data Modeling
e. Data Visualization

🧠 **Key Insights**

a. Revenue is concentrated in a few states (São Paulo dominates)
b. Certain product categories contribute most of the sales
c. Credit card is the most used payment method (~78%)
d. Customer retention is low (near one order per customer)
e. Revenue shows fluctuations over time

🚀 **Business Recommendations**

a. Improve customer retention with loyalty programs and remarketing
b. Expand operations in underperforming regions
c. Focus on high-demand product categories
d. Promote alternative payment methods
e. Optimize marketing strategies based on sales trends

⚠️ **Challenges & Solutions**
a. Faced limitations in Microsoft Fabric (no calculated columns in some modes)
b. Resolved SQL compatibility issues (e.g., FORMAT function limitations)
c. Fixed data model relationships to ensure accurate filtering
d. Handled timestamp limitations for time-based analysis

