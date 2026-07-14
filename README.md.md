# E-Commerce Sales Analytics Dashboard (Tableau)

> Executive-ready **Tableau dashboard** for e-commerce sales performance — revenue tracking, category drill-down, regional trends and time-based analysis.

---

## 🎯 Business Question

How is revenue moving across **regions, product categories and time**, and where should the merchandising / ops team focus next?

## 🖼️ Dashboard Preview

*Dashboard screenshots available in the repo — see `Dashboard 1 Image` and `Refined Dashboard 2 image`.*

## 🧩 What's Inside

- **KPI cards:** total revenue, orders, AOV, YoY growth
- **Category & sub-category** revenue mix
- **Regional split** with drill-down to state / city
- **Time-series** trend of sales & orders
- **Interactive filters:** date range, category, region

### Two dashboard versions included:

| Version | Description |
|---|---|
| **Dashboard 1** | Initial exploratory layout with comprehensive data views |
| **Refined Dashboard 2** | Clean executive view — streamlined KPIs, clearer visual hierarchy, presentation-ready |

## 🧪 Methodology

1. Cleaned and modelled raw transactional data into a star schema (`fact_sales` + `dim_date`, `dim_product`, `dim_geo`)
2. Built calculated fields and LOD expressions for KPIs (`Total Revenue`, `AOV`, `YoY %`, `MoM %`)
3. Iterated from an initial exploratory dashboard to a **refined executive version** with clearer visual hierarchy
4. Applied a consistent colour palette and conditional formatting for exec-friendly readability

## 🧰 Tech Stack

`Tableau Desktop / Public` · Calculated fields · LOD expressions · Star-schema data model

## 📁 Repo Structure

```text
.
├── Dashboard 1                  # Initial dashboard version (PDF / image export)
├── Dashboard 1 Image            # Screenshot of Dashboard 1
├── Refined Dashboard 2          # Cleaned-up executive dashboard
├── Refined Dashboard 2 image    # Screenshot of refined version
├── LICENSE
└── README.md
```

## ▶️ How to View

1. Preview the dashboard exports directly in the repo
2. If you have the `.twbx` workbook, open in **Tableau Desktop** or **Tableau Public** (free)
3. Dashboard images render inline on GitHub for quick preview

---

<sub>MIT-licensed · Author: [Parth Badiger](https://github.com/parthbadiger24-creator)</sub>
