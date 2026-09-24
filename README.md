# FreshMart Sales, Profit \& Customer Performance — Power BI Dashboard

An end-to-end **retail sales analytics dashboard** built in Power BI, covering revenue and profitability, product and category performance, customer behaviour, and store and delivery efficiency for FreshMart, an Indian hypermarket chain, across **2023–2025**.

> 📊 Power BI Desktop | 5 report pages | 68,000 orders | 90 stores | 6,000 products | 25 categories

\---

## 📌 Project Overview

Category managers, store heads and leadership need one place to see what sells, what earns, who buys and how well orders are fulfilled, instead of separate reports for each question. This project analyzes FreshMart's transactional sales data and turns it into one connected, navigable Power BI report.

**Objective:** track overall revenue and profitability, understand which categories, brands and stores perform best, study customer buying across age groups, gender and membership tiers, and monitor order fulfilment and delivery efficiency, so that teams can make faster, data-backed decisions on inventory, pricing, marketing and store operations.

Every analytical page (2–5) follows the same design: **3 slicers, 5 KPI cards and 6 charts**, with a shared navigation bar to jump between pages.

\---

## 🖼️ Dashboard Preview

### Introduction

!\[Introduction](screenshots/01\_introduction.png)

### Sales \& Revenue Overview

!\[Sales \& Revenue Overview](screenshots/02\_sales\_revenue.png)

### Product \& Category Performance

!\[Product \& Category Performance](screenshots/03\_product\_category.png)

### Customer Insights

!\[Customer Insights](screenshots/04\_customer\_insights.png)

### Store \& Delivery Performance

!\[Store \& Delivery Performance](screenshots/05\_store\_delivery.png)

\---

## 📑 Report Pages

### 1\. Introduction

Landing page with the project overview, objective, dataset summary and navigation buttons to every other page.

**KPIs:**

* Year-over-Year Sales Growth: **20.57%**
* States Covered: **40**
* Cities Covered: **77**
* Brands: **56**
* Categories: **25**

\---

### 2\. Sales \& Revenue Overview

How much FreshMart sells and earns.

**KPIs:**

* Total Orders: **68K**
* Total Sales: **₹579M**
* Total Profit: **₹69M**
* Profit Margin: **11.86%**
* Loss Rate: **1.60%**

**Charts:** Sales trend over time (by year), Sales by State, Profit by Quarter and Year, Sales by Category, Loss Rate % by Category, Sales and Profit by Month

**Filters:** Year / State / Category

**Insights:** Staples \& Grains is the top category by sales (₹34M); loss rate is highest in Kitchen \& Home categories (2.06%), followed by Frozen (1.92%) and Snacks (1.90%); profit rises steadily through the year in every year, peaking in Q4.

\---

### 3\. Product \& Category Performance

What sells, what earns and what gets discounted.

**KPIs:**

* Total Quantity Sold: **373,417**
* Total Products: **6,000**
* Average Unit Price: **₹1,604**
* Average Discount: **3%**
* Total Cost: **510M**

**Charts:** Sales by Category and SubCategory (treemap), Profit by Brand, Sales by PackSize, Sales by ProductName, Quantity Sold by Category, Sales by Sub-Category

**Filters:** Category / Brand / Sub Category

**Insights:** Pet Accessories leads sub-categories by sales (₹7.7M), followed by Popcorn and Educational Toys; Pack of 2 (13.6%) and 1 Unit (13.14%) are the largest pack sizes by sales share; top brands each contribute roughly ₹1.4M–1.8M profit.

\---

### 4\. Customer Insights

Who buys: age, membership tier and city.

**KPIs:**

* Total Quantity: **40,668**
* Average Age: **43.48**
* Total Orders: **68,000**
* Average Order Value: **₹8,511**
* One-Time Buyers: **21,900**

**Charts:** Average Discount % by Membership Tier, Sales by AgeGroup, Sales by City, Sales by MembershipTier, Membership Tier Summary (table), Top Customers (table)

**Filters:** Gender / MembershipTier / AgeGroup

**Insights:** Discount rises with tier, from 1.50% (Bronze) to 7.99% (Diamond); the 56–65 age group generates the highest sales (₹113M), and the 66+ group the lowest; Bronze is the largest tier by both customer count (14,390) and sales.

\---

### 5\. Store \& Delivery Performance

Store mix, fulfilment status and delivery speed.

**KPIs:**

