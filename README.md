# Food-Delivery-Analytics-Dashboard-
Developed a comprehensive Power BI dashboard to analyze food delivery business performance. Implemented ETL using Power Query, designed a Star Schema data model, created DAX measures for KPIs, and built interactive dashboards for executive, operations, customer, and marketing analytics.

# 🍔 Food Delivery Analytics Dashboard | Power BI

> An end-to-end Business Intelligence project built using Power BI, Power Query, DAX, and Star Schema Data Modeling to analyze food delivery operations, customer experience, and marketing campaign performance.

---

# 📌 Project Overview

This project focuses on analyzing food delivery business operations using Power BI. The dashboard provides meaningful insights into revenue, delivery performance, customer satisfaction, and marketing effectiveness through interactive visualizations and KPI-driven reporting.

The project demonstrates the complete Business Intelligence workflow:

- Data Collection
- Data Cleaning
- Power Query (ETL)
- Data Modeling
- DAX Calculations
- Interactive Dashboard Design
- Business Insights

---

# 🎯 Business Objectives

The primary objectives of this project are:

- Analyze overall business performance
- Monitor revenue and order trends
- Track delivery efficiency
- Evaluate customer satisfaction
- Measure campaign effectiveness
- Identify high-performing cities and restaurants

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|-------|----------|
| Power BI Desktop | Dashboard Development |
| Power Query | ETL & Data Cleaning |
| DAX | KPI Calculations |
| Excel | Source Data |
| GitHub | Version Control |

---

# 📂 Dataset

The project contains the following tables.

### Fact Tables

- fact_orders
- fact_order_items
- fact_ratings

### Dimension Tables

- dim_customer
- dim_city
- dim_date
- dim_restaurant
- dim_rider
- dim_payment_method
- dim_marketing_campaign
- dim_cancel_reason

### Bridge Table

- bridge_order_campaign

---

# 🔄 Power Query (ETL)

The following transformations were performed:

- Imported monthly Excel files
- Combined multiple files into single fact tables
- Promoted headers
- Changed data types
- Removed unnecessary columns
- Loaded dimension tables
- Built a clean analytical data model

---

# ⭐ Data Model

A Star Schema was implemented to improve performance and simplify reporting.

(Add Model View Image Here)

---

# 📊 Dashboard Pages

## 1️⃣ Executive Overview

Provides a high-level summary of business performance.

### KPIs

- Net Revenue
- Total Orders
- Average Order Value (AOV)
- OTIF %
- Cancellation Rate
- Average Food Rating
- Average Delivery Rating

(Add Executive Dashboard Image)

---

## 2️⃣ Operations Dashboard

Tracks operational efficiency.

### Highlights

- OTIF by City
- Delivery Time
- Cancellation Analysis
- Rider Performance
- Delivery Trend

(Add Operations Dashboard Image)

---

## 3️⃣ Customer Experience Dashboard

Analyzes customer behaviour.

### Highlights

- Customer Ratings
- Delivery Ratings
- Customer Demographics
- Occupation Analysis
- Income Segmentation

(Add Customer Dashboard Image)

---

## 4️⃣ Marketing Campaign Dashboard

Measures campaign effectiveness.

### Highlights

- Campaign Revenue
- Campaign Orders
- Campaign AOV
- Channel Performance
- Top Campaigns

(Add Marketing Dashboard Image)

---

# 📈 Key Business Insights

- Mumbai generated the highest number of orders.
- UPI is the most preferred payment method.
- Display campaigns generated the highest campaign revenue.
- Average Food Rating is 4.10.
- OTIF performance is approximately 51%.
- Campaign performance varies significantly across marketing channels.

---

# 💡 Skills Demonstrated

- Data Cleaning
- ETL using Power Query
- Star Schema Data Modeling
- DAX Measures
- KPI Design
- Business Intelligence
- Dashboard Design
- Data Visualization
- Analytical Thinking

---

# 📁 Project Structure

Food-Delivery-Analytics-PowerBI

├── Dashboard

│ └── Food_Delivery_Analytics.pbix

├── Dataset

├── Images

│ ├── Executive_Overview.png

│ ├── Operations_Dashboard.png

│ ├── Customer_Experience.png

│ ├── Marketing_Campaign.png

│ └── Data_Model.png

├── README.md

└── LICENSE

---

# Future Improvements

- Publish to Power BI Service
- Enable Scheduled Refresh
- Implement Row-Level Security (RLS)
- Add Forecasting
- Add Drill-through Reports

---

#  Author

**Shri Rishwanth U K**

Computer Science Engineering (Data Science)

SRM Institute of Science and Technology

GitHub: https://github.com/Rishwanth03

LinkedIn: https://www.linkedin.com/in/shri-rishwanth-u-k-a34618375/?skipRedirect=true

---

⭐ If you found this project useful, consider giving it a star.
