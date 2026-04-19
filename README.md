# **Olist-E-Commerce-Analytics-Project-Microsoft-Fabric**

📌 **Project Overview**

This project presents an end-to-end data analytics solution built on the Olist e-commerce dataset using Microsoft Fabric.
It covers the complete workflow from data ingestion and transformation to modeling and dashboard visualization, enabling business insights into revenue, customers, products, and payments.

## 🎯 Objectives

- Analyze overall business performance  
- Identify top-performing states and product categories  
- Understand customer purchasing behavior  
- Evaluate payment preferences  
- Provide actionable business recommendations  

## 🏗️ Data Engineering Workflow

### 🔹 Lakehouse
- Created a Lakehouse to store and manage structured data  
- Organized datasets for analysis  

### 🔹 Data Pipeline
- Built pipelines to ingest and process data  
- Managed data flow within Microsoft Fabric  

### 🔹 SQL Transformations
- Cleaned and prepared data using SQL  
- Extracted date components and handled formatting  
- Addressed Fabric limitations (unsupported functions, column restrictions)  

---

## 🧹 Data Preparation

- Handled missing values and inconsistencies  
- Removed duplicates where necessary  
- Standardized categorical fields (e.g., order status)  

---

## 🧠 Data Modeling

- Designed a **star-schema-like model**

```
Customers → Orders → Order Items → Products
                        ↓
                     Payments
```

- Configured relationships for proper filter propagation  
- Applied bidirectional filtering where required  

---

## 📊 Dashboard Features

### 🔹 KPIs
- Total Revenue  
- Total Orders  
- Total Customers  
- Average Order Value (AOV)  

### 🔹 Visualizations
- 📈 Revenue Trend Over Time  
- 🌍 Top States by Revenue  
- 🛍️ Top Product Categories by Order Volume  
- 💳 Payment Method Distribution  

### 🔹 Slicers (Filters)
- Order Status  
- Customer State  
- Payment Method  
- Order Date  

---

## ⚙️ Tools & Technologies

- Microsoft Fabric (Lakehouse, Pipeline, Power BI)  
- SQL (Data Transformation)  
- DAX (Measures)  
- Data Modeling  
- Data Visualization  

---

## 🧠 Key Insights

- Revenue is concentrated in a few states (São Paulo dominates)  
- Certain product categories contribute most of the sales  
- Credit card is the most used payment method (~78%)  
- Customer retention is low (near one order per customer)  
- Revenue shows fluctuations over time  

---

## 🚀 Business Recommendations

- Improve customer retention with loyalty programs and remarketing  
- Expand operations in underperforming regions  
- Focus on high-demand product categories  
- Promote alternative payment methods  
- Optimize marketing strategies based on sales trends  

---

## ⚠️ Challenges & Solutions

- Faced limitations in Microsoft Fabric (no calculated columns in some modes)  
- Resolved SQL compatibility issues (e.g., FORMAT function limitations)  
- Fixed data model relationships to ensure accurate filtering  
- Handled timestamp limitations for time-based analysis

##  Dashboard Preview
    https://github.com/ashish141008-tech/Olist-E-Commerce-Analytics-Project-Microsoft-Fabric-/blob/main/Olist_dashboard.png

