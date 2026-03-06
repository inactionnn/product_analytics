# Retail Sales Analytics Project

## Project Overview

This project presents a comprehensive analysis of an online retail dataset, demonstrating advanced product analytics skills. The analysis covers the full spectrum of data-driven decision making: from data quality assessment to predictive modeling and strategic recommendations.

The dataset contains transactional data from a UK-based online retailer, including information about customers, products, transactions, and geographic distribution. The analysis focuses on understanding customer behavior, identifying growth opportunities, and providing actionable business insights.

## Dataset Description

The dataset includes:
- 541,909 transactions
- 4,334 unique customers
- Data range: December 2010 to December 2011
- 38 countries represented
- Key fields: Invoice numbers, stock codes, product descriptions, quantities, invoice dates, unit prices, customer IDs, and countries

## Analysis Structure

### 1. Data Quality Assessment

The initial phase focuses on understanding data completeness and reliability:
- Identification of missing values in CustomerID and Description fields
- Detection of duplicate records
- Handling of negative quantities and prices (returns/cancellations)
- Data type verification and conversion

### 2. Revenue Metrics Analysis

Core business metrics calculation and visualization:
- Total revenue, transaction volume, and customer counts
- Average order value trends
- Revenue distribution by country and product
- Monthly and daily revenue patterns

<img width="1487" height="990" alt="image" src="https://github.com/user-attachments/assets/4c911e32-ffc1-40b0-9b36-3acf289d15fb" />


### 3. Customer Purchase Behavior

Analysis of customer purchasing patterns:
- Classification of customers by purchase frequency
- Revenue contribution by customer type
- Identification of one-time vs repeat customers

<img width="1305" height="590" alt="image" src="https://github.com/user-attachments/assets/10034695-d058-4a12-8051-85f27e7d69e8" />


### 4. Cohort Analysis & Retention

Longitudinal analysis of customer retention:
- Monthly cohort tracking
- Retention rate calculation
- Customer loyalty patterns over time

<img width="923" height="490" alt="image" src="https://github.com/user-attachments/assets/e0535d84-0d52-4061-9f2a-dd641545503b" />


### 5. RFM Segmentation

Customer segmentation based on:
- Recency: Days since last purchase
- Frequency: Number of transactions
- Monetary: Total spend

<img width="284" height="170" alt="image" src="https://github.com/user-attachments/assets/446cb0b0-1a42-46f2-897e-ae7ae17c2646" />

Five distinct segments identified:
- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Lost


### 6. Machine Learning Clustering

Unsupervised learning approach to customer segmentation:
- K-Means clustering on RFM metrics
- Optimal cluster determination using elbow method and silhouette scores
- Comparison with rule-based RFM segmentation

<img width="1490" height="1189" alt="image" src="https://github.com/user-attachments/assets/ae85b990-53a6-49ea-a2fb-4a013db85118" />

### 7. Sales Forecasting

Time series prediction using Facebook Prophet:
- Daily sales pattern analysis
- 30-day sales forecast with confidence intervals
- Seasonality decomposition
- Model accuracy metrics

<img width="1386" height="590" alt="image" src="https://github.com/user-attachments/assets/a3826286-5620-4e9b-9016-19c1366f6122" />

<img width="1389" height="590" alt="image" src="https://github.com/user-attachments/assets/d9a5e40d-31e9-4c60-ac95-4bed88e5cdd6" />


## Key Findings

### Revenue & Customer Metrics
- Total Revenue: $8.7M from 22k+ transactions
- Average Order Value: $396
- Repeat Customer Rate: 37.5%
- Average Monthly Active Customers: 865

### Customer Segmentation
1. **Champions (12% of customers)** : Generate 45% of revenue
2. **Loyal Customers (18%)** : 30% of revenue
3. **Potential Loyalists (25%)** : 15% of revenue
4. **At Risk (20%)** : 7% of revenue
5. **Lost (25%)** : 3% of revenue

### Geographic Distribution
- UK dominates with 82% of revenue
- Top international markets: Netherlands, Germany, France
- Significant growth potential in European markets

### Seasonal Patterns
- Peak sales in November (pre-Christmas)
- Weekly patterns show higher activity on weekdays
- Clear yearly seasonality with Q4 spikes

## Business Recommendations

### Customer Strategy

**Champions:**
- Implement VIP loyalty program with exclusive benefits
- Create referral program to acquire similar high-value customers
- Invite to product testing and feedback sessions

**Loyal Customers:**
- Develop upsell and cross-sell campaigns
- Create product bundles at slightly discounted prices
- Offer loyalty points for future purchases

**Potential Loyalists:**
- Encourage second purchase with targeted 10-15% discounts
- Showcase popular products in their preferred categories
- Send educational content about product features

**At Risk Customers:**
- Launch win-back campaigns with special offers
- Conduct surveys to understand reduced engagement
- Send personalized product recommendations

**Lost Customers:**
- Create re-engagement email series with strong incentives
- Analyze common characteristics to prevent future churn
- Consider one final reactivation attempt before archive

### Product & Marketing Strategy

1. **Product Focus**
   - Concentrate marketing budget on top 5 revenue-generating products
   - Bundle slow-moving items with bestsellers
   - Implement stock alerts for high-demand products

2. **Geographic Expansion**
   - Strengthen presence in top 3 international markets
   - Analyze shipping optimization for European customers
   - Consider local currency pricing for key markets

3. **Marketing Optimization**
   - 40% budget to Champions and Loyal Customers retention
   - 30% to converting Potential Loyalists
   - 20% to win-back campaigns
   - 10% to reactivation campaigns

4. **Timing Optimization**
   - Schedule campaigns based on peak purchase hours
   - Plan promotions around monthly active customer peaks
   - Prepare inventory for seasonal spikes


### Next Steps & Future Work

1. Implement A/B testing for recommended discount levels
2. Implement personalized recommendation engine
3. Develop automated reporting pipeline
4. Integrate marketing source tracking


## Conclusion

This analysis demonstrates comprehensive product analytics capabilities including:
- Data quality assessment and cleaning
- Core business metrics calculation
- Customer segmentation (both rule-based and ML)
- Cohort analysis and retention tracking
- Time series forecasting
- Strategic business recommendations

The project showcases the ability to derive actionable insights from raw data and communicate findings effectively to stakeholders.
