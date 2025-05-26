# 📊 Sales Performance Analysis & Customer Segmentation using MySQL

This end-to-end project analyzes a company's sales data to extract actionable insights using SQL and Power BI. The focus is on performance metrics, customer segmentation, and business impact.

---

## 📁 Dataset Overview

The dataset contains order-level sales information from 2003–2005:

| Table Name    | Description                              |
|---------------|------------------------------------------|
| sales_data    | Core sales facts: revenue, orders, deals |
| customers     | Customer information (country, city)     |
| products      | Product line, code, and details          |

---

## 💼 Business Objectives

- Analyze revenue trends across time, products, countries.
- Identify top-selling product lines and SKUs.
- Segment customers by revenue, frequency, and region.
- Uncover high-impact deal sizes and profitable patterns.

---

## 🛠️ Tools Used

- MySQL: Data cleaning, transformation, analysis
- Power BI: Dashboard creation and storytelling
- GitHub: Version control and project sharing

---

## 🔍 Key SQL Analyses

| Insight                                      | Method                            | Output                             |
|---------------------------------------------|-----------------------------------|------------------------------------|
| Top product lines by revenue                | GROUP BY productline              | Classic Cars = $3.9M               |
| Best-selling individual products            | GROUP BY productcode              | S18_3232 = $288K                   |
| Most profitable deal sizes                  | GROUP BY dealsize                 | Medium = $6.08M                    |
| High-revenue customers                      | GROUP BY customername             | Top 10% = 60% revenue              |
| Regional & city-wise performance            | GROUP BY city, country            | Madrid, NYC, San Rafael top        |
| Order status breakdown                      | GROUP BY status                   | Shipped: 2617, Cancelled: 60       |
| High-performing months                      | GROUP BY month_id                 | Nov > Oct > May                    |

---

## 📊 Dashboard Snapshots

Visuals created in Power BI (included in /images):

- Revenue trend by month/year
- Sales by product line and country
- Deal size segmentation
- Top customers & frequency of orders
- Status distribution overview

---

## 🎯 Business Impact

- Identified top 10% customers driving 60% revenue — enabling focused retention strategy.
- Segmented SKUs by country & deal size — aiding pricing & inventory optimization.
- Visualized seasonality & sales peaks — helpful for marketing and forecasting.
- Provided executive-ready dashboard for decision-makers.

---

## 🧠 Learnings & Takeaways

- Practice of writing optimized SQL queries for business analysis.
- Power BI storytelling and dashboarding best practices.
- Translating raw data into insights with business impact.

---

## 📂 Folder Structure

| Folder/File             | Description                             |
|-------------------------|-----------------------------------------|
| README.md               | Project overview & documentation        |
| /SQL_queries            | All MySQL queries used                  |
| /PowerBI_dashboard      | PBIX file and screenshots               |
| /images                 | Dashboard snapshots                     |
| /data                   | CSVs (anonymized or sample version)     |

---

## ✅ Author

🔗 LinkedIn | 🌐 Portfolio | 📁 GitHub | 📝 Medium Blog  
Add your links here as clickable Markdown.

---

📌 Feel free to fork, clone, or build upon this project!
