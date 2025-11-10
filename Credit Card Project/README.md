# Credit Card Transaction & Customer Analysis - Power BI Dashboard

## 📌 Problem Statement

Credit card companies generate massive volumes of transaction data daily, but struggle to extract meaningful insights from this data. The key challenges include:

- **Lack of visibility** into revenue patterns across different customer segments
- **Inability to identify** high-value customer profiles and spending behaviors
- **Poor understanding** of transaction trends and seasonal variations
- **Limited insights** into card usage patterns (chip, swipe, online)
- **Difficulty tracking** performance metrics across card categories and demographics
- **No unified view** of transaction and customer data for strategic decision-making

This project addresses these challenges by creating a comprehensive analytical framework that transforms raw transaction data into actionable business intelligence for marketing, product development, and customer relationship management.

## 🎯 Objective

Build an interactive Power BI dashboard that:
1. Analyzes credit card transaction patterns and revenue trends
2. Provides deep insights into customer demographics and behavior
3. Tracks performance across card categories, expenditure types, and geographies
4. Enables data-driven decision making for marketing and product strategies
5. Identifies opportunities for revenue optimization and customer targeting

## 📊 Dashboard Overview

### Key Metrics
- **Total Revenue**: $55M
- **Total Transaction Amount**: $45M
- **Total Interest Earned**: $7.84M
- **Transaction Count**: 656K
- **Customer Satisfaction (CSAT)**: 3.19/5
- **Total Customer Income**: $576M

## 📊 Dashboard Screenshots

