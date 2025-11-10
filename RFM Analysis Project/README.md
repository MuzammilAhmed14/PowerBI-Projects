# Sales Dashboard - RFM Analysis | Power BI

## 📌 Problem Statement

In today's competitive business environment, treating all customers equally is inefficient and costly. Companies face critical challenges in customer relationship management:

- **Unable to identify** which customers are most valuable and which are at risk of churning
- **Lack of segmentation strategy** leading to generic, ineffective marketing campaigns
- **No systematic approach** to prioritize customer retention and acquisition efforts
- **Limited visibility** into customer behavior patterns (purchase frequency, recency, spending)
- **Inefficient resource allocation** across customer segments with varying profitability
- **Missing early warning signals** for customer churn and declining engagement

This project solves these challenges by implementing **RFM (Recency, Frequency, Monetary) Analysis** - a proven data-driven framework that segments customers based on their purchasing behavior, enabling targeted strategies and maximizing customer lifetime value.

## 🎯 Objective

Build an interactive Power BI dashboard that:
1. Implements RFM segmentation to categorize customers into actionable groups
2. Tracks customer behavior trends across recency, frequency, and monetary dimensions
3. Identifies high-value customers (Champions, Loyal) and at-risk customers (Lost, At Risk)
4. Provides month-over-month performance tracking with year-over-year comparisons
5. Enables data-driven customer retention and acquisition strategies

## 📊 Dashboard Overview

