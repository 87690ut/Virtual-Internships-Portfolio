# 📊 Tata Data Visualisation: Empowering Business with Effective Insights

## 📌 Project Overview
This repository contains the analysis and dashboards created during the **Tata Data Visualisation Virtual Experience Program** on Forage. The core objective of this project was to assist the CEO and CMO of an online retail store in making data-driven decisions for global expansion and targeted marketing by analyzing their 2011 sales data.

## 🛠️ Tools & Technologies Used
* **Data Visualization & Modeling:** Microsoft Power BI
* **Data Cleaning & Transformation:** Power Query
* **Domain:** Retail Analytics, Business Intelligence

## 🧹 Data Cleaning & Pre-processing
Before generating insights, due diligence was performed to ensure 100% data accuracy:
* **Filtered Returns:** Excluded all records where `Quantity < 1` to remove return orders from the sales analysis.
* **Filtered System Errors:** Excluded records where `Unit Price < $0` to ensure only valid purchases were analyzed.
* **Feature Engineering:** Created a custom `Revenue` column using the DAX formula: `Revenue = Quantity * Unit Price`.

## 📈 Key Visuals & Business Insights

### 1. Monthly Revenue Trend (CEO Perspective)
* **Visual:** Line Chart showing the revenue trend for the year 2011.
* **Insight:** Sales remained relatively stable throughout the year but experienced a massive spike in **November**.
* **Actionable Recommendation:** Supply chain and inventory teams should proactively build stock and prepare for the peak holiday season demand starting in late Q3.

### 2. Top 10 Countries by Revenue & Quantity (CMO Perspective)
* **Visual:** Clustered Column Chart (Excluding the United Kingdom to prevent home-market bias).
* **Insight:** The **Netherlands** and **EIRE (Ireland)** emerged as the strongest international markets in both sales volume and total revenue.
* **Actionable Recommendation:** Allocate a higher percentage of the marketing budget to these high-performing European countries.

### 3. Top 10 VIP Customers (CMO Perspective)
* **Visual:** Column Chart sorted in descending order by Revenue (Excluding NULL Customer IDs).
* **Insight:** A small segment of high-value customers contributes significantly to the overall revenue.
* **Actionable Recommendation:** Implement a targeted VIP Loyalty Program to retain these top buyers and incentivize repeat purchases.

### 4. Global Product Demand (CEO Perspective)
* **Visual:** Map Chart displaying demand (Quantity) across different regions globally (Excluding the UK).
* **Insight:** The largest demand bubbles are heavily concentrated in the **European region**, with secondary demand in regions like Australia.
* **Actionable Recommendation:** If the business aims to open physical stores or new distribution hubs, mainland Europe should be the primary target for geographical expansion.

---

## 👨‍💻 Author
**Uttam Tiwari** *Data Analyst | BCA Undergrad* *Driven by a passion for transforming raw data into meaningful business strategies using Power BI, SQL, Excel, Google DOC and Python.*
