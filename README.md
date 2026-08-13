# FreshMart: Sales, Profit & Customer Performance Dashboard

A comprehensive **end-to-end Power BI dashboard** for FreshMart, one of India's largest retail hypermarket chains, providing deep insights into sales & revenue, product & category performance, customer behaviour, and store & delivery operations — all in one integrated 5-page interactive dashboard.

> 📊 Power BI Desktop | 5 report pages | Multi-dimensional analysis | Real-time KPIs & trending visualizations

---

## 📌 Project Overview

FreshMart is one of India's largest retail hypermarket chains, selling groceries, food & beverages, apparel, footwear, electronics, personal care, and home & kitchen products across the country. This dashboard gives category managers, store/regional heads, and leadership a **360° view** of revenue, profitability, product performance, customer segments, and delivery efficiency — enabling faster, data-backed decisions on inventory, pricing, marketing, and store operations.

The dashboard spans **5,10,000 orders across 90 stores, 58 cities, and 40 states**, covering **6,000 products** in **25 categories** and **117 sub-categories**, from **56 brands**, over **3 years (January 2023 – December 2025)**.

---

## 🖼️ Dashboard Preview

### Introduction & Project Overview
![Introduction](screenshots/01_introduction.png)

### Sales & Revenue Overview
![Sales & Revenue Overview](screenshots/02_sales_revenue.png)

### Product & Category Performance
![Product & Category Performance](screenshots/03_product_category.png)

### Customer Insights
![Customer Insights](screenshots/04_customer_insights.png)

### Store & Delivery Performance
![Store & Delivery Performance](screenshots/05_store_delivery.png)

---

## 📊 Key Dashboard Metrics

| Metric | Value | Insight |
|--------|-------|---------|
| **Total Sales** | ₹57,87,31,956.12 | Revenue across all stores (2023–2025) |
| **Total Orders** | 68K | Complete order volume across all stores |
| **Total Profit** | ₹68.66M | Net profit across the analysis period |
| **Profit Margin** | 11.86% | Overall profitability |
| **Loss Rate** | 1.60% | Share of loss-making transactions |
| **YoY Growth** | 20.57% | Year-over-year sales growth |
| **Total Stores** | 90 | Across 58 cities and 40 states |
| **Delivered Rate** | 86.0% | Successful delivery performance |
| **Average Delivery Days** | 1.54 | Average fulfillment time |
| **Total Quantity Sold** | 373,417 units | Across 6,000 products |

---

## 📑 Report Pages

### 1. **Introduction**
Project overview and dataset snapshot:
- **YoY Growth:** 20.57%
- **Total States Covered:** 40
- **Total Brands:** 56
- **Total Categories:** 25
- **Total Cities Covered:** 77

Business summary describing FreshMart's scope, dataset, and dashboard objectives.

---

### 2. **Sales & Revenue Overview**
**KPIs:**
- **Total Orders:** 68K
- **Total Sales:** ₹57,87,31,956.12
- **Total Profit:** ₹68.6628554M
- **Profit Margin:** 11.86%
- **Loss Rate:** 1.60%

**Visualizations:**
- Sales Trend Over Time (2023–2025 line chart)
- Sales by State (bar chart)
- Total Profit by Quarter and Year (line chart)
- Sales by Category (bar chart)
- Loss-Rate % by Category (bar chart)
- Sales and Profit by Month (combo chart)

**Filters:** Year, State, Category

---

### 3. **Product & Category Performance**
**KPIs:**
- **Total Quantity Sold:** 373,417
- **Total Product:** 6,000
- **Average Unit Price:** ₹1,604
- **Average Discount %:** 3%
- **Total Cost:** 510M

**Visualizations:**
- Sales by Category and SubCategory (matrix)
- Profit by Brand (bar chart)
- Sales by PackSize (donut: Pack of 2, 1 Unit, Pack of 6)
- Sales by ProductName (bar chart)
- Total Quantity Sold by Category (bar chart)
- Total Sales by SubCategory (bar chart)

**Filters:** Category, Brand, Sub_Category

---

### 4. **Customer Insights**
**KPIs:**
- **Total Quantity:** 40,668
- **Average Age:** 43.48
- **Total Orders:** 68K
- **Average Order Value:** 8.5K
- **One-Time Buyers:** 22K

**Visualizations:**
- Average Discount % by Membership Tier (bar chart)
- Sales by AgeGroup (bar chart)
- Sales by City (bar chart)
- Sales by Membership Tier (bar chart)
- Membership Tier summary table (Average Discount %, Count of CustomerID)
- Top Customers table (CustomerID, CustomerName, Total Sales)

**Filters:** Gender, MembershipTier, AgeGroup

**Key Insight:** Diamond tier customers receive the highest average discount (7.99%) despite being the smallest segment by count (2,038 customers).

---

### 5. **Store & Delivery Performance**
**KPIs:**
- **Average Delivery Days:** 1.54
- **Cancellation Rate:** 6.09%
- **Returned Rate:** 4.94%
- **Delivered Rate:** 86.0%
- **Total Store:** 90