![Churn Dashboard](https://github.com/MuzammilAhmed14/PowerBI-Projects/blob/main/RFM%20Analysis%20Project/Images/Dashboard.JPG)

### Key Metrics
- **Total Sales**: $1,966K (↑ 24.9% vs. Last Year: $1,574K)
- **Average Recency**: 200 days (↓ 0.5% vs. LY: 201)
- **Average Frequency**: 5 purchases (↓ 0.7% vs. LY: 5)
- **Average Monetary Value**: $2,491 (↓ 0.8% vs. LY: $2,510)
- **Total Customers**: 2,085 (across all segments)

### RFM Customer Segmentation

**Segment Distribution:**
- **Champions** (139 customers): Best customers - bought recently, buy often, and spend the most
- **Loyal Customers** (128 customers): Regular buyers with consistent purchase patterns
- **Big Spenders** (114 customers): High monetary value but may not buy frequently
- **At Risk** (105 customers): Previously good customers showing declining engagement
- **Lost** (27 customers): Haven't purchased in a long time, at high risk of permanent churn
- **Others** (276 customers): Various segments requiring further analysis

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

### Category Analysis

**Customer Distribution by Product Category:**
- **Office Supplies**: 778 customers (37% of customer base)
- **Furniture**: 666 customers (32%)
- **Technology**: 641 customers (31%)

### Customer Details Table

Detailed customer-level data showing:
- Customer ID and Name
- RFM Segment Classification
- **Frequency**: Number of purchases
- **Monetary**: Total spending amount
- **Recency**: Days since last purchase

**Sample High-Risk Customers:**
- Jennifer Halladay (Lost): 1 purchase, $55.67, 1,295 days inactive
- Mitch Willingham (Big Spender): 1 purchase, $3,333.90, 1,208 days inactive
- Hilary Holden (Lost): 1 purchase, $123.28, 1,108 days inactive
- Nicole Brennan (Lost): 2 purchases, $273.87, 1,054 days inactive

### Interactive Filters
- **Year Filter**: Analyze performance across different years
- **City Filter**: Geographic segmentation for regional strategies
- Drill-down capabilities for detailed customer analysis

## 💡 Key Insights

1. **Strong YoY growth** - 24.9% sales increase demonstrates business expansion
2. **Customer behavior declining slightly** - Small decreases in recency, frequency, and monetary metrics need attention
3. **Seasonal patterns exist** - November and August are peak months; February is weakest
4. **Segment imbalance** - 276 customers in "Others" category need better classification
5. **Churn risk identified** - 27 "Lost" customers and 105 "At Risk" customers require immediate intervention
6. **Champions are limited** - Only 139 Champions suggests opportunity to upgrade Loyal customers
7. **Big Spenders underutilized** - 114 high-value customers with low frequency need engagement
8. **Balanced category distribution** - No single category dominates, showing diversified business
9. **Long-term inactive customers** - Some customers inactive for 1,000+ days still in database
10. **Customer count fluctuates monthly** - October had 320 customers but lower sales, indicating lower average order value

## 🔍 What is RFM Analysis?

**RFM Analysis** is a customer segmentation technique that evaluates customers based on three key metrics:

- **Recency (R)**: How recently did the customer make a purchase?
  - Recent buyers are more likely to respond to promotions
  
- **Frequency (F)**: How often does the customer make purchases?
  - Frequent buyers show higher engagement and loyalty
  
- **Monetary (M)**: How much money does the customer spend?
  - High spenders contribute more to revenue

**RFM Score Calculation**: Each customer receives a score (typically 1-5) for each dimension, creating segments like:
- **Champions**: High R, F, M scores (555, 554, 544, etc.)
- **Loyal Customers**: High F and M, moderate R
- **Big Spenders**: High M, lower F
- **At Risk**: Previously high scores, declining R
- **Lost**: Low R (haven't purchased recently)

## 🛠️ Technical Implementation

**Tools Used**: Power BI Desktop

**Key Features**:
- **RFM scoring algorithm** implemented using DAX
- **Custom customer segmentation** logic based on RFM scores
- **Year-over-year comparison** with percentage change indicators
- **Monthly trend visualization** with dual-axis charts (sales + customers)
- **Interactive segment filtering** for deep-dive analysis
- **Customer-level detail table** for operational use
- **Dynamic KPI cards** with performance indicators
- **Category-based customer distribution** analysis

**DAX Measures Created**:
- Recency calculation (days since last purchase)
- Frequency count (number of transactions)
- Monetary aggregation (total customer spend)
- RFM scores (1-5 scale for each dimension)
- Segment classification logic
- YoY comparison metrics
- Average RFM values

**Data Model**:
- Customer master data
- Transaction/sales data
- Product category information
- Date dimension for time-based analysis
- RFM calculated columns and measures

## 🧠 What I Learned

### 🧩 Technical Skills
- **Power BI Desktop** advanced visualization and dashboard design
- **DAX** complex calculations for RFM scoring algorithm and segmentation logic
- **Power Query** for data transformation and RFM metric calculations
- **Data modeling** with customer transaction relationships
- **Calculated columns and measures** for dynamic RFM analysis
- **Conditional formatting** for segment-based color coding
- **Time intelligence functions** for YoY comparisons and trend analysis

### 💼 Business Intelligence
- Understanding **customer lifecycle management** and retention strategies
- Implementing **RFM methodology** as a strategic framework
- **Customer segmentation** best practices and actionable groupings
- Translating **marketing requirements** into analytical solutions
- Creating **actionable insights** for customer retention and acquisition
- Designing **executive-level KPI dashboards** with clear metrics

### 📊 Data Analytics
- **RFM Analysis methodology** - calculating and interpreting recency, frequency, monetary values
- **Customer behavior analysis** and pattern recognition
- **Cohort segmentation** based on purchasing behavior
- **Trend analysis** for seasonality and performance patterns
- **Year-over-year comparison** techniques
- **Predictive indicators** for customer churn (recency increases)
- **Value-based segmentation** to identify high-value customers

### 🧩 Problem-Solving
- Breaking down **customer base complexity** into manageable segments
- Developing **scoring algorithms** for customer classification
- Creating **early warning systems** for churn (At Risk, Lost segments)
- Balancing **simplicity and sophistication** in segmentation
- Prioritizing **customer engagement strategies** based on segments
- Identifying **quick wins** (re-engage Big Spenders) vs. long-term strategies

### 🗣️ Communication
- **Data storytelling** through RFM framework
- Creating **marketing-friendly dashboards** with clear action items
- Presenting **customer insights** to non-technical stakeholders
- Building **self-service analytics** for sales and marketing teams
- Designing **intuitive segment labels** (Champions, At Risk, Lost)
- Enabling **data-driven customer conversations** across organization

## 📈 Business Impact & Recommendations

### Immediate Actions:

**1. Champion Nurturing (139 customers)**
- VIP treatment and exclusive offers
- Early access to new products
- Personalized communication
- Loyalty rewards program

**2. At Risk Recovery (105 customers)**
- Win-back campaigns with special discounts
- Survey to understand declining engagement
- Personalized re-engagement emails
- Limited-time offers to trigger purchases

**3. Lost Customer Win-Back (27 customers)**
- Aggressive re-activation campaigns
- Deep discount offers
- "We miss you" messaging
- Remove from database if no response after 90 days

**4. Big Spender Activation (114 customers)**
- Increase purchase frequency with subscription models
- Cross-sell and upsell campaigns
- Exclusive product bundles
- Frequency-based rewards program

**5. Loyal Customer Upgrade (128 customers)**
- Convert to Champions through increased spending
- Premium product recommendations
- Referral incentives
- Bundle offers to increase basket size

### Strategic Improvements:

- **Reduce average recency** through consistent engagement campaigns
- **Increase purchase frequency** with loyalty programs and reminders
- **Address February slump** with targeted promotions
- **Leverage November peak** by preparing inventory and campaigns
- **Investigate "Others" segment** for better classification
- **Focus on Office Supplies category** (highest customer count)

```
## 🎯 Use Cases

- **Marketing Teams**: Create targeted campaigns for each RFM segment
- **Sales Teams**: Prioritize high-value customers and at-risk accounts
- **Customer Success**: Proactive outreach to At Risk and Lost customers
- **Product Teams**: Understand category preferences by customer segment
- **Finance Teams**: Forecast revenue based on customer behavior trends
- **Executive Leadership**: Monitor customer health and business growth
---

👤 **Author**  
Sheikh Muzammil Ahmed  
📊 **Data Analyst | Business Intelligence Enthusiast | Power BI Storyteller**

📫 **Connect**  
[LinkedIn](https://www.linkedin.com/in/muzammil-ahmed-ap2000)

🏷️ **Tags**  
#PowerBI #DataAnalytics #CreditCardAnalysis #FinancialAnalytics #CustomerSegmentation #DataStorytelling #BusinessIntelligence #TransactionAnalysis
