# Global-Superstore-Business-Intelligence-Dashboard

##  Project Overview

This project was developed as part of the **AnalystLab Africa Data Analytics Internship – Week 2**.

The objective is to transform Global Superstore business data into actionable insights using **Microsoft Power BI**.

The project focuses on sales performance, profitability, customer segments, product categories, regional performance, and geographical analysis.

---

##  Business Objective

The main objective is to analyze business performance and identify trends, profitability drivers, risks, and opportunities that can support better decision-making.

The analysis focuses on:

- Sales performance
- Profitability
- Profit margins
- Regional performance
- Product categories
- Customer segments
- Geographical performance
- Business risks and opportunities

---

##  Dataset

The project uses the **Global Superstore** dataset.

The dataset contains:

- 51,290 rows
- 25,035 orders
- 2011–2014 period
- 7 markets
- 3 main product categories

The dataset contains information related to orders, customers, products, sales, discounts, profit, regions, and countries.

---

##  Tools Used

- **Microsoft Power BI** – Data visualization and dashboard development
- **Power Query** – Data preparation and transformation
- **DAX** – KPI and business calculations
- **GitHub** – Project documentation and version control

---

##  Key KPIs

The dashboard tracks the following key performance indicators:

| KPI | Value |
|---|---:|
| Total Sales | $12.64M |
| Total Profit | $1.47M |
| Total Orders | 25,035 |
| Average Sales | $504.99 |
| Profit Margin | 11.61% |

---

##  Dashboard

The interactive Power BI dashboard includes:

- Sales Trend
- Sales by Region
- Profit by Region
- Sales by Category
- Profit by Category
- Sales by Customer Segment
- Sales by Country
- Category Performance Matrix

It also includes interactive filters for:

- Year
- Category
- Region

---

##  Key Business Insights

### 1. Strong sales growth

Sales increased significantly over the analyzed period, rising from approximately **$2.26M to $4.30M**.

### 2. Technology leads profitability

Technology generated approximately **$4.74M in sales** and achieved a **13.99% profit margin**, making it the strongest-performing major category.

### 3. Furniture has weaker profitability

Furniture generated approximately **$4.11M in sales**, but its profit margin was only **6.94%**, significantly below Technology and Office Supplies.

### 4. Regional profitability varies significantly

Profitability differs substantially across regions, highlighting opportunities for better resource allocation and regional strategy.

### 5. Discounting can negatively affect profitability

The analysis indicates a negative relationship between discount levels and profit, highlighting the importance of controlling excessive discounting.

---

##  Business Risks

The analysis identifies several risks:

- Excessive discounting can reduce profitability.
- Some regions generate significantly lower margins.
- Certain products contribute disproportionately to losses.

---

##  Business Opportunities

Key opportunities identified include:

- Expanding high-performing Technology products.
- Replicating successful strategies from high-margin regions.
- Improving profitability through better discount management.

---

##  Recommendations

Based on the analysis, the following actions are recommended:

1. Strengthen discount governance and monitor high-discount transactions.
2. Review structurally loss-making products and consider pricing or assortment changes.
3. Prioritize investment in high-performing Technology products.
4. Analyze and replicate strategies used by high-margin regions.
5. Monitor loss-making orders as a recurring management KPI.
6. Develop targeted strategies for customer segments with growth potential.

---

## Project Structure

```text
Global-Superstore-PowerBI/
│
├── README.md
│
├── data/
│   └── Global_Superstore.csv
│
├── powerbi/
│   └── Global_Superstore_Dashboard.pbix
│
├── reports/
│   ├── Business_Intelligence_Overview.pdf
│   └── Executive_Summary.pdf
│
└── dashboard/
    └── dashboard.png
