# E-Commerce Sales Analysis Dashboard

## 📌 Business Problem

An Indian e-commerce business needed visibility into which regions, product categories, and time periods were driving revenue and profit — and which were eroding margins through excessive discounting — to make smarter inventory and marketing decisions.

## 📊 Data Source

- Dataset contained **5,000 rows** and **15 columns**.
- Key variables included: Order Date, Region, State, City, Category, Sub-Category, Quantity, Unit Price, Discount, Sales, Profit, Payment Mode.

## 🛠️ Tools & Methodology

- **Tools Used:** Power BI (data modeling, DAX measures, interactive dashboard), CSV (raw data source).
- **Methodology:**
  1. Data Cleaning & Preprocessing (standardizing date formats, validating sales/profit calculations).
  2. Exploratory Data Analysis (EDA) to identify regional trends, category performance, and discount impact.
  3. Dashboard Creation to visualize KPIs and enable drill-through by region, category, and time period.

## 💡 Key Business Insights

- **Regional Performance:** The South region (led by Bangalore) consistently delivered the highest profit margins, making it the priority market for upsell campaigns.
- **Discount Impact:** Orders with discounts above 20% showed significantly compressed profit margins, suggesting a need to cap promotional discounts on low-margin categories like Groceries.
- **Category Leaders:** Books and Kitchen appliances drove the highest average order value, while Groceries had the highest order volume but lowest profit per unit.
- **Payment Trends:** UPI and Debit Card dominated transactions, indicating a mobile-first customer base — relevant for targeting digital ad spend.

## 🖼️ Visualizations

![E-Commerce Sales Dashboard](E-commerce%20Sale%20Analysis%20Dashboard.png)

> Full interactive dashboard available in the `.pbix` file.

## 💻 How to Run This Project

1. Clone this repository:
   ```
   git clone https://github.com/VikasDs007/E-Commerce-Sales-Analysis-Dashboard.git
   ```
2. Open `E-Commerce Sales Analysis Dashboard.pbix` with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
3. The CSV file `Ecommerce_Sales_Data_2024_2025.csv` is already linked as the data source — refresh to reload if needed.

---

*Dataset is synthetic and created for portfolio/demonstration purposes.*
