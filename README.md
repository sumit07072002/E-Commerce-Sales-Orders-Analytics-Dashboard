# E-Commerce-Sales-Orders-Analytics-Dashboard

# 📊 E-Commerce Sales & Orders Analytics Dashboard

An interactive **E-Commerce Sales & Orders Analytics Dashboard** built using **Microsoft Power BI** to analyze sales performance, profitability, order volume, and product-level business performance.

The project focuses on transforming raw e-commerce sales data into meaningful business insights through **data cleaning, data modeling, DAX measures, KPI development, and interactive data visualization**.

---

## 🎯 Project Objective

The primary objective of this project is to analyze e-commerce sales data and build an interactive dashboard that helps answer key business questions such as:

* What is the overall sales performance?
* How much profit/loss is being generated?
* How many products/orders have been sold?
* Which products or categories contribute the most to sales?
* How does sales performance change over time?
* Which areas/products require further attention?
* What are the major trends and patterns in the business?

The dashboard is designed to provide a consolidated view of business performance and support data-driven decision-making.

---

## 🛠️ Tools & Technologies

| Tool                   | Purpose                                         |
| ---------------------- | ----------------------------------------------- |
| **Microsoft Power BI** | Dashboard development and data visualization    |
| **Power Query**        | Data cleaning and transformation                |
| **DAX**                | KPI calculations and analytical measures        |
| **Excel / CSV**        | Source data and initial data exploration        |
| **Data Modeling**      | Building relationships and analytical structure |

---

## 📌 Key KPIs

The dashboard includes important business performance indicators such as:

* **Total Sales**
* **Profit / Loss**
* **Total Quantity Sold**
* **Maximum Sales**
* Sales trends over time
* Product/category performance
* Additional performance metrics based on selected filters

The KPI cards provide a quick overview of the current business performance and dynamically respond to dashboard filters.

---

## 📈 Dashboard Features

### 1. Sales Performance Analysis

The dashboard provides an overview of overall sales performance and allows users to analyze changes in sales across different periods.

A time-based visualization is used to identify:

* Sales trends
* Growth or decline periods
* Seasonal patterns
* Changes in business performance over time

---

### 2. Profit & Loss Analysis

Profitability is analyzed to understand how sales translate into business returns.

The dashboard helps identify:

* Overall profit/loss
* Profitable and less-profitable areas
* Changes in profitability
* Products/categories contributing to profitability

---

### 3. Quantity Analysis

The dashboard tracks the total quantity of products sold and enables users to compare sales volume across different dimensions.

This helps understand whether high sales are driven by:

* Higher order volume
* Higher quantity sold
* Specific products/categories

---

### 4. Product / Category Performance

The dashboard allows product-level and category-level analysis to identify differences in performance.

Users can investigate:

* High-performing products
* Low-performing products
* Sales contribution
* Quantity contribution
* Profitability

---

### 5. Interactive Analysis

Power BI slicers and filters allow users to dynamically explore the dataset.

When a filter is applied, the KPI cards and visualizations update accordingly, making it possible to perform detailed analysis without creating separate reports for each segment.

---

## 🧮 DAX Measures

Several DAX measures were created to calculate dynamic business KPIs.

Example:

```DAX
Total Sales =
SUM(Sales[Sales])
```

```DAX
Total Quantity =
SUM(Sales[Quantity])
```

```DAX
Profit / Loss =
SUM(Sales[Profit])
```

Additional measures were created according to the analytical requirements of the dashboard.

Using **measures instead of static calculations** allows the KPIs to respond dynamically to slicers, filters, and other report interactions.

---

## 🔄 Data Analysis Workflow

The project follows an end-to-end analytics workflow:

```text
Raw Data
    ↓
Data Cleaning
    ↓
Data Transformation
    ↓
Data Modeling
    ↓
DAX Measures
    ↓
Dashboard Development
    ↓
Business Insights
```

### Data Preparation

The raw dataset was prepared before building the dashboard.

Key data preparation activities included:

* Checking data types
* Handling inconsistent values
* Reviewing missing values
* Preparing fields for analysis
* Creating an appropriate analytical structure
* Ensuring data was suitable for Power BI visualization

---

## 📊 Dashboard Design

The dashboard was designed with a focus on:

* Clear KPI presentation
* Easy navigation
* Interactive filtering
* Trend analysis
* Product/category comparison
* Business-focused visual storytelling

The use of KPI cards, charts, and interactive filters allows users to move from a high-level overview to detailed analysis.

---

## 💡 Business Insights

The dashboard can be used to identify patterns such as:

* Changes in sales performance over time
* Products/categories generating higher sales
* Areas with stronger or weaker profitability
* Differences between sales volume and quantity sold
* Periods showing significant changes in performance

These insights can help businesses evaluate sales performance and identify areas requiring further investigation.

---

## 📁 Project Structure

```text
E-Commerce-Sales-Orders-Analytics-Dashboard/
│
├── Dataset / Data Files
│
├── Power BI Dashboard
│
├── Dashboard Screenshots
│
└── README.md
```

---

## 🧠 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* Data Modeling
* Power Query
* DAX
* KPI Development
* Business Intelligence
* Data Visualization
* Dashboard Design
* Business-oriented Data Analysis
* Data Storytelling

---

## 📌 Project Highlights

**End-to-end Power BI project** covering:

> **Data → Cleaning → Transformation → Modeling → DAX → Visualization → Business Insights**

The project demonstrates how raw e-commerce data can be transformed into an interactive business intelligence dashboard for performance analysis.



---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
