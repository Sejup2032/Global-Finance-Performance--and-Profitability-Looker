# 📊 Global Finance Performance & Profitability Dashboard
## 📌 Overview

This project focuses on building an **interactive executive-level finance dashboard** using **Google Looker Studio** to monitor global sales, profitability, and cost performance.

The dashboard helps stakeholders quickly understand financial health and drill down into **country-level, time-based, and product-level insights** for better decision-making.

## 🎯 Objective
Provide a **single view of financial KPIs** (Sales, Profit, Cost)
Enable **drill-down analysis** across regions, time, and product categories
Improve **decision-making speed** with interactive filtering and visuals
## 🛠️ Tech Stack
- **Data Visualization**: Google Looker Studio
- **Data Source**: Excel / Google Sheets
- **Data Processing**: Calculated Fields, Aggregations, Filters
- **Design**: Dark-themed UI with consistent financial color scheme
## 🚀 Key Features
### 📈 Executive KPI Scorecards
- Display of key metrics like:
 - Total Sales
 - Total Profit
 - Unit Cost
- Provides a quick snapshot of overall business performance
### 🌍 Geographical Analysis
- Interactive map visualization
- Bubble size represents profitability
- Helps identify high-performing and low-performing regions
### 📅 Time-Series Analysis
- Monthly Sales vs Profit trends
- Quarterly Cost analysis
- Helps track business growth and seasonal patterns
### 🔍 Interactive Filtering
- Country-level dropdown filter
- Cross-filtering enabled (clicking visuals updates entire dashboard)
- Enables dynamic and focused analysis
### 🛍️ Product Performance Insights
- Treemap for product category distribution
- Donut chart for sales channels
- Helps understand revenue contribution across segments
## 🧩 Challenges & Solutions
### ⚠️ Data Volume & Aggregation Issue
- Problem:
Large volume of daily transaction data caused performance issues and system errors during time-based grouping.
- Solution:
Created calculated fields using MONTH() and QUARTER() functions
Adjusted chart granularity to enforce aggregation
Resulted in improved performance and smoother visualization

## 🎨 Dashboard Readability (UI/UX)
- Problem:
Too many labels and dense visuals made the dashboard cluttered and hard to read
- Solution:
- Removed unnecessary labels
- Used smooth line charts for better trend visualization
- Applied a consistent dark theme with high-contrast colors
- Improved overall clarity and user experience

## 📂 Dataset Details
The dataset includes the following fields:
- **Time**: Year, Quarter, Month (Order Date)
- **Geography**: Country, Region
- **Financial Metrics**: Sales, Profit, Cost, Unit Cost, Price
- **Product Info**: Category, Sub-category, Sales Channel
  
## 📸 Dashboard Preview
<img width="1382" height="750" alt="image" src="https://github.com/user-attachments/assets/f53b49a6-ac37-47da-bcf7-869d983288c1" />

🔗 Live Dashboard
👉 https://datastudio.google.com/s/pIWGgEc5sDo

## 💡 Key Learnings
- Handling large datasets efficiently in Looker Studio
- Designing interactive dashboards for business users
- Balancing performance with visualization quality
- Improving UI/UX for better storytelling with data
  
## 📌 How to Use
- Open the dashboard using the link above
- Use filters to select country or time period
- Click on charts to explore deeper insights
- Analyze trends and compare performance across regions
