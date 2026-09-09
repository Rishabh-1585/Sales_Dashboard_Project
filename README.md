# 📊 Sales & Profit Dashboard (Excel)

An interactive Excel dashboard built to analyze sales and profit performance across categories, states, customers, and time periods. The workbook combines raw transactional data, PivotTables, and a fully interactive dashboard with slicers for dynamic filtering.

![Dashboard Preview](dashboard-preview.png)

## 📁 Project Structure

The workbook (`Sales_Data.xlsx`) contains three sheets:

| Sheet | Description |
|---|---|
| **Sales_Data** | Raw transactional dataset — the single source of truth for all analysis |
| **Pivot Tables** | PivotTables powering the dashboard visuals and KPIs |
| **Dashboard** | Interactive, presentation-ready dashboard view |

## 🗂️ Data Fields

The `Sales_Data` sheet contains the following columns:

- `Order Date` / `Order_Date` — transaction date
- `Customer Name` — name of the customer
- `Salesman Name` — sales representative who handled the order
- `State` — Indian state where the order originated
- `Category` — product category (Electronics, Furniture, Office Supplies)
- `Sub-Category` — product type (Printer, Chair, Bookcase, Binder, Table, Laptop, Pen, Paper, Mobile, etc.)
- `Sales` — total sale value (₹)
- `Quantity` — units sold
- `Profit` — profit earned (₹)
- `Month` — order month
- `Year` — order year (2025, 2026)

## 📈 Dashboard Highlights

The dashboard provides a 360° view of sales performance with the following components:

- **KPI Cards** — Total Sales and Total Profit at a glance
- **Profit by Year** — grouped bar chart comparing profit across categories, split by year
- **Category Sales** — bar chart ranking sales across product sub-categories (Printer, Chair, Bookcase, Binder, Table, Laptop, Pen, Paper, Mobile)
- **Top 5 Customer Profit** — horizontal bar chart of the most profitable customers
- **Sales by Month** — seasonal sales trend across the calendar year
- **Customer Count by Year** — donut chart comparing customer volume between 2025 and 2026
- **Sales by State** — map visualization of sales distribution across Indian states

### 🎛️ Interactive Filters (Slicers)
- **Category** — Electronics, Furniture, Office Supplies
- **Year** — 2025, 2026
- **Month** — January through December

All visuals update dynamically based on the selected slicer combination.

## 🛠️ Tools & Techniques Used

- Microsoft Excel PivotTables & PivotCharts
- Slicers for interactive filtering
- Map Chart (geographic visualization by state)
- Donut & bar charts for KPI storytelling
- Dashboard layout design with KPI cards and icons

## 🚀 How to Use

1. Download `Sales_Data.xlsx`
2. Open it in Microsoft Excel (2016 or later recommended for Map Charts)
3. Go to the **Dashboard** tab
4. Use the **Category**, **Year**, and **Month** slicers to filter and explore insights interactively

## 💡 Key Insights (Sample)

- Printer, Chair, and Bookcase are the top-performing sub-categories by sales
- Priya Singh is the top contributing customer by profit
- Sales show a distinct seasonal decline from April onward, dipping through mid-year
- Rajasthan and Maharashtra are among the highest-performing states by sales

## 📌 Notes

- All monetary values are in Indian Rupees (₹)
- Data covers fiscal years 2025 and 2026

---

⭐ If you found this dashboard useful, consider starring the repo!

