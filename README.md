# NetLive - Supply Chain & Inventory Analytics

## 📊 Project Overview

This project analyzes inventory performance, product movement, and supplier efficiency using Power BI.

It simulates a real-world supply chain environment to identify stock imbalances, supplier inefficiencies, and operational risks through data-driven insights.

---

## 🎯 Business Problem

Companies often face challenges such as stock shortages, overstock, and inefficient supplier performance.

This project replicates these challenges to analyze inventory behavior and support better decision-making.

---

## 🔄 End-to-End Data Workflow

This is a complete end-to-end analytics project:

1. **Data Generation (SQL)**

   * Designed and created a simulated dataset representing supply chain operations
   * Built tables for products, suppliers, inventory movements, and warehouses

2. **Data Transformation (Power Query)**

   * Cleaned and structured raw data
   * Standardized formats and handled inconsistencies
   * Prepared the dataset for analysis

3. **Data Modeling (Power BI)**

   * Established relationships between fact and dimension tables
   * Implemented a star schema model

4. **Business Logic (DAX)**

   * Inventory classification: *Stockout, Risk, Healthy*
   * Product rotation calculation
   * Average supplier lead time
   * Inventory KPIs and performance indicators

5. **Data Visualization (Power BI Dashboard)**

   * Built interactive dashboards for analysis and decision-making

---

## 📊 Dataset Details

The dataset was simulated to replicate real-world supply chain operations, including:

* Inventory movements (inbound and outbound)
* Supplier lead times
* Product categories and stock levels
* Logistics costs

This approach enables controlled analysis of scenarios such as stockouts, demand variability, and supplier performance.

---

## 🧱 Data Model

**Fact Table:**

* Inventory Movements

**Dimension Tables:**

* Products
* Suppliers
* Warehouses
* Calendar (Date)

---

## 📈 Key Features

* KPI indicators (Inventory health)
* Inventory status classification (Stockout, Risk, Healthy)
* Product rotation analysis
* Supplier lead time evaluation
* Logistic cost analysis
* Drillthrough for product-level insights

---

## 🧠 Key Insights

* 82.5% of products are in stockout condition
* Stockouts are concentrated in Food and Home categories (>90%)
* Supplier I has the highest lead time (8.14 days)
* Inventory value (~2.38M) is not aligned with demand

---

## 📊 Dashboard Preview

### 🟣 Executive Overview

![Executive Overview](executive-overview.png)

---

### 🔵 Inventory Analysis

![Inventory Analysis](inventory-analysis.png)

---

### 🟢 Product Detail

![Product Detail](product-detail.png)

---

## 🛠 Tools & Technologies

* SQL
* Power BI
* Power Query
* DAX

---

## 🚀 Business Value

This dashboard helps to:

* Identify stock shortages
* Improve demand and supply alignment
* Evaluate supplier performance
* Optimize logistics costs
* Support data-driven decision-making

---

## 📂 Project Structure

```
NetLive-SupplyChain-Analytics/
│
├── dataset.sql  
├── NetLive.pbix  
├── README.md  
├── executive-overview.png  
├── inventory-analysis.png  
├── product-detail.png  
```

---

## 📈 Conclusion

This project demonstrates how data analytics can be applied to monitor inventory performance, detect risks such as stockouts, and support supply chain decision-making through interactive dashboards.

---

## 📌 Author

**Yerson Huaman Noriega**
