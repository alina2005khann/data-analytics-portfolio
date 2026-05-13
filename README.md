# 📊 Data Analytics Portfolio
### Alina Khan | MySQL · Python · Power BI · Excel | 2026

---

## 🔥 Project 1: Superstore Sales Analytics

### 🎯 Business Problem
Retail company had no visibility into which products,
regions and customers were profitable vs losing money.

### 🛠️ Tools Used
- **MySQL** — Data cleaning + 8 business analysis queries
- **Python** — EDA, visualization 
- **Power BI** — 2-page interactive dashboard

### 📊 Dataset
- Source: Superstore Sales (Kaggle)
- Size: 9,994 rows × 23 columns
- Period: 2014–2017

### ✅ What I Did

**1. Data Cleaning (MySQL)**
- Fixed Region casing (west/WEST → West)
- Corrected Category typos (Furnitur → Furniture)
- Handled NULL values in Sales and Profit
- Removed 5 duplicate rows
- Fixed negative Delivery Days
- Converted dates from VARCHAR to DATE

**2. Business Analysis (8 SQL Queries)**
- Category and Sub-Category profit analysis
- Regional performance comparison
- Monthly revenue trends with RANK() OVER PARTITION BY
- VIP customer identification with profit margins
- Discount impact analysis
- Shipping mode efficiency

**3. Python EDA **
- Connected Python to MySQL via SQLAlchemy
- Built 5 professional charts (Matplotlib + Seaborn)

**4. Power BI Dashboard (2 Pages)**
- Page 1: KPI Cards + Monthly Trend + Region Performance
- Page 2: Category + Segment + Discount + VIP Customers
- Synchronized slicers across both pages
- Insight boxes below every chart

### 📈 Key Findings

| Finding | Result |
|---|---|
| Best Category | Technology — $145K profit |
| Money Losers | Tables & Bookcases — negative profit |
| Peak Months | Sep, Nov, Dec — every year |
| Discount Risk | 40%+ discount = -$122K loss |
| Best Region | West — $107K profit |
| Top Customer | Tamara Chand — $8,400 profit |
<img width="1112" height="1039" alt="sales analytics full dashboard" src="https://github.com/user-attachments/assets/c10d8cc0-4241-4a38-a980-f11d21f2f1c3" />


### 💡 Business Recommendations
1. Discontinue Tables and Bookcases
2. Cap discounts at 20% maximum
3. Maximize marketing in Sep/Nov/Dec
4. Retain Consumer segment VIP customers

### 📁 Files
| File | Description |
|---|---|
| `sql/Project1_Complete_SQL.sql` | Full SQL script |
| `notebooks/sales_analysis.ipynb` | Python analysis |
| `powerbi/SALES_ANALYTICS.pbix` | Dashboard file |
| `screenshots/` | Dashboard previews |

---
*More projects coming soon...*