* Average Delivery Days: **1.54**
* Cancellation Rate: **6.09%**
* Returned Rate: **4.94%**
* Delivered Rate: **86.0%**
* Total Stores: **90**

**Charts:** Sales by StoreType, Orders by Year and Status, Average Delivery Days by Store Type, Sales by StoreCity, Sales by StoreState, Monthly Orders by Status

**Filters:** StoreType / StoreState / Status

**Insights:** Telangana leads states by sales (₹38M); Chandigarh (₹26M) and Hyderabad (₹25M) lead store cities; order volume grows each year from 2023 to 2025; 86% of orders are delivered, with an average delivery time of about 1.5 days.

\---

## 💡 Key Insights

✅ **Growth \& Profitability**

* Sales grew **20.57%** year over year
* ₹579M in sales and ₹69M in profit at an **11.86%** margin
* Loss rate held at 1.60% overall

✅ **Product Performance**

* 373,417 units sold across 6,000 products, 25 categories and 56 brands
* Average discount is only 3%, with an average unit price of ₹1,604
* Staples \& Grains leads categories; Pet Accessories leads sub-categories

✅ **Customer Behaviour**

* Average customer age is 43.48; the 56–65 group spends the most
* Discounts scale with loyalty tier (Bronze 1.50% → Diamond 7.99%)
* 21,900 one-time buyers: a clear opportunity for repeat-purchase campaigns

✅ **Store \& Delivery Operations**

* 86% of orders delivered, 6.09% cancelled, 4.94% returned
* Average delivery time of 1.54 days across 90 stores
* Telangana, Chandigarh and Hyderabad are the strongest markets

\---

## 🛠️ Skills Demonstrated

|Area|Evidence|
|-|-|
|**Data Modelling**|Retail sales data structured for orders, products, customers and stores|
|**DAX**|Growth, margin, loss-rate, delivery-rate and average-based measures across every page|
|**Dashboard/UX Design**|Consistent 3-slicer + 5-card + 6-chart layout with a shared navigation bar|
|**Data Storytelling**|Logical flow: overview → sales → product → customer → store operations|
|**Domain Knowledge**|Retail KPIs: profit margin, loss rate, membership tiers, fulfilment and delivery efficiency|
|**Visualization Range**|Cards, treemap, donut, bar/column, line, area, stacked column, tables, slicers|

\---

## 🚀 Quick Start

### Prerequisites

* **Power BI Desktop** (free download from [Microsoft](https://powerbi.microsoft.com/en-us/desktop/))

### Steps

1. **Clone this repo**

```bash
   git clone https://github.com/khanhusein/freshmart-dashboard.git
   cd freshmart-dashboard
   ```

2. **Open the dashboard**

   * Double-click `freshmart\_sales\_analysis.pbix`
   * Or open Power BI Desktop → File → Open
3. **Explore the slicers**

   * Filter by Year, State, Category, Brand, Membership Tier, Age Group, Store Type and Order Status on each page

\---

## 📂 Project Structure

```
freshmart-dashboard/
├── README.md
├── LICENSE
├── freshmart\_sales\_analysis.pbix
├── data/
│   └── FreshMart\_Sales\_Analysis.csv
└── screenshots/
    ├── 01\_introduction.png
    ├── 02\_sales\_revenue.png
    ├── 03\_product\_category.png
    ├── 04\_customer\_insights.png
    └── 05\_store\_delivery.png
```

\---

## 🔮 Future Enhancements

* \[ ] Drillthrough pages from summary cards to order-level detail
* \[ ] Row-level security (regional managers see only their stores)
* \[ ] Live/scheduled-refresh data source (replace static import)
* \[ ] Mobile-optimized dashboard views
* \[ ] Repeat-purchase and customer lifetime value analysis
* \[ ] Demand forecasting by category

\---

## 📝 License

This project is provided as-is for educational and portfolio purposes.

\---

## 👤 Author

**Mohammed Husein Khan**

🔗 **Links:**

* [LinkedIn](https://www.linkedin.com/in/mohammed-husein-khan-615645427)
* [GitHub](https://github.com/khanhusein)

\---

## 💬 Questions?

Feel free to open an **Issue** on GitHub or connect via LinkedIn for questions or collaboration opportunities.

\---

**Last Updated:** September 24, 2026  
**Power BI Version:** Latest Desktop  
**Data:** FreshMart transactional sales data (Jan 2023 – Dec 2025)

