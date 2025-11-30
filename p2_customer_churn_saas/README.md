# Project Title: SaaS Churn Analysis & Insights
A complete, client-ready exploratory data analysis (EDA) of a SaaS churn dataset.<br><br>

## Business Problem Statement
A SaaS company wants to understand why customers are leaving (churning) and what factors drive churn. The goal is to:
- Identify high-risk customer groups
- Extract actionable business insights
- Provide recommendations to reduce churn <br><br>

## Dataset Description
The dataset spans 5 CSV files:
1. accounts.csv – customer metadata
2. subscriptions.csv – subscription lifecycles and revenue
3. feature_usage.csv – daily product interaction logs
4. support_tickets.csv – support activity and satisfaction scores
5. churn_events.csv – churn dates, reasons, and refund behaviors

**Kaggle Link of Dataset:** https://www.kaggle.com/datasets/rivalytics/saas-subscription-and-churn-analytics-dataset


## Key insights
1. Most customers stay, but **churn rate is significant (~22%)**
2. **Customers from DevTools industry churn the most-** Indicates dissatisfaction in DevTools industry customer.
3. **Churning is higher for customers who are sourced through event-** Risky customer segment.
4. **For enterprise customer the churing is proportionally higher-** Indicates dissatisfaction.
5. **Customers with low no. of seats churn at a higher rate-** Upgrade of seats with small upgrade amount may help in reducing the churn.
6. **High pricing a key reason of churing-** A cheap budget plan or a discount may help.
7. **Churning is low where initial response time is low-** Quick response for support call may reduce the churn. 

## Recommendations
1. **Improve first-month onboarding-** Reduce early churn by targeted onboarding for new customers.
2. **Incentivize longer contracts-** Offer discounts or benefits for 1-year or 2-year contracts.
3. **Review fiber optic customer experience-** Investigate speed, downtime, or service quality issues.
4. **Promote autopay / credit card payments-** Electronic check customers are high-risk.
5. **Introduce service bundles-** Security + tech support bundles can increase retention.

## Visual sample charts
Links to be added

## How to run the notebook/script
Place dataset (.csv) files in ../data folder. Then run the notebook file.
