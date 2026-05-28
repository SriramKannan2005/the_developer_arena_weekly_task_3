# 📊 Sales Data Analysis Report

**Dataset:** `sales_data.csv`  
**Records:** 100 transactions | **Period:** January – April 2024  
**Products:** Phone, Laptop, Tablet, Headphones, Monitor  
**Regions:** North, South, East, West  

---

## 1. Overall Performance

| Metric | Value |
|---|---|
| 💰 Total Revenue | ₹1,23,65,048 |
| 🛒 Total Orders | 100 |
| 📦 Total Units Sold | 478 |
| 📈 Average Order Value | ₹1,23,650 |

---

## 2. Product Performance (Best → Worst)

| Rank | Product | Revenue | Units Sold | Revenue Share |
|---|---|---|---|---|
| 🥇 1 | Laptop | ₹38,89,210 | 136 | 31.5% |
| 🥈 2 | Tablet | ₹28,84,340 | 127 | 23.3% |
| 🥉 3 | Phone | ₹28,59,394 | 101 | 23.1% |
| 4 | Headphones | ₹13,84,033 | 48 | 11.2% |
| 5 | Monitor | ₹13,48,071 | 66 | 10.9% |

**🏆 Best-Selling Product:** **Laptop** — leads in both revenue (₹38.9L) and units sold (136 units).

---

## 3. Regional Performance

| Rank | Region | Revenue | Orders | Revenue Share |
|---|---|---|---|---|
| 🥇 1 | North | ₹39,83,635 | — | 32.2% |
| 🥈 2 | South | ₹37,37,852 | — | 30.2% |
| 🥉 3 | East | ₹25,19,639 | — | 20.4% |
| 4 | West | ₹21,23,922 | — | 17.2% |

**📍 Top Region:** North leads with ₹39.8L (32.2% of total revenue).  
North + South together account for **62.4%** of all revenue.

---

## 4. Monthly Revenue Trend

| Month | Revenue |
|---|---|
| January 2024 | ₹41,20,524 |
| February 2024 | ₹26,56,050 |
| March 2024 | ₹44,85,006 |
| April 2024 | ₹11,03,468 |

> **Note:** April shows a sharp dip — likely because the dataset captures only partial April data.  
> March was the strongest month at ₹44.9L.

---

## 5. Top 5 Customers

| Rank | Customer ID | Revenue |
|---|---|---|
| 1 | CUST016 | ₹3,73,932 |
| 2 | CUST007 | ₹3,63,870 |
| 3 | CUST083 | ₹3,50,888 |
| 4 | CUST073 | ₹3,49,510 |
| 5 | CUST020 | ₹3,33,992 |

Top 5 customers collectively contribute **₹17.7L** (~14.4% of total revenue).

---

## 6. Key Insights & Recommendations

### ✅ Strengths
- **Laptop dominates** with 31.5% revenue share — strong product-market fit.
- **North & South regions** are growth engines, contributing 62% of total revenue.
- **Consistent high performers:** Top 5 customers are reliable revenue anchors.

### ⚠️ Opportunities
- **Headphones & Monitor** underperform in revenue despite reasonable unit counts — consider pricing review or bundled offers.
- **East & West regions** have significant room to grow (only 37.6% combined share) — targeted campaigns recommended.
- **February dip** warrants attention — seasonal promotions could smooth revenue across months.

### 💡 Recommendations
1. Double down on **Laptop + Tablet** (54.8% combined share) with upsell opportunities.
2. Run **regional promotions** in East and West to balance geographic revenue distribution.
3. Implement a **loyalty program** for top customers (CUST016, CUST007) to retain high-value accounts.
4. Investigate the **February slowdown** and plan targeted campaigns to prevent recurrence.

---

## 7. Data Quality Notes

| Check | Result |
|---|---|
| Missing Values | ✅ None |
| Duplicate Rows | ✅ None |
| Date Range | 2024-01-01 to 2024-04-30 |
| Data Types | All columns correctly typed after Date conversion |

---

*Report generated from `sales_data.csv` — 100 transactions across 5 products, 4 regions, Q1–Q2 2024.*
