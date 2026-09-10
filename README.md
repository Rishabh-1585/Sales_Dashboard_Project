# 📊 Sales & Profit Dashboard — Excel

An interactive **Sales & Profit Analytics Dashboard** built using Microsoft Excel to analyze sales performance, profitability, customers, products, states, and time-based trends.

The project follows a complete data analytics workflow:

**Raw Data → Data Cleaning → Data Preparation → PivotTables → PivotCharts → Dashboard → Interactive Analysis → Business Insights**

![Dashboard Preview](dashboard-preview.png)

---

## 🎯 Project Objective

The objective of this project is to transform raw transactional sales data into an interactive and easy-to-understand Excel dashboard that helps analyze business performance.

The dashboard answers important business questions such as:

* What is the total sales and profit?
* How does profit change year over year?
* Which categories and sub-categories generate the highest sales?
* Which customers contribute the most profit?
* Which states generate the highest sales?
* How does sales performance change month by month?
* How many customers are contributing in each year?
* Which areas need improvement?

---

# 🔄 Project Workflow

```text
Raw Sales Data
      ↓
Data Cleaning
      ↓
Data Preparation
      ↓
Helper Columns
      ↓
PivotTables
      ↓
PivotCharts
      ↓
Slicers & Filters
      ↓
Interactive Dashboard
      ↓
Business Insights
      ↓
Recommendations
```

---

# 📁 Project Structure

The workbook `Sales_Data.xlsx` contains three sheets:

| Sheet            | Description                                          |
| ---------------- | ---------------------------------------------------- |
| **Sales_Data**   | Raw transactional dataset and single source of truth |
| **Pivot Tables** | PivotTables used for analysis and dashboard visuals  |
| **Dashboard**    | Interactive, presentation-ready dashboard            |

---

# 🗂️ Data Fields

The `Sales_Data` sheet contains the following fields:

| Field                       | Description                                |
| --------------------------- | ------------------------------------------ |
| `Order Date` / `Order_Date` | Transaction date                           |
| `Customer Name`             | Name of the customer                       |
| `Salesman Name`             | Sales representative who handled the order |
| `State`                     | Indian state where the order originated    |
| `Category`                  | Product category                           |
| `Sub-Category`              | Product type                               |
| `Sales`                     | Total sales value in ₹                     |
| `Quantity`                  | Number of units sold                       |
| `Profit`                    | Profit earned in ₹                         |
| `Month`                     | Order month                                |
| `Year`                      | Order year                                 |

### Product Categories

The dataset contains categories such as:

* Electronics
* Furniture
* Office Supplies

### Example Sub-Categories

* Printer
* Chair
* Bookcase
* Binder
* Table
* Laptop
* Pen
* Paper
* Mobile

---

# 🧹 Step 1 — Data Cleaning

Before creating the dashboard, the raw transactional data was checked and prepared for analysis.

### Data cleaning activities included:

* Checking duplicate records
* Checking missing values
* Standardizing state names
* Checking customer names
* Validating date formats
* Ensuring Sales and Profit were numeric
* Checking Quantity values
* Removing unnecessary inconsistencies
* Maintaining consistent category and sub-category names

The cleaned dataset was then used as the source for all further analysis.

---

# 🛠️ Step 2 — Data Preparation

After cleaning the data, the dataset was converted into a structured Excel Table.

The table contains all transactional records and acts as the **single source of truth** for the dashboard.

Additional fields such as:

* Month
* Year

were used to perform time-based analysis.

---

# 📊 Step 3 — PivotTable Analysis

PivotTables were created to summarize the transactional dataset and generate the metrics required for the dashboard.

### Main PivotTable analyses:

### 1. Profit by Year

Analyzes profit performance across different years and product categories.

**Purpose:**

To compare yearly profitability and identify changes in category performance.

---

### 2. Sales by Sub-Category

Ranks product sub-categories according to their total sales.

**Purpose:**

To identify the highest and lowest-performing products.

---

### 3. Top 5 Customers by Profit

Identifies customers generating the highest profit.

**Purpose:**

To understand which customers contribute significantly to business profitability.

---

### 4. Sales by Month

Analyzes sales performance across different months.

**Purpose:**

To identify seasonal patterns and changes in monthly sales.

---

### 5. Customer Count by Year

Compares customer volume across 2025 and 2026.

**Purpose:**

To understand yearly customer participation and growth.

---

### 6. Sales by State

Analyzes total sales generated from different Indian states.

**Purpose:**

To identify high-performing geographical regions.

---

# 📈 Step 4 — Dashboard Development

After creating the required PivotTables, the results were converted into visualizations and arranged into an interactive dashboard.

The dashboard was designed to provide a **360° view of sales and profitability performance**.

---

# 📌 Dashboard Components

## 💰 KPI Cards

The dashboard contains high-level KPI cards for:

* **Total Sales**
* **Total Profit**

These KPIs provide an immediate overview of business performance.

---

## 📊 Profit by Year

A grouped bar chart was created to compare profit across product categories and years.

**Business purpose:**

Helps identify which categories are generating higher profits and how profitability changes between years.

