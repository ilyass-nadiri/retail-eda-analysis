# 📊 Retail Sales — Exploratory Data Analysis

An end-to-end exploratory data analysis (EDA) project analyzing retail sales performance, customer behavior, and product trends for a fictional Moroccan retail company using Python and Pandas.

---

## 📋 Project Overview

**Role:** Data Analyst  
**Tool:** Python (Pandas, NumPy), Jupyter Notebook  
**Skills:** Data Cleaning, EDA, GroupBy Aggregations, Pivot Tables, Merging, Time Series Analysis

This project simulates a real business scenario where the Head of Sales requests a full analysis of 2024 sales data to present to investors.

---

## 🗂️ Dataset

| Property | Detail |
|---|---|
| Records | 200 orders |
| Period | January 2024 → December 2024 |
| Customers | 49 unique customers |
| Cities | 6 (Casablanca, Rabat, Marrakech, Fes, Tangier, Agadir) |
| Categories | 5 (Electronics, Clothing, Home, Beauty, Sports) |
| Features | order_id, customer_id, city, category, product, quantity, unit_price, order_date, status |

---

## 📁 Notebook Structure

```
retail_eda.ipynb
│
├── 🔍 Preliminary        → Data inspection, type fixing, feature engineering
├── 📊 Section 1          → Business Overview (KPIs at a glance)
├── 💰 Section 2          → Revenue Analysis (by category, city, order size)
├── 👥 Section 3          → Customer Analysis (segmentation, loyalty, city depth)
├── 🛍️  Section 4          → Product Analysis (top products, cancellation rates)
├── ⏱️  Section 5          → Time Analysis (monthly trends, day of week, MoM change)
└── 📝 Section 6          → Key Findings & Recommendations
```

---

## 🔍 Key Findings

1. **Total 2024 Revenue:** 619,675 dh across 200 orders — 82% completion rate
2. **Electronics dominates** at 67.9% of total revenue (333,750 dh)
3. **VIP customers** (3+ orders) generate 67.7% of revenue despite being a minority
4. **Agadir** has the highest average order value — indicating a high-value customer base
5. **Electronics peaks** in tech launch months (Feb, Apr, Oct, Dec) — aligned with global product release cycles
6. **Beauty category** has the most units sold but lowest revenue — driven by low unit pricing
7. **42.9% cancellation rate** on Jeans and Tablet — significantly above the 12% average
8. **Weekend orders are surprisingly low** — potential website/app issue outside business hours
9. **Beauty underperforms in February** despite Valentine's Day — a missed commercial opportunity

---

## ⚠️ Key Concerns

- Revenue heavily concentrated in Electronics (67.9%) — high business risk if category declines
- August is the lowest revenue month (10,025 dh) — significant seasonal dip
- High cancellation rate on specific products needs urgent investigation

---

## 💡 Recommendations

1. **Investigate cancellations** on Jeans and Tablet (delivery, sizing, pricing issues)
2. **Launch loyalty programs** for Occasional customers to convert them to Regular buyers
3. **Valentine's Day Beauty campaign** — capture the February opportunity currently being missed
4. **Diversify revenue** — reduce Electronics dependency by growing Clothing and Sports

---

## 🛠️ How to Run This Project

1. Clone this repository
2. Install dependencies: `pip install pandas numpy jupyter`
3. Open `retail_eda.ipynb` in Jupyter Notebook or VS Code
4. Run all cells from top to bottom

---

## 🧰 Technologies Used

- **Python 3** — programming language
- **Pandas** — data manipulation and analysis
- **NumPy** — numerical computing
- **Jupyter Notebook** — interactive analysis environment
- **Git & GitHub** — version control and portfolio hosting
