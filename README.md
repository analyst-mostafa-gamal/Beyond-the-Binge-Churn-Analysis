# Beyond the Binge: Streaming Service Churn Analysis

<img width="1302" height="732" alt="Screenshot 2026-04-27 221728" src="https://github.com/user-attachments/assets/7dad93ad-1658-443e-b338-f979d05095ed" />

## 📌 Project Overview
"Beyond the Binge" is an end-to-end data analytics project focused on identifying why customers cancel their streaming subscriptions. By analyzing customer demographics, usage patterns, and contract types, this project identifies high-risk segments and provides data-driven strategies to increase Customer Lifetime Value (CLV).

## 🛠️ Technical Stack: The Hybrid Workflow
This project utilizes a professional data pipeline, separating the data preparation (Python) from the visualization (Power BI):

**Python (Data Engineering & ETL):**

- **Pandas:** Used for cleaning inconsistent records, handling missing values, and data type standardization.

- **Grouping & Aggregation:** Performed advanced grouping to create "Tenure Buckets" and "Usage Tiers" to simplify the model for visualization.


**Power BI (Business Intelligence):**

- **DAX Measures:** Developed custom measures for Churn Rate %, Average Revenue Per User (ARPU), and Total Lost Revenue.

- **Dynamic Visuals:** Built an interactive dashboard with "What-If" parameters to simulate how a 5% reduction in churn would impact the bottom line.


## 📊 Data Logic & Technical Notes
- **Data Preparation:** Python was chosen for the ETL phase to ensure a repeatable and scalable cleaning process that handles large datasets more efficiently than Excel.

- **DAX Architecture:** Instead of using calculated columns, I utilized DAX Measures to ensure the dashboard remains fast and responsive during cross-filtering.

- **Grouping Logic:** Tenure was grouped into categories (e.g., 0-6 months, 6-12 months) in Python to allow for clearer trend visualization in Power BI.

### Business Case & Executive Summary

## 📈 Key Performance Indicators (KPIs)
These represent the "Health Check" of the platform:

**Total Subscribers:** 8,579

**Monthly Revenue:** €395.39K

**Retention Rate:** 85.17% (Demonstrating high core loyalty)

**Churn Rate:** 14.83% (The primary target for business optimization)

**Average Revenue Per User (ARPU):** €46.09

**Ad Spend Efficiency (ROAS):** €220.69

## 🔍 Key Business Insights
**The "Prime Time" Window:** 45% of platform traffic peaks during **Evening hours** (reaching ~4.7K concurrent users). This is the critical window for content drops and push notifications.

**Acquisition Quality vs. Volume:** While **PPC (Pay-Per-Click)** brings in the highest volume of users (1,816), **Referral** and **SEO** channels provide better long-term conversion stability and higher quality users.

**The "Cash Cow" Plan:** The **Standard Plan** is the backbone of the platform’s economy, contributing **34.56%** of total revenue.

**Device Preference:** **Smart TVs** are the dominant device for long-form viewing, suggesting that UI/UX improvements should be prioritized for television apps.

**Retention Profitability:** Insights prove that **Retention-based campaigns** yield the highest ROI (€222.31), confirming that it is significantly more cost-effective to keep an existing user than to acquire a new one.

## 💡 Strategic Recommendations
To move the platform from "Volume Acquisition" to "Value Retention," I propose the following actions:

**Optimize for High-Value Devices:** Enhance the UI/UX specifically for **Smart TVs**, as this is where the most profitable and engaged users spend their time.

**Tier Upselling Strategy:** Use personalized content recommendations to target **"Basic Plan"** users and incentivize upgrades to the **Standard Plan** (the platform's highest revenue driver).

**Realignment of Marketing Spend:** Reallocate **10% of the current marketing budget** from "Awareness" (top-of-funnel) to "Retention" (bottom-of-funnel) to maximize the Return on Ad Spend (ROAS).

**Engagement-Based Retention:** Implement automated push notifications for **"Low Engagement"** users during the afternoon to "prime" them for the Evening peak usage window.

**Feature Adoption:** Increase awareness of the **"Download" feature** for mobile users within their first 30 days, as data suggests a high correlation between feature usage and long-term retention.
