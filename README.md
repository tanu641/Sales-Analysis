
# 📊 Regional Sales Data Analysis & Power BI Dashboard

**An end-to-end data analytics project** that leverages Python (EDA) and Power BI to uncover sales trends, regional performance, product profitability, and customer insights using 5 years of sales data across U.S. regions.

---

## 🔎 Overview

This project solves a real-world business problem:  
> **Inconsistent sales and profit performance across U.S. regions, limited visibility into top products, customer value, and channel efficiency.**

Using data analytics, we cleaned, analyzed, and visualized regional sales data to:
- Identify high-performing SKUs, regions, and customer segments
- Detect seasonal trends and outliers
- Recommend actionable strategies for growth and margin improvement
- Present findings using a dynamic, self-service **Power BI dashboard**

---

## 🧩 Problem Statement

Sales and profit performance varies across U.S. regions, with limited visibility into:
- Seasonal fluctuations
- Top-selling SKUs
- Profitability by sales channels

**Goal:** Use data to identify growth opportunities and improve regional sales strategy.

---

## 🔍 Approach

The solution is divided into two phases:

1. **EDA using Python**  
   - Clean and transform raw sales data
   - Derive key metrics (e.g., profit, margin)
   - Visualize trends, correlations, and patterns

2. **Dashboard in Power BI**  
   - Enable slicing/filtering by product, region, time, and channel
   - Empower business users with real-time insights

---

## 🧪 Data Overview

- Multiple datasets: Sales, Products, Customers, Budgets, Regions
- Merged into a clean, structured dataset with key features:
  - `order_date`, `customer_name`, `channel`, `product_name`
  - Financials: `revenue`, `cost`, `profit`, `profit_margin_pct`
  - Geography: `state_name`, `us_region`, `lat`, `lon`
  - Planning: `budget (2017)`

---

## 📈 Key Insights

- 📆 **Seasonality:** Revenue peaks in May–June; lowest in January
- 🛍️ **Products:** 25 & 26 dominate sales (~25% of total)
- 🛒 **Channels:** Wholesale = 54.1% of revenue; Export = highest margin
- 🌎 **Geography:** California leads in revenue; West region outperforms others
- 💰 **Customers:** Top customers contribute most revenue with >35% margins

---

## ✅ Recommendations

- Offer **seasonal promotions** in April & January
- Focus on **high-performing SKUs**; re-evaluate low-margin ones
- Expand **Export** for margins, incentivize **Wholesale** for volume
- Replicate California’s success in other regions
- Monitor margins; analyze **discount-heavy orders**

---

## 🧰 Tech Stack

- **Python** (Pandas, Matplotlib, Seaborn) for EDA  
- **Power BI** for interactive dashboards  
- **Excel** for initial data storage and structure  

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `EDA_Regional_Sales_Analysis.ipynb` | Jupyter notebook with EDA steps |
| `Regional Sales Dataset.xlsx` | Raw and structured dataset |
| `SALES REPORT.pbix` | Final Power BI dashboard |
| `PPT - Regional Sales Analysis.pptx` | Presentation summarizing findings |
| `Sales_data(EDA Exported).csv` | Processed dataset used for dashboard |

---

## 🖥️ Dashboard Preview

**Pages:**
- Performance Summary
- Customer Segmentation
- Revenue Scenarios

---

## 🏁 Conclusion

This end-to-end analysis empowered stakeholders to:
- Identify trends and anomalies
- Make informed strategic decisions
- Onboard new datasets for future use

> ✅ Created by Tanu Verma – Aspiring Data Analyst

---
