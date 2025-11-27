# 📊 Ecommerce Analysis in Power BI

## A complete end-to-end data analytics case study

### 📌 Overview

This project is an end-to-end Power BI Ecommerce Analysis Case Study based on the DataCamp project Whiskique – Online Pet Supply Store.
The goal of this analysis is to help the business:

- Increase sales and customer reach

- Understand customer behavior

- Optimize shipping & reduce operational costs

- Identify profitable products and growth opportunities

### The project includes data cleaning, modeling, DAX calculations, dashboard design, insights, and recommendations.

### 📂 Dataset

The dataset consists of several CSV files representing different parts of the business:

- Sales / Transactions

- Products

- Customers

- Shipping & State Information

- Total Records: 24,000+ rows across all tables.

These files include information about product orders, customer details, product categories, pricing, shipping costs, and geographical mapping.

![Dataset](images/dataset.JPG)

### 🛠️ Process Workflow

**1️⃣ Data Cleaning (Power Query)**

- Corrected data types

- Removed duplicates

- Handled missing values

- Normalized product names and IDs

- Extracted time-based fields (Year, Month, etc.)

![DataCleaning](images/power-query.JPG)

**2️⃣ Data Modeling**

A Star Schema was created:

- Fact Table: Sales

- Dimensions: Products, Customers, States, Invoices

![DataModeling](images/data_modeling.JPG)

**3️⃣ DAX Measures**
Key measures created:

![Measures](images/Measures.JPG)

![DAXExample](images/shipping_baseline_dax.JPG)

**4️⃣ Dashboard Design**

The dashboard includes:
![Dashboard_Overview](images/project-1.JPG)
![Dashboard_Market_Basket_Analysis](images/project-2.JPG)
![Dashboard_Shipping_Metrics](images/project-3.JPG)


### 📈 Key Insights


- Several product pairs have strong frequency scores → excellent cross-sell opportunities

- Certain products have high sales volume but low profitability due to shipping cost

- Shipping items in larger quantities reduces cost per unit

- Underperforming states represent potential markets for targeted marketing

### 💡 Recommendations


**🛒 Cross-Selling Strategy**

- Promote recommended items directly on product pages

- Bundle frequently purchased items

- Create discount offers to encourage cross-sell items

**🚚 Reduce Operating Costs**

- Consolidate shipments for popular combinations

- Improve inventory allocation in high-performing states

**📦 Customer Reach**

Develop campaigns for top customer segments

Improve performance in underdeveloped regions

Encourage repeat purchases through personalized offers


### 🧰 Skills Demonstrated

- Power Query (Data Cleaning)

- Power BI Data Modeling

- DAX Measure Writing

- Market Basket Analysis

- Dashboard Design

- Business Insights & Recommendations
