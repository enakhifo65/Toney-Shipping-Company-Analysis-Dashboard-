# Toney-Shipping-Company-Analysis-Dashboard-
Power BI Shipping &amp; Logistics Analytics Dashboard with KPI tracking, revenue analysis, TEU monitoring, and operational insights.
## Project Overview

The Shipping Analytics Dashboard is a comprehensive Power BI solution developed to analyze and monitor shipping operations, logistics performance, revenue trends, vessel activities, and port efficiency.

This project provides business stakeholders and operations managers with actionable insights through interactive dashboards, KPI monitoring, and operational analytics.

The dashboard combines financial analysis, operational performance tracking, and executive-level reporting into a centralized business intelligence solution.

---

# Objectives

The primary objectives of this project are to:

- Monitor Total TEUs (Twenty-foot Equivalent Units)
- Analyze shipping revenue performance
- Track operational delays and on-time arrivals
- Evaluate vessel and shipping line performance
- Compare actual performance against targets
- Identify operational inefficiencies across ports and move codes
- Provide management with data-driven insights for decision-making

---

# Dashboard Pages

## 1. Executive Overview

This page provides a high-level summary of shipping and financial performance.

### Key Metrics
- Total TEUs
- Total Revenue
- Delay Rate
- On-Time Arrival Rate
- MOM Growth %
- YOY Growth %

### Key Insights
- Revenue trends over time
- Delay analysis by origin port
- Revenue vs Target comparison
- Vessel performance overview
- Shipping line contribution analysis

---

## 2. Operations Analysis

This page focuses on operational efficiency and logistics activities.

### Features
- Average moves per day, week, month, and year
- TEU movement analysis
- Move code performance
- Port destination analysis
- User productivity tracking
- Vessel activity analysis
- Shipping line operational performance

### Operational KPIs
- Total TEUs by Month
- TEUs by Move Codes
- TEUs by Shipping Line
- TEUs by Vessel Name
- Top & Least Performing Shipping Lines

---

## 3. Revenue Analysis

This page provides detailed financial insights into shipping operations.

### Revenue Metrics
- Total Revenue
- Revenue per Size
- Revenue per Terminal Day
- Revenue by Vessel
- Revenue by Shipping Line
- Revenue by Destination Port
- Quarterly Revenue Trends

### Financial Analysis
- Revenue target tracking
- Comparative trend analysis
- Revenue contribution breakdown
- Operational revenue segmentation
  
---
## 4. Fleet Analysis

This page focuses on fleet performance

### Fleet Metrics
- Total Truck Trips
- Trucks Trips by month
- Truck Utilization


# Tools & Technologies Used

- **Power BI**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel**

---

# Key Features

- Interactive dashboard navigation
- Dynamic slicers and filters
- KPI cards with MOM & YOY analysis
- Revenue and operational trend analysis
- Custom dashboard UI/UX design
- Target vs Actual performance tracking
- Drill-down analytical reporting
- Responsive visual storytelling

---

# Business Questions Answered

This dashboard helps answer critical business questions such as:

- Which shipping lines generate the highest revenue?
- Which ports experience the highest delay rates?
- How are TEUs trending over time?
- Which vessels contribute most to operations?
- How does actual performance compare to targets?
- Which move codes generate the most operational activity?
- What are the major revenue drivers?

---

# Data Preparation Process

The dataset was cleaned and transformed using Power Query.

### Data Preparation Steps
- Removed duplicates
- Handled missing values
- Standardized column formats
- Created calculated columns
- Built relationships between tables
- Developed custom DAX measures for KPI calculations

---

# DAX Measures Implemented

Examples of measures created in this project include:

```DAX
Total Revenue = SUM(ShippingData[Revenue])

Total TEUs = SUM(ShippingData[TEUs])

YOY Revenue % =
DIVIDE(
    [Total Revenue] - [Previous Year Revenue],
    [Previous Year Revenue]
)

MOM Revenue % =
DIVIDE(
    [Current Month Revenue] - [Previous Month Revenue],
    [Previous Month Revenue]
)
```

---

# Dashboard Screenshots

## Executive Overview
<img width="1281" height="717" alt="Dashboard 1" src="https://github.com/user-attachments/assets/e53148d2-6997-4852-8efd-93525d00fedb" />

## Operations Analysis
<img width="1282" height="721" alt="Dashboard 2" src="https://github.com/user-attachments/assets/c7b4e93f-753e-415a-8fc8-cc5a78aa9eb6" />

## Revenue Analysis
<img width="1283" height="721" alt="Dashboard 3" src="https://github.com/user-attachments/assets/d469fc95-2cbf-4c20-9132-e78faeb0ef81" />

## Fleet Analysis
<img width="1284" height="722" alt="Dashboard 4" src="https://github.com/user-attachments/assets/093fbeda-7d2f-4d65-a348-9057c619fd08" />


---

# Project Structure

```text
Shipping-Analytics-Dashboard/
│
├── README.md
├── Shipping_Analytics.pbix
├── Dataset/
│   └── shipping_data.xlsx
├── Screenshots/
│   ├── executive_overview.png
│   ├── operations_analysis.png
│   └── revenue_analysis.png
├── DAX/
│   └── measures.md
└── Documentation/
    └── project_overview.pdf
```

---

# Key Learnings

Through this project, I gained practical experience in:

- Business Intelligence reporting
- Dashboard storytelling
- Data visualization best practices
- KPI development
- DAX calculations
- Data modeling
- Operational analytics
- Financial performance analysis

---


# Author

## Enakhifo Victor

- LinkedIn: www.linkedin.com/in/victor-ohiorenua-enakhifo-033146188
- Email: enakhifoanthony65@gmail.com

---

# License

This project is for educational and portfolio purposes only.
