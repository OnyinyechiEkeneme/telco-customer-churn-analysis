# ConnectTel Customer Churn Analysis Dashboard

## Project Overview

This project analyzes customer churn behavior for ConnectTel, a telecommunications company experiencing a high churn rate of 26.5%.

The objective of the project is to identify:

* Who is churning
* Why customers are churning
* Revenue impact of churn
* High-risk customer segments
* Customers requiring immediate retention intervention

The solution was built in Power BI using advanced DAX modeling, custom HTML/CSS visuals, and interactive customer prioritization components.

---

# Business Problem

ConnectTel serves 7,043 telecom customers across internet and phone services.

The company identified a critical business issue:

* 26.5% of customers are churning
* Customer acquisition costs are 5–7x higher than retention costs
* The retention team only reacts after customers leave

The business needed a proactive analytics solution capable of:

* Predicting high-risk customers
* Identifying churn drivers
* Quantifying revenue at risk
* Prioritizing customer retention efforts

---

# Business Questions Answered

## How bad is the problem?

* What is the current churn rate?
* How many customers have churned?
* Is churn worsening over time?
* What percentage of revenue is at risk?

## Who is churning?

* Which customer groups churn most frequently?
* Which tenure groups are most vulnerable?
* Are senior citizens more likely to churn?
* Are high-value customers churning?

## Why are they churning?

* Which factors drive churn?
* Which contract types are highest risk?
* Which customers should the retention team prioritize?

## Financial Impact

* How much recurring monthly revenue is being lost?
* Which customer segments create the largest financial exposure?
* Which risk tiers threaten revenue most?

---

# Tools & Technologies Used

* Power BI
* DAX
* Power Query
* HTML/CSS inside Power BI
* JavaScript-powered custom visuals
* CSV data modeling
* Time intelligence calculations

---

# Advanced Features Implemented

## Advanced DAX Modeling

Implemented:

* Calculated columns
* KPI measures
* Time intelligence measures
* Risk scoring logic
* Dynamic comparison metrics
* Revenue-at-risk calculations

Examples include:

* Churn Rate
* Revenue Lost %
* Risk Tier Metrics
* Period-over-Period Analysis
* Retention Rate
* Revenue at Risk

---

# Custom Risk Scoring System

A custom churn risk scoring framework was developed using customer behavioral indicators.

Risk factors included:

* Short tenure
* Month-to-month contracts
* Fiber optic subscriptions
* Electronic check payments
* Lack of tech support
* Senior citizen status
* No partner/dependent indicators

Customers were dynamically classified into:

* Critical
* High
* Medium
* Low risk tiers

This enabled proactive customer prioritization for retention campaigns.

---

# Custom HTML/CSS/JavaScript Components

Instead of relying entirely on native Power BI visuals, custom interactive components were built using HTML, CSS, and JavaScript embedded inside Power BI.

## Custom Components Built

### Risk Tier Cards

Custom HTML/CSS KPI cards showing:

* Customer counts
* Revenue at risk
* Average tenure
* Fiber optic concentration
* Payment behavior analysis

### Top High-Risk Customers Table

A dynamically generated HTML table identifying:

* Highest-risk active customers
* Revenue-heavy churn risks
* Priority retention targets

### Interactive Customer Intelligence Table

A fully interactive customer table featuring:

* Search functionality
* Dynamic filtering
* Pagination
* Risk-level sorting
* Revenue prioritization
* Score-based visual indicators

The table was generated using:

* DAX-generated HTML
* Embedded CSS styling
* JavaScript filtering/sorting logic

---

# Time Intelligence Features

Implemented dynamic period analysis using:

* Previous Month
* 3-Month Analysis
* 6-Month Analysis
* 12-Month Analysis
* Year-to-Date (YTD)

Custom time period tables and DAX date logic were used to support trend analysis.

---

# Dashboard Features

* Dynamic KPI cards
* Churn segmentation
* Revenue-risk analysis
* Interactive filtering
* Risk-priority customer identification
* Trend analysis
* Customer behavioral analysis
* Financial impact monitoring
* Retention prioritization dashboard

---

# Dataset Information

Dataset contains:

* 7,043 telecom customers
* Customer demographics
* Service subscriptions
* Billing information
* Contract details
* Churn status
* Revenue metrics

---

# Folder Structure

```text
connecttel-churn-analysis
│
├── data
│   └── Telco_Churn.csv
│
├── dax
│   ├── Measures.txt
│   ├── Calculated_Columns.txt
│   ├── Calendar_Table.txt
│   ├── HTML_Custom_Visuals.txt
│   
│
├── screenshots
│   ├── churn_overview.png
│   └── customer_priority_list_table.png
│
├── reports
│   └── Final_Report.pdf
│
├── ConnectTel_Churn_Dashboard.pbix
└── README.md
```

---

# Key Insights

* Month-to-month customers showed the highest churn risk
* Fiber optic customers had elevated churn behavior
* Electronic check users were disproportionately represented among churned customers
* Short-tenure customers represented the most vulnerable segment
* Critical-risk customers represented significant recurring revenue exposure

---

# Project Outcome

The dashboard provides a proactive retention intelligence system that enables the business to:

* Identify high-risk customers early
* Prioritize intervention campaigns
* Reduce churn exposure
* Protect recurring revenue
* Improve retention strategy efficiency

---

# Future Improvements

Potential future enhancements include:

* Machine learning churn prediction
* SQL data warehouse integration
* Real-time streaming dashboards
* Customer lifetime value forecasting
* Automated retention recommendation engine
* Python predictive analytics integration
