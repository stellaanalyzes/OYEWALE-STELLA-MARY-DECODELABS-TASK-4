# E-Commerce Sales Dashboard — Power BI

For Task 4 of my internship, I built an e-commerce sales dashboard in Power BI. I visualised key metrics including total revenue, orders, quantity, and AOV alongside trends in monthly revenue, product performance, order status, payment methods, and referral sources.

---

##  Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dashboard Features](#dashboard-features)
- [Key Insights](#key-insights)
- [Screenshots](#screenshots)
- [Tools Used](#tools-used)
- [Key Takeaways](#key-takeaways)

---

##  Project Overview

This project covers the data visualisation phase of the e-commerce sales dataset, completed as Task 4 and the final task of my data analytics internship. Using Power BI, I designed and built an interactive sales dashboard that brings together all the cleaned and analysed data from the previous tasks into a single, visually coherent report. The dashboard allows users to explore performance across time, product, payment method, referral source, and coupon code using slicers and interactive visuals.

---

##  Dataset

The dataset used is the cleaned e-commerce orders table from Task 1, containing 1,200 records across 13 columns. The key fields used in this dashboard include `TotalPrice`, `Quantity`, `OrderStatus`, `Product`, `PaymentMethod`, `ReferralSource`, `CouponCode`, and `Date`.

---

##  Dashboard Features

### KPI Cards
- **Total Revenue** — $1.26M
- **Total Orders** — 1K
- **Total Quantity** — 4K
- **Average Order Value (AOV)** — $1.05K

### Visuals
- **Monthly Revenue Trend** — Line chart showing revenue movement across all 12 months, peaking in May–June (~$135K) and dipping in October (~$88K)
- **Top 4 Products by Revenue** — Horizontal bar chart ranking Printer, Tablet, Monitor, and Phone by total revenue
- **Quantity by Month** — Bar chart showing units sold per month across the year
- **Orders by Order Status** — Bar chart comparing Cancelled, Returned, Pending, Shipped, and Delivered order counts
- **Orders by Payment Method** — Donut chart showing distribution across Cash, Credit Card, Debit Card, Gift Card, and Online
- **Referral Source by Orders** — Bar chart ranking Instagram, Email, Google, Facebook, and Referral by order volume

### Slicers
- **Year** — Filter by 2023, 2024, or 2025
- **Coupon Code** — Filter by No Payment, Save10, or Winter15

---

##  Key Insights

- **Total Revenue** — Revenue reached $1.26M across 1,200 orders and 4,000 units sold. AOV sits at $1,050, a strong indicator of high-value purchasing behaviour.
- **Revenue Trend** — Monthly revenue peaks sharply in May–June (~$135K) before declining to a trough in October (~$88K), a 53% seasonal swing that signals a critical promotional window in April.
- **Top Product** — Printers generated the highest revenue (~$190K), nearly double that 
- **Top Product** — Printers generated the highest revenue (~$190K), nearly double that of Phones (~$100K). Accessory and ink bundle upsells remain an untapped growth lever for this category.
- **Order Status** — Cancellations (250) and Returns (247) both exceed Deliveries (231), a significant fulfilment red flag that calls for root cause analysis on post-checkout drop-off.
- **Quantity Trend** — Units sold peak mid-year and decline in tandem with revenue, confirming a seasonal demand pattern rather than a structural decline.
- **Payment Preference** — Spend is distributed almost evenly across all 5 payment methods (~20% each), indicating no checkout friction. Introducing BNPL could capture additional high-AOV conversions.
- **Referral Source** — Instagram leads with 280 orders, ahead of Email, Google, Facebook, and Referral, making it the strongest acquisition channel.

---

##  Screenshots

### Dashboard
![E-Commerce Sales Dashboard](TASK_4_DASHBOARD.jpg)

### Key Insights
![Key Insights](Task_4_key_insights.png)

---

##  Tools Used

- Microsoft Power BI

---

##  Key Takeaways

- A well-designed dashboard turns raw data into decisions — the seasonal revenue pattern and fulfilment issues would not have been as visible in a spreadsheet alone.
- Cancellations and returns exceeding deliveries is a business-critical finding that would have gone unnoticed without visualisation.
- Interactive slicers by year and coupon code allow stakeholders to drill into specific segments without needing technical skills.
- Power BI's visual hierarchy makes it easy to communicate complex patterns clearly and quickly to any audience.