### Main Transactions Dashboard
![Credit Card Transactions Dashboard](https://github.com/MuzammilAhmed14/PowerBI-Projects/blob/main/Credit%20Card%20Project/Images/Transaction%20Dashboard.JPG)

### Customer Overview Dashboard
![Credit Card Customer Dashboard](https://github.com/MuzammilAhmed14/PowerBI-Projects/blob/main/Credit%20Card%20Project/Images/Customer%20Dashboard.JPG)

---

### Page 1: Credit Card Transactions Overview

**Quarterly Performance**
- Q1: $14.0M revenue, 163.3K transactions
- Q2: $13.8M revenue, 161.6K transactions
- Q3: $14.2M revenue, 166.6K transactions
- Q4: $13.3M revenue, 164.2K transactions

**Revenue by Expenditure Type**
- Bills: $14M (highest spending category)
- Entertainment: $10M
- Fuel: $9M
- Grocery: $9M
- Food: $8M
- Travel: $6M

**Revenue by Card Category**
- Blue Card: $46M (83% of total revenue)
- Silver Card: $6M
- Gold Card: $2M
- Platinum Card: $1M

**Revenue by Transaction Method**
- Swipe: $35M (64% of transactions)
- Chip: $17M (31%)
- Online: $3M (5%)

**Revenue by Education Level**
- Graduate: $22M
- High School: $11M
- Unknown: $8M
- Uneducated: $8M
- Post-Graduate: $3M
- Doctorate: $2M

**Revenue by Customer Job**
- Businessman: $17M
- White-collar: $10M
- Self-employed: $8M
- Government: $8M
- Blue-collar: $7M
- Retirees: $5M

**Detailed Metrics Table**
- Revenue, transaction amount, and interest earned breakdown by card category
- Blue card dominates with $46.1M revenue and $6.5M interest earned

---

### Page 2: Credit Card Customer Overview

**Age-wise Revenue Distribution**
- 40-50 years: $14M (highest revenue segment)
- 50-60 years: $11M
- 30-40 years: $10M
- 60+ years: $9M
- 20-30 years: $4M + $5M segments

**Gender-based Analysis**
- Male: $30M revenue
- Female: $25M revenue

**Income Group Revenue**
- High Income: $22M (40% of revenue)
- Medium Income: $10M
- Low Income: $8M
- Unknown: $8M + $7M segments

**Revenue by Dependents**
- 3 dependents: $9M (highest)
- 2 dependents: $8M
- 4 dependents: $7M
- 1 dependent: $7M
- 0 dependents: $5M + $5M
- 5 dependents: $4M

**Education-wise Revenue**
- Graduate: $12M (highest)
- High School: $10M
- Post-Graduate: $6M
- Unknown: $5M + $4M
- Doctorate: $4M
- Uneducated: $4M

**Top 5 States by Revenue**
- Texas (TX): $13M
- New York (NY): $13M
- California (CA): $12M
- Florida (FL): $7M
- New Jersey (NJ): $2M

**Marital Status Revenue**
- Married: $26M
- Single: $22M
- Unknown: Remaining revenue

**Weekly Revenue Trends**
- Time series visualization from Jan 2023 to Oct 2023
- Revenue ranges between $0.2M to $0.8M per week
- Identifies seasonal patterns and trends

**Customer Job Analysis Table**
- Businessmen generate highest revenue ($17.4M) with $187M total income
- White-collar workers: $10.1M revenue with $104M income
- Self-employed: $8.3M revenue with $75M income

---

## 💡 Key Insights

1. **Blue cards dominate** - 83% of revenue comes from basic Blue card category
2. **Bill payments lead spending** - Bills are the highest expenditure category at $14M
3. **Physical transactions preferred** - 64% revenue from swipe, only 5% online
4. **Mid-age customers are key** - 40-50 age group generates highest revenue ($14M)
5. **High-income focus** - 40% of revenue from high-income customers
6. **Businessmen are top spenders** - Highest revenue and income generation
7. **Geographic concentration** - Texas and New York lead with $13M each
8. **Quarterly stability** - Revenue relatively stable across quarters ($13-14M)
9. **Gender gap exists** - Male customers generate 20% more revenue than females
10. **Family-oriented customers** - Customers with 2-3 dependents show highest spending

---

## 🛠️ Technical Implementation

**Tools Used**: Power BI Desktop

**Key Features**:
- Interactive KPI cards displaying key metrics
- Quarterly trend analysis with combo charts
- Bar charts for categorical comparisons
- Time series analysis for weekly revenue trends
- Geographic visualization for state-wise performance
- Matrix tables for detailed breakdowns
- Dynamic filters (Week, Quarter, Gender, Card Category, Income Group)
- Cross-filtering across all visualizations
- Dual-page dashboard design (Transactions + Customers)

**Data Model**:
- Transaction data (amount, volume, date, type)
- Customer demographics (age, gender, education, job, marital status)
- Card information (category, chip type)
- Geographic data (state-level)
- Revenue and interest calculations

---

## 🧠 What I Learned

### 🧩 Technical Skills
- **Power BI Desktop** proficiency with multi-page dashboard design
- **DAX** functions for revenue calculations, aggregations, and time intelligence
- **Power Query** for ETL processes and data transformation
- **Data modeling** with relationships between transaction and customer tables
- Creating **dynamic filters and slicers** for interactive analysis
- **Time series visualization** for trend analysis
- **Calculated measures** for KPIs (total revenue, interest earned, CSAT)

### 💼 Business Intelligence
- Translating **financial data requirements** into analytical solutions
- **KPI identification** for credit card business metrics
- **Dashboard design** principles for financial reporting
- Creating **dual-perspective analysis** (transactions + customers)
- Understanding **credit card business models** and revenue streams
- **Stakeholder-focused design** for executive and operational teams

### 📊 Data Analytics
- **Customer segmentation** across multiple dimensions (age, income, job, education)
- **Transaction pattern analysis** by expenditure type and payment method
- **Geographic analysis** and regional performance tracking
- **Time-based analysis** with quarterly and weekly trends
- **Revenue attribution** across card categories and customer segments
- **Cohort analysis** by demographics and behavior

### 🧩 Problem-Solving
- Breaking down **complex financial data** into digestible insights
- Identifying **revenue drivers** and high-value customer segments
- Creating **actionable insights** for marketing and product teams
- Balancing **depth of analysis** with dashboard simplicity
- Designing **intuitive navigation** between transaction and customer views

### 🗣️ Communication
- **Financial storytelling** through data visualization
- Creating **executive-friendly dashboards** with clear KPIs
- Designing **self-service analytics** for business users
- Building **visual hierarchy** to guide user attention
- Presenting **multi-dimensional analysis** in an accessible format
- Enabling **data-driven conversations** across departments

---

## 📈 Business Impact

This dashboard enables:
- **Targeted marketing campaigns** based on customer segments (age, income, job)
- **Product strategy optimization** (focus on Blue card, enhance online experience)
- **Revenue forecasting** using quarterly and weekly trends
- **Customer acquisition strategies** focusing on high-value demographics
- **Geographic expansion planning** based on state-level performance
- **Payment method optimization** (improving online transaction experience)
- **Risk management** through transaction pattern monitoring
- **Customer satisfaction improvement** initiatives based on CSAT scores
- **Card category repositioning** to boost Gold and Platinum adoption

---

## 🎯 Use Cases

- **Marketing Teams**: Identify high-value customer segments for campaigns
- **Product Teams**: Understand card usage patterns to improve offerings
- **Sales Teams**: Target specific demographics and regions for growth
- **Finance Teams**: Track revenue trends and interest earnings
- **Customer Success**: Improve CSAT through behavioral insights
- **Executive Leadership**: Monitor overall business performance and KPIs

---

👤 **Author**  
Sheikh Muzammil Ahmed  
📊 **Data Analyst | Business Intelligence Enthusiast | Power BI Storyteller**

📫 **Connect**  
[LinkedIn](https://www.linkedin.com/in/muzammil-ahmed-ap2000)

🏷️ **Tags**  
#PowerBI #DataAnalytics #CreditCardAnalysis #FinancialAnalytics #CustomerSegmentation #DataStorytelling #BusinessIntelligence #TransactionAnalysis
