# Python-Analytics
# E-Commerce Sales Analysis

A  data analysis project on global e-commerce sales using Python (pandas · numpy · matplotlib).

---

---

## 🛠️ Tools

- **Python** · pandas · numpy · matplotlib
- **Jupyter Notebook** (VS Code)

---

## 📌 Steps

**1. Load Data**
Read the Excel file with pandas.

**2. Inspect**
Check shape, columns, data types, and summary stats.

**3. Clean Column Names**
Lowercase + underscores (e.g. `Order Date` → `order_date`).

**4. Fix Data Types**
Convert dates to `datetime` and text columns to `category`.

**5. Check Quality**
Verify no nulls and no duplicates.

**6. Feature Engineering**
Add new columns:
- `year`, `month`, `quarter` — from order date
- `delivery_days` — ship date minus order date
- `profit_margin` — profit ÷ revenue × 100

**7. EDA — Pivot Tables**
Five pivots covering region, item type, sales channel, yearly trend, and top countries.

**8. Visualization**
Four clean charts:
1. Profit by Region
2. Profit by Item Type
3. Yearly Profit Trend by Region
4. Top 10 Countries by Profit

---

## 📊 Analysis

> Fill these in with the actual numbers from your notebook output.

**By Region**
- Sub-Saharan Africa leads in total profit
- Europe and Asia follow closely
- North America has the lowest contribution

**By Product**
- Office Supplies and Cosmetics generate the highest profit
- Beverages and Snacks have the lowest margins

**By Channel**
- Online and Offline sales are nearly even
- Delivery times are similar across both channels

**By Year**
- Profit fluctuates significantly year-over-year
- No single region dominates every year
- 2012 was the strongest year overall

**By Country**
- A few countries account for most of the profit
- Top performers come from multiple regions, not just one

---

## ✅ Recommendations

**1. Focus on top regions**
Allocate more marketing budget to Sub-Saharan Africa and Europe — they drive the most profit.

**2. Push high-margin products**
Promote Office Supplies and Cosmetics. Reduce investment in low-margin categories like Beverages.

**3. Strengthen weaker regions**
Investigate why North America underperforms — possibly pricing, competition, or logistics.

**4. Maintain channel balance**
Online and Offline both perform well. Keep investing in both, no need to favor one.

**5. Track yearly performance**
Yearly profit is volatile. Set up monthly or quarterly tracking to catch trends earlier.

**6. Improve delivery speed**
Review regions with longer delivery times — faster shipping can improve customer satisfaction and repeat orders.

