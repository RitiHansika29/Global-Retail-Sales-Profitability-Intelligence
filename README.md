# Global Retail Sales & Profitability Intelligence


An end-to-end **Business Intelligence and Business Analyst project** built using Microsoft Power BI to analyze global retail sales, profitability, customer segments, products, markets, and regional performance.

The project transforms raw retail transaction data into an interactive executive dashboard and actionable business insights.

---

## 📌 Project Overview

Retail businesses generate large volumes of transactional data, but raw data alone does not provide clear answers to important business questions.

This project analyzes a global retail dataset to answer questions such as:

- How are overall sales and profitability performing?
- Which product categories and products generate the most sales?
- Which categories contribute the most profit?
- Which markets and regions perform strongly?
- How does customer segment distribution look?
- How do discounts relate to profitability?
- Which areas require further business investigation?

The project follows a complete Business Analyst / BI workflow:

**Business Question → Data → Data Cleaning → Data Modeling → DAX → Visualization → Insight → Business Recommendation**

---

## 🎯 Business Objectives

The main objectives of this project are to:

- Analyze overall sales performance
- Measure total profit and profitability
- Identify high-performing product categories
- Analyze product and sub-category performance
- Compare regional and market performance
- Understand customer segment contribution
- Analyze the relationship between discounts and profit
- Build an executive-level Power BI dashboard
- Convert data into meaningful business insights

---

## 📊 Dataset

**Dataset:** Global Superstore / Superstore Retail Dataset

The dataset contains approximately **51,290 retail transaction records** and **27 columns**.

### Important fields include:

| Field | Description |
|---|---|
| Order ID | Unique identifier for an order |
| Order Date | Date when the order was placed |
| Ship Date | Date when the order was shipped |
| Ship Mode | Shipping method |
| Customer ID | Unique customer identifier |
| Customer Name | Customer name |
| Segment | Customer segment |
| City | Customer city |
| State | Customer state |
| Country | Customer country |
| Market | Geographic market |
| Region | Geographic region |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Product name |
| Sales | Revenue generated |
| Quantity | Quantity sold |
| Discount | Discount applied |
| Profit | Profit generated |
| Shipping Cost | Shipping cost |
| Order Priority | Priority of the order |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**
- **Business Analysis**
- **GitHub**

---

# 🔄 Data Preparation

The raw dataset was prepared using Power Query before building the dashboard.

### Main preparation steps

1. Imported the Superstore dataset into Power BI
2. Inspected column names and data types
3. Enabled column profiling
4. Checked data quality across the complete dataset
5. Verified date fields
6. Removed unnecessary fields
7. Preserved legitimate negative-profit transactions
8. Loaded the cleaned dataset into the Power BI model

The main transaction table was renamed to:

**Sales**

---
