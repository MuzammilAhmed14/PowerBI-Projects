# Sales Dashboard - RFM Analysis | Power BI

## 📌 Problem Statement

In today's competitive business environment, treating all customers equally is inefficient and costly. Companies face critical challenges in customer relationship management:

- **Unable to identify** which customers are most valuable and which are at risk of churning  
- **Lack of segmentation strategy** leading to generic, ineffective marketing campaigns  
- **No systematic approach** to prioritize customer retention and acquisition efforts  
- **Limited visibility** into customer behavior patterns (purchase frequency, recency, spending)  
- **Inefficient resource allocation** across customer segments with varying profitability  
- **Missing early warning signals** for customer churn and declining engagement  

This project solves these challenges by implementing **RFM (Recency, Frequency, Monetary) Analysis** — a proven data-driven framework that segments customers based on their purchasing behavior, enabling targeted strategies and maximizing customer lifetime value.

---

## 🎯 Objective

Build an interactive Power BI dashboard that:
1. Implements RFM segmentation to categorize customers into actionable groups  
2. Tracks customer behavior trends across recency, frequency, and monetary dimensions  
3. Identifies high-value customers (Champions, Loyal) and at-risk customers (Lost, At Risk)  
4. Provides month-over-month performance tracking with year-over-year comparisons  
5. Enables data-driven customer retention and acquisition strategies  

---

## 📊 Dashboard Overview

<p align="center">
  <img src="https://github.com/MuzammilAhmed14/PowerBI-Projects/blob/main/RFM%20Analysis%20Project/Images/Dashboard.JPG?raw=true" alt="RFM Dashboard" width="800">
</p>

### Key Metrics
- **Total Sales**: $1,966K (↑ 24.9% vs. Last Year: $1,574K)  
- **Average Recency**: 200 days (↓ 0.5% vs. LY: 201)  
- **Average Frequency**: 5 purchases (↓ 0.7% vs. LY: 5)  
- **Average Monetary Value**: $2,491 (↓ 0.8% vs. LY: $2,510)  
- **Total Customers**: 2,085 (across all segments)

---

### RFM Customer Segmentation

**Segment Distribution:**
- **Champions** (139 customers): Bought recently, buy often, and spend the most  
- **Loyal Customers** (128 customers): Regular buyers with consistent purchase patterns  
- **Big Spenders** (114 customers): High spenders but buy less frequently  
- **At Risk** (105 customers): Previously good customers showing declining engagement  
- **Lost** (27 customers): Haven’t purchased in a long time, at risk of churn  
- **Others** (276 customers): Various segments requiring further analysis  

---

### Monthly Trend Analysis

**Sales & Customer Trends (Month-by-Month):**
- **November**: $0.24M sales, 282 customers (highest performing month)  
- **August**: $0.23M sales, 268 customers  
- **March**: $0.20M sales, 270 customers  
- **September**: $0.19M sales, 302 customers  
- **December**: $0.18M sales, 274 customers  
- **October**: $0.17M sales, 320 customers  
- **May**: $0.16M sales, 291 customers  
- **July**: $0.15M sales, 287 customers  
- **June**: $0.14M sales, 177 customers  
- **April**: $0.13M sales, 374 customers  
- **January**: $0.10M sales, 373 customers  
- **February**: $0.08M sales, 179 customers (lowest performing month)  

---

### Category Analysis

**Customer Distribution by Product Category:**
- **Office Supplies**: 778 customers (37%)  
- **Furniture**: 666 customers (32%)  
- **Technology**: 641 customers (31%)  

---

### Customer Details Table

Detailed customer-level data includes:
- Customer ID and Name  
- RFM Segment Classification  
- **Frequency**: Number of purchases  
- **Monetary**: Total spend  
- **Recency**: Days since last purchase  

**Sample High-Risk Customers:**
- Jennifer Halladay (**Lost**) — 1 purchase, $55.67, 1,295 days inactive  
- Mitch Willingham (**Big Spender**) — 1 purchase, $3,333.90, 1,208 days inactive  
- Hilary Holden (**Lost**) — 1 purchase, $123.28, 1,108 days inactive  
- Nicole Brennan (**Lost**) — 2 purchases, $273.87, 1,054 days inactive  

