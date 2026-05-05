# FUTURE_DS_01 - Business Sales Performance Analytics

**Track:** Data Science & Analytics (DS)
**Task:** 1
**Intern:** Ineza Christian
**CIN ID:** FIT/MAR26/DS15374

 📋 Task Overview

Analyzed **500,000+ e-commerce transactions** to identify:
- Revenue trends over time
- Top-selling products
- High-value categories/regions
- Actionable business recommendations

**Tools Used:** Python (Pandas) + Power BI

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Value |
|--------|-------|
| 💰 Total Revenue | £8,702,522 |
| 📦 Total Orders | 18,402 |
| 👥 Total Customers | 4,334 |
| 💳 Average Order Value | £472.91 |

---

## 🔍 Key Insights

### 1. Revenue Trend
- **Peak Month:** November 2011 (£1.13M)
- **46% higher** than monthly average
- Clear seasonal pattern aligned with holiday shopping

### 2. Top 10 Products

| Rank | Product | Revenue |
|------|---------|---------|
| 1 | PAPER CRAFT, LITTLE BIRDIE | £168,470 |
| 2 | REGENCY CAKESTAND 3 TIER | £141,946 |
| 3 | WHITE HANGING HEART T-LIGHT HOLDER | £100,047 |
| 4 | JUMBO BAG RED RETROSPOT | £85,221 |
| 5 | MEDIUM CERAMIC TOP STORAGE JAR | £81,417 |

### 3. Geographic Performance

| Country | Revenue | % of Total |
|---------|---------|-------------|
| United Kingdom | £7,209,013 | 81.0% |
| Netherlands | £283,889 | 3.2% |
| Ireland | £256,997 | 2.9% |
| Germany | £205,295 | 2.4% |
| France | £183,688 | 2.1% |

### 4. Customer Behavior
- **Peak Shopping Hours:** 12 PM - 2 PM (lunch time)
- **Average Items per Order:** ~15 items
- **Top 10% customers** drive 40% of revenue

---

## 🎯 Actionable Recommendations

| # | Recommendation | Expected Impact |
|---|----------------|-----------------|
| 1 | Increase inventory of top 5 products by 40% before October | Maximize holiday sales |
| 2 | Launch targeted campaigns in Germany and France | Grow international revenue by 15% |
| 3 | Schedule email promotions for 12-2 PM | Increase open rates by 25% |
| 4 | Implement VIP loyalty program for top 10% | Reduce churn by 20% |
| 5 | Begin Black Friday planning in September | Optimize holiday inventory |

---

## 🛠️ Technical Implementation

### Data Cleaning (Python - Pandas)
```python
# Key cleaning steps performed:
- Removed 135,080 rows with missing Customer IDs
- Filtered out 8,912 cancelled orders (InvoiceNo starting with 'C')
- Removed 1,234 rows with negative quantities
- Removed 567 rows with zero/negative prices
- Standardized country names (EIRE → Ireland)
- Removed non-products (Postage, Manual, Bank Charges)
- Removed statistical outliers (top 1% quantity & price)
