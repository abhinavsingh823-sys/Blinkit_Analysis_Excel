# 🛒 Blinkit Grocery Sales Dashboard

An interactive **Excel dashboard** analysing sales, ratings and outlet performance for a Blinkit-style grocery dataset (8,523 records). Built with PivotTables, PivotCharts and Slicers to answer: *what sells, where, and through which kind of outlet?*

![Dashboard preview](images/dashboard.png)

## 📌 Project Overview

| | |
|---|---|
| **Tool** | Microsoft Excel (PivotTables, PivotCharts, Slicers, KPI cards) |
| **Dataset** | 8,523 rows × 13 columns |
| **Focus** | Sales performance by item type, fat content, outlet size, outlet location and outlet type |

## 🎯 Business Questions

1. What are the total sales, average sales per item and average customer rating?
2. Which item categories drive the most revenue?
3. How do Low Fat and Regular products compare?
4. Which outlet sizes, locations (tiers) and types perform best?
5. How do sales vary by outlet establishment year?

## 📊 Key KPIs

| Metric | Value |
|---|---|
| Total Sales | **1,201,681** |
| Average Sales per Item | **140.99** |
| Number of Items | **8,523** |
| Average Rating | **3.97 / 5** |

## 🔍 Key Insights

- **Top categories:** Fruits & Vegetables (~178K) and Snack Foods (~175K) lead, followed by Household (~136K) and Frozen Foods (~119K).
- **Fat content:** Low Fat items generate ~**65%** of sales (776K vs 425K for Regular).
- **Outlet size:** Medium outlets contribute the most (~508K, ~42%), then Small (~445K) and High (~249K).
- **Location:** Tier 3 cities lead (~472K), ahead of Tier 2 (~393K) and Tier 1 (~336K).
- **Outlet type:** Supermarket Type1 accounts for ~**66%** of sales (~788K) — but average sales *per item* is almost identical across all outlet types (~140–142), so Type1's lead comes from **volume** (5,577 records), not higher-value items.
- **Establishment year:** Outlets established in 2018 show the highest sales (~205K).

> ⚠️ These are descriptive findings on a single dataset snapshot; they show patterns, not causes.

## 🗂️ Dataset Description

| Column | Description |
|---|---|
| S.No. | Row number |
| Item Fat Content | Low Fat / Regular |
| Item Identifier | Unique product ID |
| Item Type | Product category (16 types) |
| Outlet Establishment Year | Year the outlet opened |
| Outlet Identifier | Unique outlet ID |
| Outlet Location Type | Tier 1 / Tier 2 / Tier 3 |
| Outlet Size | Small / Medium / High |
| Outlet Type | Grocery Store / Supermarket Type1–3 |
| Item Visibility | Share of display area given to the item |
| Item Weight | Weight of the item |
| Sales | Sales value |
| Rating | Customer rating |

## 🧹 Data Cleaning

- **Fat content labels** were inconsistent (`Low Fat`, `Low fat`, `low fat`) and standardised to **Low Fat**.
- **Item Weight** has 1,463 missing values (~17%); these were left as-is since weight isn't used in the KPIs shown.

## 📁 Repository Structure

```
blinkit-grocery-sales-dashboard/
├── data/
│   └── BlinkIT_Grocery_Data_Excel.xlsx   # data + pivot tables + dashboard
├── images/
│   └── dashboard.png                     # dashboard screenshot
├── README.md
└── .gitignore
```

## ▶️ How to Use

1. Download `data/BlinkIT_Grocery_Data_Excel.xlsx`.
2. Open it in **Microsoft Excel** (slicers need Excel 2013 or later; desktop Excel recommended).
3. Go to the **Dashboard** sheet and use the slicers to filter.
4. The **Sheet Design** sheet holds the pivot tables behind each chart.

## 🛠️ Skills Demonstrated

Data cleaning · PivotTables · PivotCharts · Slicers · KPI design · Dashboard layout · Business storytelling

## 👤 Author

**Abhinav** — B.E. Biotechnology Engineering, UIET, Panjab University
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile) · 💻 [GitHub](https://github.com/your-username)

## 🙏 Acknowledgements

Dataset source: _add the original source/link here (e.g. Kaggle or course instructor)_.