---

## 📦 Category / Sub-Category Sales

A bar chart ranks sales across product sub-categories.

Example:

```text
Printer
Chair
Bookcase
Binder
Table
Laptop
Pen
Paper
Mobile
```

**Business purpose:**

Helps identify high-demand products and areas with lower sales performance.

---

## 👥 Top 5 Customer Profit

A horizontal bar chart displays the five customers contributing the highest profit.

**Business purpose:**

Helps identify valuable customers and understand customer-level profitability.

---

## 📅 Monthly Sales Trend

A monthly sales chart shows how sales change throughout the year.

**Business purpose:**

Helps identify seasonal trends, growth periods, and declining sales periods.

---

## 🍩 Customer Count by Year

A donut chart compares customer count between:

* 2025
* 2026

**Business purpose:**

Provides a quick visual comparison of customer volume between years.

---

## 🗺️ Sales by State

A geographic map visualization displays sales distribution across Indian states.

**Business purpose:**

Helps identify high-performing and low-performing geographical markets.

---

# 🎛️ Step 5 — Interactive Slicers

Slicers were added to make the dashboard interactive.

### Available Filters

* **Category**

  * Electronics
  * Furniture
  * Office Supplies

* **Year**

  * 2025
  * 2026

* **Month**

  * January
  * February
  * March
  * April
  * May
  * June
  * July
  * August
  * September
  * October
  * November
  * December

When a slicer is selected, the connected PivotTables and charts update dynamically.

This allows users to analyze the business from different perspectives without manually changing the underlying data.

---

# 🎨 Step 6 — Dashboard Design

The dashboard was designed with a focus on:

* Simple layout
* Clear KPI presentation
* Consistent formatting
* Easy navigation
* Interactive filtering
* Visual storytelling
* Business-focused charts

The objective was to make complex transactional data understandable at a glance.

---

# 💡 Key Insights

Based on the current analysis, some major observations include:

* **Printer, Chair, and Bookcase** are among the top-performing sub-categories by sales.
* **Priya Singh** is one of the highest-contributing customers by profit.
* Sales show a noticeable seasonal pattern, with a decline from April onward.
* **Rajasthan and Maharashtra** are among the stronger-performing states by sales.
* Product categories show different profitability patterns across years.
* Customer contribution varies across different periods.

> **Note:** These observations are based on the current dataset and dashboard analysis.

---

# 📌 Business Recommendations

Based on the dashboard analysis, the following actions can be considered:

### 1. Focus on High-Performing Products

Increase inventory and promotional activities for products with consistently high sales.

### 2. Improve Low-Performing Products

Analyze products with low sales and evaluate pricing, demand, and promotional strategies.

### 3. Strengthen High-Value Customer Relationships

Create loyalty programs and targeted offers for customers contributing significant profit.

### 4. Regional Expansion

Focus marketing and sales efforts on high-performing states while identifying opportunities in weaker regions.

### 5. Seasonal Planning

Use monthly sales trends to improve inventory planning and promotional campaigns during low-sales periods.

---

# 🛠️ Tools & Technologies

* **Microsoft Excel**
* Excel Tables
* Excel Formulas
* PivotTables
* PivotCharts
* Slicers
* Map Charts
* Donut Charts
* Bar Charts
* Data Cleaning
* Data Analysis
* Dashboard Design
* Business Intelligence

---

# 🚀 How to Use

### Step 1

Download the `Sales_Data.xlsx` workbook.

### Step 2

Open the file using Microsoft Excel.

### Step 3

Navigate to the **Dashboard** sheet.

### Step 4

Use the available slicers:

```text
Category
Year
Month
```

### Step 5

Select different combinations of filters to dynamically explore:

* Sales
* Profit
* Customers
* Products
* States
* Monthly trends

---

# 📂 Repository Structure

```text
Sales-Analytics-Dashboard/
│
├── Sales_Data.xlsx
├── dashboard-preview.png
└── README.md
```

---

# 📈 Project Outcome

This project demonstrates the ability to convert raw transactional data into a meaningful business intelligence solution using Excel.

The project covers the complete analytics workflow:

```text
Data Collection
       ↓
Data Cleaning
       ↓
Data Preparation
       ↓
Data Analysis
       ↓
PivotTable Creation
       ↓
Data Visualization
       ↓
Interactive Dashboard
       ↓
Business Insights
       ↓
Recommendations
```

The final dashboard provides management with a quick and interactive way to monitor sales performance, profitability, customer contribution, product performance, and geographical sales distribution.

---

# 🎓 Skills Demonstrated

Through this project, the following Data Analyst skills were demonstrated:

* Data Cleaning
* Data Preparation
* Exploratory Data Analysis
* Excel PivotTables
* PivotCharts
* Interactive Dashboard Development
* KPI Analysis
* Data Visualization
* Customer Analysis
* Product Analysis
* Time-Series Analysis
* Geographic Analysis
* Business Insights
* Data-Driven Recommendations

---

## ⭐ Project

If you found this project useful, consider giving the repository a ⭐ on GitHub.
