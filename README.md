# Customer-Cohort-Lifetime-Value-Studio
E-commerce Customer Cohort &amp; Lifetime Value Analytics project built with Power BI, DAX, Power Query, Excel, and CSV. Analyzes GMV, AOV, conversion, customer retention, cohorts, returns, channel performance, segmentation, and customer lifetime value through interactive business intelligence dashboards.
# 🛒 E-commerce Customer Cohort & Lifetime Value Analytics

## 📌 Project Overview

The **E-commerce Customer Cohort & Lifetime Value Analytics** project is an end-to-end Business Intelligence solution developed using **Microsoft Power BI, DAX, Power Query, Excel, and CSV data**.

The project provides a unified view of **acquisition, conversion, retention, customer lifetime value, returns, product performance, and revenue trends** through interactive Power BI dashboards.

The objective is to help e-commerce stakeholders make data-driven decisions related to **GMV growth, customer retention, conversion improvement, return management, channel performance, and customer lifetime value**.

---

## 🎯 Business Objective

The primary objective is to build a Power BI analytics workspace covering:

* 📈 Acquisition performance
* 🛒 E-commerce conversion
* 🔄 Customer retention
* 📦 Product & category performance
* 💰 Revenue / GMV analysis
* 🔁 Returns & refund analysis
* 👥 Customer segmentation
* 💎 Customer Lifetime Value (CLV)

The project aims to provide a single trusted analytical view across different e-commerce data sources.

---

## 💼 Business Goals

The dashboard is designed around the following business goals:

* Grow GMV by 25% YoY
* Reduce return rate below 8%
* Increase AOV by 10%
* Improve channel mix toward owned channels
* Increase conversion above 3%
* Increase repeat-purchase rate to 40%

---

## 📊 Key KPIs

The project contains **15 major KPIs**:

| KPI                     | Description                                        |
| ----------------------- | -------------------------------------------------- |
| GMV                     | Gross Merchandise Value                            |
| AOV                     | Average Order Value                                |
| New vs Repeat GMV       | Revenue contribution from new and repeat customers |
| Payment Method Mix      | Payment method contribution                        |
| Cart Abandonment %      | Percentage of carts not converted                  |
| Conversion Rate         | Orders / Sessions                                  |
| YoY GMV Growth          | Year-over-year GMV growth                          |
| Repeat Purchase Rate    | Percentage of returning customers                  |
| Orders                  | Total number of orders                             |
| Top Categories          | Highest-performing product categories              |
| Channel Mix %           | GMV contribution by channel                        |
| Avg Items per Order     | Average quantity of items per order                |
| Avg Shipping Cost       | Average shipping cost                              |
| Customer Lifetime Value | Estimated customer value                           |
| Forecast Next Month GMV | Forecasted future GMV                              |

---

## 🧩 Data Model

The Power BI data model uses a combination of fact and dimension tables.

### Fact Table

**FactOrders**

Contains e-commerce order-line information including:

* OrderLineID
* OrderID
* OrderDate
* CustomerID
* ProductID
* ChannelID
* Quantity
* OrderValue
* Discount
* ShippingCost
* OrderStatus
* PaymentMethod

### Dimension / Supporting Tables

* DimCustomer
* DimProduct
* DimChannel
* DimDate
* DimReturn
* DimSession

The model connects order data with customer, product, channel, date, return and session information for analysis.

---

## 🔄 Data Preparation

Data preparation was performed using **Power Query** and involved:

* Data cleaning
* Data transformation
* Data validation
* Data standardization
* Handling different data sources
* Preparing tables for Power BI data modeling
* Creating relationships between fact and dimension tables

The project assumes normalized currency, linked returns, available GA4 e-commerce events, deduplicated customer IDs and daily order synchronization.

---

## 📐 DAX Analysis

DAX was used to create business metrics and analytical calculations.

Key DAX concepts used include:

* `CALCULATE`
* `DIVIDE`
* `FILTER`
* `ALL`
* `ALLSELECTED`
* `RANKX`
* `DATESINPERIOD`
* `DATESYTD`
* `DATESMTD`
* `SAMEPERIODLASTYEAR`
* `DISTINCTCOUNT`
* `SWITCH`
* `VAR`

### Examples of analytical calculations

* YoY Growth
* Running Total
* Rolling 3-Month Average
* YTD Amount
* MTD Amount
* Prior Year Amount
* Return Rate
* Customer Segmentation
* Percentage of Total
* Total Quantity
* Selected Period

---

## 📊 Dashboard Pages

### 1. E-Commerce Executive Scorecard

Designed for e-commerce leadership.

**KPIs:**

* GMV
* AOV
* Conversion
* Return Rate

**Visuals:**

