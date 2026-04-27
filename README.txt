Beyond the Binge: Streaming Service Churn Analysis
📌 Project Overview
"Beyond the Binge" is an end-to-end data analytics project focused on identifying why customers cancel their streaming subscriptions. By analyzing customer demographics, usage patterns, and contract types, this project identifies high-risk segments and provides data-driven strategies to increase Customer Lifetime Value (CLV).

🛠️ Technical Stack: The Hybrid Workflow
This project utilizes a professional data pipeline, separating the data preparation (Python) from the visualization (Power BI):

Python (Data Engineering & ETL):

Pandas: Used for cleaning inconsistent records, handling missing values, and data type standardization.

Grouping & Aggregation: Performed advanced grouping to create "Tenure Buckets" and "Usage Tiers" to simplify the model for visualization.


Power BI (Business Intelligence):

DAX Measures: Developed custom measures for Churn Rate %, Average Revenue Per User (ARPU), and Total Lost Revenue.

Dynamic Visuals: Built an interactive dashboard with "What-If" parameters to simulate how a 5% reduction in churn would impact the bottom line.

📈 Key Insights & KPIs
Total Churn Rate: [Insert % e.g., 26.5%]

Contract Risk: Customers on Month-to-Month contracts are [X]x more likely to churn than those on Annual plans.

Payment Method Impact: High correlation between churn and "Electronic Check" payments, suggesting potential friction in the payment experience.

Tenure Sweet Spot: The highest churn occurs within the first 6 months of subscription; customers who survive past 12 months show a 70% increase in loyalty.

📊 Data Logic & Technical Notes
Data Preparation: Python was chosen for the ETL phase to ensure a repeatable and scalable cleaning process that handles large datasets more efficiently than Excel.

DAX Architecture: Instead of using calculated columns, I utilized DAX Measures to ensure the dashboard remains fast and responsive during cross-filtering.

Grouping Logic: Tenure was grouped into categories (e.g., 0-6 months, 6-12 months) in Python to allow for clearer trend visualization in Power BI.

💡 Strategic Recommendations
Incentivize Annual Plans: Offer a 10% discount to Month-to-Month users to switch to 1-year contracts, targeting the segment with the highest churn risk.

Onboarding Focus: Implement a "First 90 Days" engagement campaign (exclusive content, personalized emails) to push customers past the 6-month churn danger zone.

Payment Migration: Transition "Electronic Check" users toward Auto-pay or Credit Card options to reduce involuntary churn caused by expired or failed manual payments.