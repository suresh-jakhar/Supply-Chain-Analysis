# 📦 Supply Chain Analysis using Python

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)](https://jupyter.org/)


A hands-on data analysis project to explore supply chain, We dive into product pricing, revenue patterns, and product categories, and use interactive visualizations to extract actionable insights.



## 🛠 Techniques & Tools Used

This project dives into supply chain data to uncover trends, performance insights, and operational gaps. Below is a summary of the techniques and libraries used throughout the analysis.

### 📋 Data Preparation
- Imported and explored data using **pandas**
- Handled missing values using `dropna` for critical analysis columns
- Created pivot tables for aggregated views

### 📊 Visualization (Interactive)
Used **Plotly Express** and **Plotly Graph Objects** for all visualizations:
- **Scatter Plot** of Price vs Revenue with custom manual trendline using `numpy.polyfit`
- **Pie Charts** for:
  - Sales by Product Type
  - Cost distribution by Transportation Mode
  - Defect rate distribution by Transportation Mode
- **Bar Charts** for:
  - Revenue by Shipping Carrier
  - Order Quantity by SKU
  - Defect Rates by Product Type
- **Line Charts** for:
  - Revenue by SKU
  - Stock Levels by SKU

### 🧮 Statistical & Manual Analysis
- Used `numpy.polyfit` to create a **manual trendline** for price vs revenue analysis
- Aggregated performance metrics like:
  - Total Revenue per shipping carrier
  - Average lead times and manufacturing costs by product type
  - Average defect rates by product and transportation mode

### 📦 Supply Chain Focus Areas
- Product-level and SKU-level revenue insights
- Order volume and stock level trends
- Shipping cost comparisons
- Manufacturing cost and lead time efficiency
- Defect rate analysis by both product and transport method

### 📚 Libraries Used
- `pandas` – data manipulation
- `numpy` – trendline fitting
- `plotly.express` and `plotly.graph_objects` – visualizations
- `plotly.io` – template styling






: Suresh Jakhar 
