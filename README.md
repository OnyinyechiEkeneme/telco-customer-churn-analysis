# ConnectTel Customer Churn Analysis Dashboard

## Dashboard Preview

<img width="571" height="320" alt="Churn_overview png" src="https://github.com/user-attachments/assets/1c4aad4e-2a5e-4887-990b-eaf1258694ab" />

<img width="678" height="375" alt="Priority_list" src="https://github.com/user-attachments/assets/bd31190f-602f-4c49-9d12-ce209e27b2f7" />

# Executive Summary

ConnectTel experienced a customer churn rate of 26.5%, creating major recurring revenue loss.
This project developed an advanced Power BI churn intelligence dashboard that identified high-risk customers, quantified revenue exposure, and enabled proactive retention prioritization using DAX-based risk scoring and custom HTML-powered customer intelligence visuals.

# Business Problem

ConnectTel was losing customers at an increasing rate, impacting monthly recurring revenue and customer lifetime value.

The company lacked:

- visibility into churn drivers
- proactive retention systems
- customer risk prioritization
- revenue exposure tracking

The retention team only reacted after churn occurred, leading to inefficient intervention strategies and increased acquisition costs.

# Project Objectives

The project aimed to:

- Identify the customers most likely to churn
- Understand key churn drivers
- Quantify monthly revenue loss
- Create a customer risk segmentation framework
- Build an interactive retention intelligence dashboard
- Enable prioritization of high-risk customers

# Dataset Overview

The dataset contains 7,043 telecom customers and includes:

- Customer demographics
- Service subscriptions
- Contract types
- Billing information
- Payment methods
- Monthly charges
- Churn status
- Customer tenure

# Methodology

## Data Preparation
- Cleaned missing values
- Standardized categorical fields
- Created transformation logic in Power Query

## Data Modeling
- Built star-schema relationships
- Created custom calendar table
- Developed advanced DAX measures

## Risk Modeling
- Built a custom churn risk scoring framework
- Classified customers into:
  - Critical
  - High
  - Medium
  - Low

## Dashboard Design
- Built dynamic KPI cards
- Added time-intelligence analysis
- Created interactive HTML customer tables

# Key Business Insights

## Insight 1 — Month-to-Month Contracts Drive Churn

Customers on month-to-month contracts represented the largest share of churned customers.

### Why It Matters
Short-term contracts reduce customer commitment and increase switching behavior.

### Recommendation
Introduce loyalty incentives or discounted annual contract upgrades for high-risk customers.

# Recommendations

## Immediate Actions
- Prioritize critical-risk customers
- Target month-to-month contracts
- Reduce churn among high-value customers

## Medium-Term Actions
- Improve onboarding
- Promote auto-pay adoption
- Improve tech support accessibility

## Long-Term Actions
- Build ML churn prediction models
- Develop automated retention systems
- Implement real-time monitoring

# Business Outcome

The dashboard transformed churn analysis from reactive reporting into a proactive retention intelligence system.

The solution enables:

- earlier churn detection
- better customer prioritization
- improved revenue protection
- data-driven retention decision-making
