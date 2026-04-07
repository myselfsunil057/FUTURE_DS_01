# 📚 Sales Performance Dataset Documentation

---

## 🧠 Overview

This dataset represents retail sales transactions used to analyze revenue, profitability, product performance, customer behavior, and regional trends.

It supports business intelligence reporting and enables decision-making across sales, marketing, and operations functions.

---

## 🎯 Purpose

- Measure overall business performance (Revenue, Profit, Margin)  
- Analyze product and category contribution  
- Track customer segmentation behavior  
- Evaluate regional sales distribution  
- Identify time-based trends and growth patterns  

---

## 📊 Key Business Metrics

- **Total Revenue:** $2M  
- **Net Profit:** $286K  
- **Total Orders:** 5009  
- **Profit Margin:** 12.47%  
- **Average Revenue per Order:** ~$399  

---

## 📦 Data Dictionary (Unified)

| Column Name   | Data Type | Description |
|---------------|----------|-------------|
| OrderID | String | Unique identifier for each transaction |
| OrderDate | Date | Date when the order was placed |
| ShipDate | Date | Date when the Order was dispatched |
| ProductID | String | Identifier for purchased product |
| CustomerID | String | Identifier for customer |
| ProductName | String | Name of the product sold |
| Category | String | High-level product grouping |
| SubCategory | String | Detailed product classification |
| CustomerName | String | Name of the customer |
| Segment | String | Customer classification (Consumer, Corporate, Home Office) |
| Region | String | Geographic region of sale |
| Postal Code | Integer | Standardized geographic City identifier |
| State | String | State of transaction |
| City | String | City of transaction |
| Quantity | Integer | Number of units sold |
| SalesAmount | Decimal | Total revenue generated from transaction |
| Discount | Decimal | Discount applied on sale |
| Profit | Decimal | Net profit after costs |
| UnitPrice | Decimal | Price per unit of product |


---

## 🔗 Relationship Logic (Business Perspective)

- Each transaction is linked to a specific product, customer, and region  
- Each order is time-stamped for trend and forecasting analysis  
- Products are grouped into categories and subcategories for performance tracking  
- Customers are segmented for behavioral and sales analysis  
- Geographic hierarchy enables regional performance evaluation  

---

## 📐 Business Rules

- Each record represents a single order line item  
- Revenue is calculated at transaction level after discount application  
- Profit reflects cost-adjusted earnings  
- No duplicate transaction identifiers are allowed  
- Time fields are standardized for analytical consistency  

---

## 📊 Analytical Scope

This dataset enables analysis across:

- Revenue and profitability trends  
- Product-level performance concentration  
- Customer segmentation behavior  
- Regional sales contribution  
- Time-series growth and seasonality patterns  

---

## ⚠️ Data Considerations

- Profitability varies significantly across product categories  
- Revenue concentration exists in a limited set of high-performing products  
- Discount patterns may influence margin efficiency  
- Some product segments show inconsistent performance distribution  

---

## 🚀 Usage Context

This dataset is designed for:

- Power BI dashboards  
- Executive KPI reporting  
- Sales performance analysis  
- Business strategy optimization  
- Product and customer analytics  

---

## 🧠 Closing Insight

This dataset is not just transactional data — it is a decision engine for understanding business performance at scale.
