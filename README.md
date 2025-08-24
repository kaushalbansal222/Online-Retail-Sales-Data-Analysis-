# Online-Retail-Sales-Data-Analysis-

## Project Overview

This project analyzes **UK-based e-commerce transactions (2010–2011)** to extract actionable business insights. It demonstrates **end-to-end data analytics**:

* Cleaning and preprocessing raw data
* Performing **exploratory data analysis (EDA)**
* Calculating **key retail KPIs**
* Conducting **customer segmentation via RFM analysis**
* Building **visualizations** that highlight business opportunities
* Analyzing **cancellations & loss recovery**

---

## Dataset

* **Source**: [UCI Online Retail Data](https://archive.ics.uci.edu/ml/datasets/online+retail)
* **Scope**: \~500,000 transaction records
* **Period**: Dec 2010 – Dec 2011
* **Key Fields**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## Tech Stack

* **Programming**: Python (Jupyter Notebook)
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Datetime
* **Analysis Techniques**: EDA, KPI Computation, RFM Segmentation, Cancellation Analysis, Pareto Analysis

---

## Metrics & Analysis

### Sales & Revenue Metrics

* **Top Products by Revenue** → Identified best-performing SKUs.
* **Revenue by Country** → UK dominates, but strong contributions from Netherlands, Germany, and France.
* **Monthly Revenue Trend** → Clear seasonality, with peaks around Christmas.
* **Average Order Value (AOV)** → Average spend per transaction.
* **Customer Lifetime Value (CLV)** → Approximate total revenue per customer.
* **Revenue per Country per Customer** → Market profitability comparison.

### Customer Behavior Metrics

* **Repeat Purchase Rate** → % of customers who made multiple purchases.
* **Churn / Inactive Customers** → Customers with no purchase in the last 3+ months.
* **Customer Segmentation (RFM)**:

  * **Recency**: Days since last purchase
  * **Frequency**: Number of purchases
  * **Monetary**: Total spend
  * Segments: Champions, Loyal, At-Risk, Lost, etc.

### Cancellations Analysis

Unlike many projects that drop cancellations, this analysis **keeps them** to understand operational inefficiencies:

* **Total Cancellations** → Number of cancelled invoices
* **Cancelled Items** → Quantity of items cancelled
* **Cancelled Value (£)** → Total monetary value of cancellations
* **Cancellation Rate (Invoices)** → % of total invoices that are cancellations
* **Cancellation Rate (Revenue)** → % of revenue lost due to cancellations
* Identified **seasonality in cancellations** to detect potential logistics or supply chain issues

### Strategic Insights

* **Pareto Principle (80/20 Rule)** → Top 20% of customers contribute \~60–70% of revenue.
* **Seasonality Analysis** → Strong Q4 performance (holiday effect).
* **Product Mix Optimization** → A small set of products disproportionately drives sales.
* **Cancellation Patterns** → High cancellation rates linked to certain SKUs and busy holiday months.

---

## Key Visualizations  

- **Top 10 Products by Revenue**  
  ![Top Products](plots/top_products.png)  

- **Monthly Sales Trend**  
  ![Monthly Revenue](plots/monthly_revenue.png)  

- **Top 10 Countries by Revenue**  
  ![Top Countries](plots/top_countries.png)  

- **Customer Recency Distribution**  
  ![Recency Distribution](plots/recency_distribution.png)  

- **Revenue vs Cancellations Over Time**  
  ![Cancellations vs Revenue](plots/cancellations_vs_revenue.png)  

- **Monthly Cancellation Rate (%)**  
  ![Cancellation Rate](plots/cancellation_rate.png)  

---

## Key Findings

* Top 5 products generated a large share of revenue.
* UK market dominates, but some smaller countries show higher **average spend per customer**.
* Seasonality is strong: **holiday months account for disproportionate sales and cancellations**.
* **\~20% of customers drive \~60% of revenue**, highlighting the importance of customer retention.
* RFM segmentation revealed clear **champion and loyal customer groups**, providing opportunities for targeted marketing.
* **Cancellations accounted for a measurable share of transactions**, with peaks in Q4 → signals potential supply chain / order fulfillment inefficiencies.

---

## Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Key KPI Computation (AOV, CLV, Repeat Rate, Churn, Pareto)
* Customer Segmentation (RFM)
* **Cancellation Analysis & Risk Detection**
* Visualization & Storytelling with Python
* Translating analytics into **business insights**

---

This project is part of my **portfolio** to demonstrate how Python-based analytics can be applied to **real-world business datasets** for decision-making, including **both revenue growth opportunities and operational risk management**.