* KPI cards
* Trend analysis
* Channel mix

**Filters:**

* Period
* Region

---

### 2. Acquisition & Funnel View

Designed for Performance Marketing analysis.

**KPIs:**

* Sessions
* Conversion
* CAC

**Visuals:**

* Funnel
* Source mix

**Filters:**

* Source
* Device

---

### 3. Merchandising Performance

Designed for merchandising analysis.

**KPIs:**

* Top Categories
* Top SKUs
* Return Reasons

**Visuals:**

* Treemap
* Pareto analysis

**Filters:**

* Category
* Brand

---

### 4. Customer Cohort & LTV

Designed for customer growth and retention analysis.

**KPIs:**

* Repeat Rate
* Customer Lifetime Value
* Cohort Retention

**Visuals:**

* Cohort grid
* Retention curve

**Filters:**

* Cohort
* Channel

---

## 🔍 Additional Analysis

The project also includes concepts for:

* Trend Analysis
* Geographic Analysis
* Executive Summary
* Detail Drill-through
* Forecasting
* About / Methodology

These views support deeper exploration of trends, geography, transactions, forecasts and reporting methodology.

---

## 💡 Business Questions

The project is designed to answer questions such as:

1. How are returns and refunds modeled?
2. How is Customer Lifetime Value calculated?
3. How can attribution be measured across channels?
4. How is session data handled against order-level data?
5. What could cause a sudden GMV decline?
6. Which categories and products perform best?
7. How can customer retention be improved?
8. Which channels contribute most to revenue?

---

## 🛠️ Tools & Technologies

| Technology                | Usage                                  |
| ------------------------- | -------------------------------------- |
| **Power BI**              | Dashboard development & visualization  |
| **DAX**                   | Business calculations & KPIs           |
| **Power Query**           | Data cleaning & transformation         |
| **Microsoft Excel**       | Data preparation & source data         |
| **CSV**                   | Marketing data source                  |
| **Data Modeling**         | Relationships and analytical structure |
| **Business Intelligence** | Decision-support reporting             |

---

## 📁 Repository Structure

```text
ecommerce-customer-cohort-ltv-powerbi/
│
├── 📁 PowerBI/
│   └── Ecommerce_Customer_Cohort_LTV.pbix
│
├── 📁 Dataset/
│   ├── PowerBI_Data_Model.xlsx
│   └── MarketingSpend.csv
│
├── 📁 Documentation/
│   ├── Project_Document.pdf
│   └── Customer_Cohort.pdf
│
├── 📁 DAX/
│   └── Measures.md
│
├── 📁 Screenshots/
│   ├── executive-summary.png
│   ├── acquisition-funnel.png
│   ├── merchandising-performance.png
│   └── customer-cohort-ltv.png
│
├── .gitignore
└── README.md
```

---

## 📸 Dashboard Preview

### Executive Summary

Power BI screenshot:

```markdown
(https://github.com/Sai7070-var/Customer-Cohort-Lifetime-Value-Studio/blob/main/Screenshot%202026-08-20%20142849.png
)
```

### Acquisition & Funnel

```markdown
(https://github.com/Sai7070-var/Customer-Cohort-Lifetime-Value-Studio/blob/main/Screenshot%202026-08-20%20142916.png
)
```

### Merchandising Performance

```markdown
!(https://github.com/Sai7070-var/Customer-Cohort-Lifetime-Value-Studio/blob/main/Screenshot%202026-08-20%20142930.png
)
```

### Customer Cohort & LTV

```markdown
!(<img width="1373" height="775" alt="Screenshot 2026-08-20 142946" src="https://github.com/user-attachments/assets/14cdd45a-45b8-4122-bce5-433ed641415d" />
)
```


---

## 📈 Future Improvements

Potential enhancements include:

* Real-time data integration
* Automated scheduled refresh
* Advanced customer segmentation
* Machine learning-based CLV prediction
* More detailed marketing attribution
* Customer churn prediction
* Advanced forecasting
* Automated alerts for KPI changes
* Integration with live e-commerce platforms

---

## 🎓 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Data Transformation
* Data Modeling
* Power BI Dashboard Development
* DAX
* Power Query
* KPI Development
* Customer Cohort Analysis
* Customer Lifetime Value Analysis
* E-commerce Analytics
* Business Intelligence
* Data Visualization
* Business Problem Solving
* Analytical Storytelling

---

## 👨‍💻 Author

**Sai**

**MBA – Business Analytics**

Interested in:

* Data Analyst
* Business Analyst
* Power BI Developer
* Business Intelligence

---

## ⭐ Project

If you find this project useful, feel free to **star ⭐ the repository** and explore the dashboard, DAX calculations and documentation.
