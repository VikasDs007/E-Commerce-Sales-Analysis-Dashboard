# 🛒 E-Commerce Sales Analysis Dashboard

> **A Power BI analytics dashboard that 
> transforms 5,000 rows of Indian e-commerce 
> transactions into actionable insights on 
> regional performance, discount impact, and 
> category profitability — helping businesses 
> stop margin erosion and double down on 
> what actually works.**

[![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=flat-square&logo=powerbi)](https://powerbi.microsoft.com)
[![Excel](https://img.shields.io/badge/Excel-Data%20Processing-green?style=flat-square&logo=microsoftexcel)](https://microsoft.com/excel)
[![Dataset](https://img.shields.io/badge/Dataset-5%2C000%20rows-blue?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)]()

---

## 🎯 The Business Problem

An Indian e-commerce business was flying 
blind on three critical questions:

> *"Which regions and categories are actually 
> making us money — and which are quietly 
> destroying our margins through discounting?"*

Without a unified view of sales, profit, 
and discount impact across regions and 
categories, inventory and marketing decisions 
were being made on gut feel rather than data.

This dashboard changes that.

---

## 📈 Key Results

| Metric | Finding |
|--------|---------|
| Dataset | 5,000 orders · 15 columns · 2024–2025 |
| Highest margin region | South (led by Bangalore) |
| Margin killer | Discounts above 20% |
| Highest AOV categories | Books + Kitchen Appliances |
| Highest volume, lowest profit | Groceries |
| Dominant payment method | UPI + Debit Card (mobile-first) |

---

## 💡 Business Insights That Drive Decisions

**1. South region is your profit engine — 
invest here first:**
Bangalore and the South region consistently 
delivered the highest profit margins across 
all categories. Upsell campaigns and premium 
inventory should be prioritized here before 
expanding to lower-margin regions.

**2. Discounts above 20% are a margin trap:**
Orders with discounts exceeding 20% showed 
significantly compressed margins — especially 
in Groceries. The data makes a clear case for 
capping promotional discounts on low-margin 
categories. Every rupee of discount above 20% 
costs more in margin than it recovers in volume.

**3. Books and Kitchen have the highest 
revenue potential per order:**
These categories drive the highest average 
order value (AOV). Marketing spend should 
concentrate here for maximum revenue per 
acquisition — not on Groceries which drives 
volume but kills profit per unit.

**4. Mobile-first payment behavior signals 
where to spend ad budget:**
UPI and Debit Card dominate transactions — 
this is a mobile-first customer base. Digital 
ad spend on mobile platforms will outperform 
desktop or traditional channels for this 
audience.

---

## 🖼️ Dashboard

![E-Commerce Sales Dashboard](E-commerce%20Sale%20Analysis%20Dashboard.png)

> Full interactive dashboard with drill-through 
> by region, category, and time period 
> available in the `.pbix` file below.

---

## 🔍 Analytics Methodology

```
Raw CSV (5,000 rows)
	↓
Data Cleaning
(date standardization, sales/profit 
validation, discount normalization)
	↓
Exploratory Data Analysis
(regional trends, category performance,
discount impact analysis)
	↓
DAX Measures
(Profit Margin %, AOV, Discount Rate,
YoY Growth, Category Contribution %)
	↓
Power BI Dashboard
(KPI cards, regional maps, trend lines,
category drill-through)
```

**Key DAX Measures Built:**

| Measure | Business Use |
|---------|-------------|
| Profit Margin % | Identify margin erosion by category |
| Average Order Value | Prioritize high-value categories |
| Discount Rate | Flag over-discounted products |
| Regional Profit Rank | Focus investment decisions |
| Category Contribution % | Budget allocation |

---

## 💻 How to Run

```bash
# Clone the repo
git clone https://github.com/VikasDs007/E-Commerce-Sales-Analysis-Dashboard.git
```

**Power BI Setup:**
1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Open `E-Commerce Sales Analysis Dashboard.pbix`
3. CSV `Ecommerce_Sales_Data_2024_2025.csv` 
   is pre-linked — hit Refresh to reload data

---

## 🗂️ Project Structure

```
E-Commerce-Sales-Analysis-Dashboard/
│
├── E-Commerce Sales Analysis Dashboard.pbix
├── Ecommerce_Sales_Data_2024_2025.csv
├── E-commerce Sale Analysis Dashboard.png
└── README.md
```

---

## 🔮 Future Enhancements

- [ ] **Python EDA layer** — add Jupyter 
	  notebook with Pandas + Seaborn analysis 
	  showing statistical significance of 
	  discount impact on margins
- [ ] **Predictive reorder model** — ML model 
	  to predict which SKUs need restocking 
	  based on sales velocity and seasonality
- [ ] **Customer segmentation** — RFM analysis 
	  (Recency, Frequency, Monetary) to 
	  identify high-value customer segments
- [ ] **LLM Q&A layer** — "Which category 
	  should we run promotions on next month?" 
	  answered by AI using sales data context

---

## 🧠 Skills Demonstrated

| Category | Skills |
|----------|--------|
| Business Intelligence | Power BI, DAX measures, KPI dashboards |
| Data Analysis | EDA, trend analysis, discount impact modeling |
| Business Communication | Translating sales data into pricing and marketing decisions |
| Domain Knowledge | E-commerce metrics, retail analytics, margin optimization |

---

## 👤 Author

**Vikas Chaurasia** — Data Analyst |
AI-Powered Analytics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vikasds007-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/vikasds007)
[![GitHub](https://img.shields.io/badge/GitHub-VikasDs007-black?style=flat-square&logo=github)](https://github.com/VikasDs007)
[![Portfolio](https://img.shields.io/badge/Portfolio-vikasds007.github.io-orange?style=flat-square)](https://vikasds007.github.io)

---

*If this project was useful, a ⭐ means a lot!*

