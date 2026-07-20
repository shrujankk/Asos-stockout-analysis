# 📊 ASOS Stockout Analysis
A business-focused data analytics project that analyzes inventory availability, quantifies revenue at risk from stockouts, and delivers actionable recommendations using real-world e-commerce data.
> **Status:** 🚧 In Progress  
> **Next Update:** Interactive Power BI Dashboard

---

## 📌 Project Overview

Inventory availability plays a critical role in the success of any e-commerce business. Stockouts can result in lost sales, poor customer experience, and inefficient inventory planning.

This project presents an end-to-end data analytics workflow using an apparel dataset from **ASOS** to identify inventory inefficiencies, estimate revenue at risk due to stockouts, and generate actionable business insights.

Rather than simply visualizing the data, the analysis focuses on solving a practical retail problem through data-driven decision making.

---

## 🎯 Business Problem

Retail companies frequently lose potential revenue when customers cannot purchase products because they are out of stock.

This project investigates:

- Which brands experience the highest stockout rates?
- How much potential revenue is being lost?
- Which brands should be prioritized for inventory replenishment?
- How does product pricing relate to stock availability?

---

## 🎯 Objectives

- Clean and preprocess raw e-commerce product data.
- Standardize inconsistent pricing information.
- Extract brand-level insights from product descriptions.
- Calculate stock availability metrics.
- Estimate potential revenue loss caused by stockouts.
- Create business-focused visualizations.
- Generate actionable recommendations for inventory optimization.

---

## 📂 Dataset

The project uses an apparel product dataset containing information scraped from the **ASOS** e-commerce platform.

The dataset includes attributes such as:

- Product Information
- Brand
- Price
- Available Sizes
- Stock Availability

> **Note:** The dataset is not included in this repository because it exceeds GitHub's web upload size limit. The notebook documents the complete preprocessing and analysis workflow.

---

## ⚙️ Methodology

The project follows the following workflow:

1. Imported the raw dataset into Python.
2. Cleaned and standardized pricing information.
3. Removed invalid and inconsistent values.
4. Extracted brand information from product descriptions.
5. Calculated stock availability metrics.
6. Estimated potential revenue loss (phantom revenue).
7. Aggregated metrics at the brand level.
8. Performed exploratory data analysis (EDA).
9. Created business-focused visualizations.
10. Generated inventory optimization recommendations.

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Programming Language | Python |
| Data Analysis | Pandas |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Google Colab |
| Version Control | Git & GitHub |
| Business Intelligence *(Upcoming)* | Microsoft Power BI |

---

## 📈 Key Insights

The analysis identified several important inventory trends:

- High-value brands showed greater potential revenue loss from stockouts.
- Several brands consistently experienced higher stockout percentages.
- Revenue risk varied significantly across brands.
- Inventory prioritization opportunities were identified through brand-level analysis.

---

## 📊 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Stockout Analysis
      │
      ▼
Revenue Risk Estimation
      │
      ▼
Business Insights
      │
      ▼
Inventory Recommendations
```

---

## 📁 Repository Structure

```text
asos-stockout-analysis/
│
├── inventory_stockout_analysis.ipynb
├── requirements.txt
└── README.md
```

## 📷 Dashboard

The dashboard will include:

- Revenue at Risk KPI
- Stockout Rate KPI
- Brand Performance Analysis
- Executive Summary Dashboard

---

## 💼 Business Value

This project demonstrates how data analytics can support inventory management by:

- Identifying revenue leakage caused by stockouts.
- Supporting inventory replenishment decisions.
- Improving operational efficiency.
- Delivering actionable business insights.