---

### Interactive Filters
- **Year Filter**: Analyze performance across different years  
- **City Filter**: Regional segmentation  
- **Drill-downs**: Explore customer-level insights  

---

## 💡 Key Insights

1. **24.9% YoY growth** indicates strong performance  
2. **Slight decline** in recency, frequency, and monetary metrics — early warning  
3. **Seasonality detected** — November & August strong, February weak  
4. **Segment imbalance** — 276 customers in “Others” need reclassification  
5. **Churn alert** — 132 customers in “At Risk” or “Lost” categories  
6. **Limited Champions** — Potential to convert Loyal → Champions  
7. **Big Spenders underutilized** — High value, low frequency  
8. **Diverse product mix** — Balanced across categories  
9. **Inactive customers (1000+ days)** still in DB → cleanup needed  
10. **Customer fluctuations** — October: many customers, low AOV  

---

## 🔍 What is RFM Analysis?

**RFM Analysis** segments customers using three metrics:  
- **Recency (R)** — How recently a purchase was made  
- **Frequency (F)** — How often purchases occur  
- **Monetary (M)** — How much money is spent  

Each customer gets an RFM score (1–5 scale).  
Example segments:
- **Champions**: 555, 554, 544  
- **Loyal**: High F & M, moderate R  
- **Big Spenders**: High M, low F  
- **At Risk**: Declining R  
- **Lost**: Low R  

---

## 🛠️ Technical Implementation

**Tools Used**: Power BI Desktop  

**Key Features:**
- RFM scoring algorithm via **DAX**  
- Custom segmentation logic  
- **YoY comparisons** and percentage indicators  
- Monthly trend charts  
- Interactive filters and KPIs  
- Customer-level data table  

**Data Model Includes:**
- Customer master  
- Transaction/sales data  
- Product categories  
- Date dimension  

---

## 🧠 What I Learned

### 🧩 Technical Skills
- Power BI visualization & dashboard design  
- DAX for scoring & metrics  
- Power Query transformations  
- Data modeling & time intelligence  
- Conditional formatting & interactivity  

### 💼 Business Intelligence
- Customer lifecycle & retention strategy  
- Segmentation best practices  
- Turning insights into actions  
- Executive-ready reporting  

### 📊 Data Analytics
- RFM methodology  
- Customer pattern recognition  
- Cohort & trend analysis  
- Predictive churn signals  

---

## 📈 Business Impact & Recommendations

### Immediate Actions
**Champions (139)** — Nurture loyalty with exclusive offers  
**At Risk (105)** — Win-back campaigns & reactivation  
**Lost (27)** — Deep discount outreach  
**Big Spenders (114)** — Increase frequency via bundles  
**Loyal (128)** — Convert to Champions through incentives  

### Strategic Recommendations
- Reduce average **recency** via engagement  
- Boost **frequency** with loyalty programs  
- Address **February slump** with targeted promos  
- Prep **November** for high demand  
- Refine **“Others”** classification  

---

## 🎯 Use Cases

- **Marketing Teams** — Design campaigns for each RFM group  
- **Sales Teams** — Prioritize high-value customers  
- **Customer Success** — Prevent churn via proactive outreach  
- **Product Teams** — Identify product affinities  
- **Finance Teams** — Forecast revenue by segment  
- **Executives** — Track customer health and growth  

---

👤 **Author**  
**Sheikh Muzammil Ahmed**  
📊 *Data Analyst | Business Intelligence Enthusiast | Power BI Storyteller*  

📫 **Connect:**  
[LinkedIn](https://www.linkedin.com/in/muzammil-ahmed-ap2000)  

🏷️ **Tags:**  
#PowerBI #DataAnalytics #RFMAnalysis #CustomerSegmentation #DataStorytelling #BusinessIntelligence #CustomerRetention #MarketingAnalytics  

---
