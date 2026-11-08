# 📊 Sales Analysis Dashboard – Power BI

## 📌 Project Overview

This project focuses on analyzing sales performance using **Microsoft Power BI**. The dashboard provides interactive visualizations and meaningful business insights to help stakeholders understand sales trends, revenue performance, product performance, and customer behavior.

The objective is to transform raw sales data into actionable insights through data cleaning, data modeling, DAX calculations, and interactive reporting.

## 🎯 Business Objectives

- Analyze overall sales and revenue performance.
- Identify top-performing products and categories.
- Understand monthly and yearly sales trends.
- Evaluate regional and customer-wise sales performance.
- Monitor profit and sales growth.
- Support data-driven business decisions.

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** – Data visualization and dashboard development.
- **Power Query** – Data cleaning and transformation.
- **DAX (Data Analysis Expressions)** – Measures and calculated columns.
- **Microsoft Excel / CSV** – Data source.
- **GitHub** – Project documentation and version control.

## 📈 Dashboard Features

### 1. Sales Overview
- Total Sales
- Total Profit
- Total Orders
- Average Order Value
- Sales Growth

### 2. Sales Trends
- Monthly sales performance.
- Year-over-year sales comparison.
- Revenue trends over time.

### 3. Product Analysis
- Top-selling products.
- Sales by product category.
- Profitability by product.

### 4. Regional Analysis
- Sales by geographical region.
- Regional revenue comparison.
- Identification of high-performing regions.

### 5. Customer Analysis
- Top customers by revenue.
- Customer purchasing patterns.
- Customer contribution to overall sales.

## 🔍 Data Analysis Process

1. **Data Collection:** Import sales data from CSV or Excel.
2. **Data Cleaning:** Handle missing values, duplicates, and incorrect data types using Power Query.
3. **Data Transformation:** Prepare and structure the dataset.
4. **Data Modeling:** Establish relationships between relevant tables.
5. **DAX Calculations:** Create measures for sales, profit, orders, and growth.
6. **Visualization:** Develop interactive dashboards using Power BI.
7. **Insights:** Identify business trends and provide actionable recommendations.

## 📊 Key DAX Measures

```dax
Total Sales =
SUM(Sales[SalesAmount])

Total Profit =
SUM(Sales[Profit])

Total Orders =
DISTINCTCOUNT(Sales[OrderID])

Average Order Value =
DIVIDE(
    [Total Sales],
    [Total Orders],
    0
)
```

## 📸 Dashboard Preview

Add your Power BI dashboard screenshot here.

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `Power_BI_Visuals_Practice.Answers.pbix` file using Power BI Desktop.
3. Update the dataset connection if required.
4. Refresh the data.
5. Explore the interactive dashboard using filters and slicers.

## 💡 Business Insights

The dashboard can help answer questions such as:

- Which products generate the highest revenue?
- Which region contributes the most to sales?
- How does sales performance change month over month?
- Which customers contribute the most revenue?
- Which product categories generate the highest profit?

## 👨‍💻 Author

**Shahada Parveen**

Data Analytics | Power BI 

---

⭐ If you find this project useful, feel free to star the repository!
