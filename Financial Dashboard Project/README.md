# 📊 Financial Performance Dashboard | Power BI

## 📌 Problem Statement

Organizations today operate in complex and highly competitive environments, making it essential to understand financial performance with clarity and precision. However, most businesses struggle with:

- Lack of a unified view of sales, profit, COGS, and other financial KPIs
- Difficulty identifying which products, segments, and countries drive profitability
- Poor visibility into discount impact and product-level margin leakage
- Limited awareness of trends in sales, cost fluctuations, and profit changes
- Inability to analyze seasonality or compare performance across different years
- No interactive scenario planning to forecast the effect of margin changes
- Absence of actionable insights for pricing, product strategy, and operational efficiency

This project solves these challenges by delivering a Financial Performance Dashboard that integrates analytics with data storytelling, enabling smarter, faster, and more strategic decision-making.

## 🎯 Objective

Build a multi-page Power BI dashboard that:

- Presents an executive-level financial overview
- Performs product- and segment-level profitability analysis
- Identifies high and low-margin products
- Highlights country-level financial performance
- Shows month-by-month and year-over-year financial trends
- Enables profit forecasting using a What-If Simulation
- Provides actionable recommendations for business improvement

## 📊 Dashboard Overview

<p align="center">
  <img src="https://raw.githubusercontent.com/MuzammilAhmed14/PowerBI-Projects/main/Financial%20Dashboard%20Project/Images/Performance%20Overview%20page.JPG" alt="Financial Dashboard" width="800">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/MuzammilAhmed14/PowerBI-Projects/main/Financial%20Dashboard%20Project/Images/Product%20%26%20Segment%20page.JPG" alt="Product & Segment Page" width="800">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/MuzammilAhmed14/PowerBI-Projects/main/Financial%20Dashboard%20Project/Images/Strategic%20Insights%20page.JPG" alt="Strategic Insights Page" width="800">
</p>

**Key Metrics:**

- Total Sales
- Total Profit
- Total COGS
- Total Units Sold
- Profit Margin (%)
- Top Product by Profit
- Lowest Margin Product

> Values are fully dynamic and update with each slicer selection.

---

### 📈 Page 1 — Executive Financial Overview

**Purpose:** “What is happening in the business?”

**Highlights:**

- KPI summary of Sales, Profit, Units Sold, and COGS
- Sales & Profit Trend across months
- Sales distribution by Segment
- Regional performance (Country-wise Sales & Profit)
- Product performance snapshot
- Insight textbox to summarize key observations

> Gives leadership a complete top-level view of business performance and financial health.

---

### 📊 Page 2 — Product & Segment Profitability

**Purpose:** “Why is it happening?”

**Key Visuals:**

- Sales vs Profit by Product
- Profit Margin % by Product
- Units Sold by Product
- Discount Impact by Product
- Product × Country Profitability Heatmap

**KPI Tiles:**

- Top Product by Profit
- Average Profit Margin
- Lowest Margin Product

> Helps uncover which products generate strong margins, which are draining profitability, and how segments and markets contribute to overall performance.

---

### 📉 Page 3 — Strategic Insights & Recommendations

**Purpose:** “What should we do next?”

**Key Visuals:**

- Profit Trend (YOY comparison)
- Country-level Profit Margin
- Profit Contribution by Country
- COGS vs Sales Trend
- Discount Trend

**What-If Simulation:**

- Simulated Profit
- Profit Increase Amount
- Profit Increase %

**Recommendations:**

- Guides decisions related to pricing, product focus, expansion, and cost management.

---

## 🧩 DAX Calculations

All DAX formulas for:

- Core KPIs
- Profitability metrics
- Time intelligence
- What-If simulation
- Margin calculations

> Are included in a separate file: `Financial_DAX_Measures.txt`

---

## 💡 Key Insights

- A few products dominate profit, highlighting a concentration risk
- Low-margin products negatively impact total profitability
- France and Germany are high-profit regions
- Mexico underperforms consistently
- Significant discount usage reduces margin for specific products
- Clear seasonality observed across months
- Small increases in margin significantly impact profit (via what-if model)
- COGS variability causes swings in monthly profitability
- Product mix optimization can greatly improve financial results
- Strategic pricing adjustments needed for low-margin products

---

## 🛠️ Technical Implementation

**Tools Used:**

- Power BI Desktop
- Power Query
- DAX
- Excel dataset

**Core Functionalities:**

- Multi-page interactive dashboard
- Financial KPI cards
- Product & segment insights
- Country-level profitability analysis
- Trend analysis
- What-If scenario modeling
- Insight and recommendation sections

**Data Model Includes:**

- Fact table (Sales, Profit, COGS, Discounts)
- Product dimension
- Country dimension
- Segment dimension
- Date table

---

## 🧠 What I Learned

### 🧩 Technical Skills

- Power BI visualization best practices
- Advanced DAX calculations
- Time intelligence (YTD, YOY)
- Data modeling & relationship design
- Building What-If analysis
- Power Query transformations

### 💼 Business Intelligence

- Profit & margin diagnostics
- Root-cause analysis of poor-performing products
- Understanding discounting impact
- Country and segment performance analysis
- Translating data into business actions

### 📊 Data Analytics

- Financial trend interpretation
- Profitability segmentation
- Cost and margin variability analysis
- Scenario planning with DAX

---

## 📈 Business Impact & Recommendations

**Immediate Actions:**

- Reduce discounting for low-margin products
- Optimize pricing for underperforming items
- Promote and bundle high-margin products
- Improve operational cost efficiency
- Focus on growth in top-performing regions

**Strategic Recommendations:**

- Implement monthly margin tracking
- Develop a dynamic pricing strategy
- Strengthen high-profit markets (France & Germany)
- Reduce cost fluctuations via supplier optimization
- Build product-level profitability scorecards

---

## 🎯 Use Cases

- **Finance Teams:** Cost, sales & margin optimization
- **Executives:** Strategic decision-making
- **Sales:** Product targeting & pricing strategy
- **Operations:** COGS monitoring
- **Marketing:** Promotion planning based on product profitability
- **Consultants:** Executive storytelling dashboards

---

## 👤 Author

**Sheikh Muzammil Ahmed**  
📊 Data Analyst | Business Intelligence Strategist | Power BI Storyteller

📫 Connect: [LinkedIn](https://www.linkedin.com/in/muzammil-ahmed-ap2000) 

---

## 🏷️ Tags

`#PowerBI #DataAnalytics #FinancialDashboard #Profitability #BusinessIntelligence #DataStorytelling #DAX #WhatIfAnalysis #SalesAnalytics`
