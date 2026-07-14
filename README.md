# E-Commerce Sales Analytics Dashboard (Tableau)

> Executive-ready **Tableau dashboard** for e-commerce sales performance — revenue tracking, category drill-down, regional trends and time-based analysis.

---

## 🎯 Business Question

How is revenue moving across **regions, product categories and time**, and where should the merchandising / ops team focus next?

## 🖼️ Dashboard Preview

![Sales dashboard — refined view](img/dashboard-1.jpg)

*Single-page refined executive view with KPI cards, category mix, regional split and trend line.*

## 🧩 What's Inside

- **KPI cards:** total revenue, orders, AOV, YoY growth
- **Category & sub-category** revenue mix
- **Regional split** with drill-down to state / city
- **Time-series** trend of sales & orders
- **Interactive filters:** date range, category, region

## 🧪 Methodology

1. Cleaned and modelled raw transactional data into a star schema (`fact_sales` + `dim_date`, `dim_product`, `dim_geo`)
2. Built calculated fields and LOD expressions for KPIs (`Total Revenue`, `AOV`, `YoY %`, `MoM %`)
3. Built the layout iteratively — the current file is the **refined** version replacing an earlier cluttered draft
4. Applied a consistent colour palette and conditional formatting for exec-friendly readability

## 🧰 Tech Stack

`Tableau Desktop / Public` · Calculated fields · LOD expressions · Star-schema data model

## 📁 Repo Structure

```text
.
├── dashboard/
│   └── Dashboard_1.pdf         # exported PDF preview of the refined dashboard
├── tableau/
│   └── ecommerce_sales.twbx    # Tableau packaged workbook (source)
├── img/
│   └── dashboard-1.jpg
└── README.md
```

## ▶️ How to view

1. Open `tableau/ecommerce_sales.twbx` in **Tableau Desktop** or **Tableau Public** (free)
2. Or preview the exported PDF at `dashboard/Dashboard_1.pdf`
3. Live version (if published): *add your Tableau Public URL here*

---

<sub>MIT-licensed · Author: [Parth Badiger](https://github.com/parthbadiger24-creator)</sub>