**Visualizations:**
- Sales by StoreType (bar chart)
- Orders by Year and Status (Cancelled, Delivered, Pending, Returned)
- Average Delivery Days by StoreType (bar chart)
- Sales by StoreCity (bar chart)
- Sales by StoreState (bar chart)
- Total Orders by Month and Status (line chart)

**Filters:** StoreType, StoreState, Status

---

## 💡 Key Business Insights

✅ **Sales Performance**
- Total revenue: ₹57.87 Cr across 68K orders, with 20.57% YoY growth
- Top-performing category: Staples & Groceries (₹34M)
- Top state by sales: Telangana (₹38M)

✅ **Profitability**
- Overall profit margin of 11.86% with a low 1.60% loss rate
- Kitchen & Home Essentials carries the highest loss-rate % by category (2.06%)

✅ **Product & Category**
- 6,000 SKUs across 25 categories and 117 sub-categories from 56 brands
- Average discount held tight at 3%, indicating disciplined pricing strategy
- Pack of 2 leads sales share by pack size (13.6%)

✅ **Customer Behaviour**
- 40,668 total customer quantity with an average customer age of 43.48
- 22K one-time buyers signal an opportunity to improve repeat-purchase rate
- Diamond members get the richest discounts (7.99%) versus Bronze (1.50%)

✅ **Store & Delivery**
- 86.0% delivery success rate with a fast average delivery time of 1.54 days
- 6.09% cancellation rate and 4.94% return rate leave room for fulfillment improvements
- Chandigarh, Hyderabad, and Kohima are the top-performing cities by sales

---

## 🛠️ Technical Skills Demonstrated

| Area | Evidence |
|---|---|
| **Data Modelling** | Multi-table relational model (Orders, Products, Customers, Stores) |
| **DAX** | YoY growth, delivery rate, profit margin, loss rate, discount % measures |
| **Dashboard Design** | 5-page dashboard with consistent KPI + chart layout |
| **Data Storytelling** | Logical flow: Intro → Sales & Revenue → Product & Category → Customer Insights → Store & Delivery |
| **Domain Knowledge** | Retail/hypermarket KPIs: category profitability, membership tiering, delivery efficiency |
| **Visualization Range** | KPI cards, line/bar/donut charts, matrices, tables, treemap-style breakdowns |

---

## 🚀 How to Use

### Prerequisites
- **Power BI Desktop** (free download from [Microsoft](https://powerbi.microsoft.com/en-us/desktop/))

### Steps
1. **Download the dashboard**
   ```
   FreshMart_sales_Analysis_project.pbix
   ```

2. **Open in Power BI Desktop**
   - Double-click the file
   - Or: File → Open → Select .pbix

3. **Explore the data**
   - Navigate through 5 pages
   - Use slicers to filter by Year, State, Category, StoreType, MembershipTier, and more
   - Hover over charts for drill-down details

---

## 📂 Project Structure

```
FreshMart-Sales-Analysis/
├── README.md
├── FreshMart_sales_Analysis_project.pbix
├── LICENSE
└── screenshots/
    ├── 01_introduction.png
    ├── 02_sales_revenue.png
    ├── 03_product_category.png
    ├── 04_customer_insights.png
    └── 05_store_delivery.png
```

---

## 📈 Dataset Summary

**Time Period:** January 2023 – December 2025 (3 years)

| Dimension | Count |
|-----------|-------|
| Total Orders | 5,10,000 |
| Total Stores | 90 |
| Cities Covered | 58 (77 including secondary breakdowns) |
| States Covered | 40 |
| Item Categories | 25 |
| Sub-Categories | 117 |
| Products | 6,000 |
| Brands | 56 |
| Delivery Status Types | 4 (Delivered, Cancelled, Pending, Returned) |

**Data Quality:** Complete transactional dataset with no missing values in key metrics.

---

## 🔮 Future Enhancements

- [ ] Predictive demand forecasting by category and store
- [ ] Real-time inventory and stockout alerts
- [ ] Customer segmentation and churn prediction model
- [ ] Dynamic pricing and discount recommendation engine
- [ ] Delivery route optimization (map integration)
- [ ] Customer lifetime value (CLV) analysis
- [ ] A/B testing dashboard for promotional campaigns

---

## 📝 License

This project is protected under the MIT License. See [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Mohammed Husein Khan**

🔗 **Links:**
- [LinkedIn](https://www.linkedin.com/in/mohammed-husein-khan-615645427)
- [GitHub](https://github.com/khanhusein)

---

## 💬 Questions?

Feel free to open an **Issue** on GitHub or connect via LinkedIn for questions, feedback, or collaboration opportunities.

---

**Dataset:** Simulated/Synthetic FreshMart transactional sales data (Jan 2023 – Dec 2025)
**Last Updated:** August 14, 2026
**Power BI Version:** Latest Desktop
**Pages:** 5 | **Tables:** Multi-dimensional | **KPIs:** 25+
