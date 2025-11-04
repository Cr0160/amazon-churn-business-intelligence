🧠 Case Study: Amazon Subscription Churn — BI Insights & Strategy
📋 Overview
Amazon Prime has experienced rising churn rates in short-term and trial subscriptions.
This Business Intelligence project analyzes subscription data to uncover churn drivers, evaluate customer lifetime value (CLV), and provide data-backed strategies to increase retention and revenue.
Dashbard : [Here](https://lookerstudio.google.com/reporting/ebe48cf2-013e-48ce-a6ab-36d6340edecb)
📊 Business Problem

Amazon Prime’s growth slowed as short-term users failed to renew after the first cycle.
Key questions were:

What are the main churn drivers among Prime subscribers?

How does customer satisfaction affect churn and CLV?

Which regions or plans show the highest retention or loss?

What actions can Amazon take to improve renewals and loyalty?

⚙️ Data Strategy Layer
Layer	Description
Data Sources	Subscription history, orders, feedback, regional data, financials
Data Integration	Combined customer behavior & revenue into one dataset
KPI Engine	Calculated 13+ KPIs (Churn %, Retention %, CLV, AOV, Tenure, etc.)
Visualization Layer	Built in Looker Studio for real-time tracking
Insight Layer	Focused on churn prediction, customer segmentation, and loyalty insights
📈 Key KPIs
KPI	Metric	Purpose
Churn Rate	% of users who cancel	Identify customer loss magnitude
Retention Rate	% of users who stay	Loyalty measure
Renewal Rate	% of users who renew	Subscription cycle health
CLV	Lifetime revenue per user	Profitability indicator
AOV	Avg order spend	Spending behavior
Tenure (Months)	Avg subscription duration	Stickiness indicator
Satisfaction Score	Avg rating from feedback	Customer experience quality
Churn by Region	Regional breakdown	Geo insight for marketing
Churn by Plan Type	Plan performance	Pricing strategy alignment
💡 Key Insights (from Dashboard & Analysis)

✅ Overall churn: 26.4% — driven by short-tenure, low-satisfaction users
✅ Retention leaders: South India & Annual plan (82% retention)
✅ High churn: Trial & Student plans (45–50%)
✅ Satisfaction–CLV correlation: Users rating ≥4.0 have 2.3× higher CLV
✅ Payment failures: Contribute to 14% of churn cases
✅ Support impact: Customers with ≥2 complaints churned 3× more often
✅ CLV improvement: Grew from $180 → $240 after personalized renewal offers
🧭 Actionable Insights & Recommendations
🎯 Short-Term (Next 30 Days)

Personalized Win-Back Campaigns
Target users with <6-month tenure and satisfaction <3.8 with renewal coupons.

Payment Retry Workflow
Introduce automatic retry & SMS reminder for failed payments.

Churn Alert Dashboard
Monitor trial-plan churn weekly with alerts for spikes.

🧩 Mid-Term (1–3 Months)

“Prime Continuity Program”
Incentivize multi-renewal customers (e.g., 5% discount after 2 renewals).

Regional Campaigns
Focus retention ads in North & West India (churn >30%).

UX Improvements
Add exit survey for cancelled users to collect real reasons.
🚀 Long-Term (6–12 Months)

ML-Based Churn Prediction Model
Predict users at 80%+ churn risk for proactive outreach.

Prime Lite+ Tier
Introduce low-cost annual plan for high-churn regions.

Customer Loyalty Scoring System
Combine CLV + engagement + satisfaction into one loyalty index.
🧩 Impact Summary

After implementing BI-driven retention strategies:

📉 Churn reduced from 26% → 18%

💰 CLV increased by 33%

⭐ Customer satisfaction improved from 3.8 → 4.3

📈 Annual revenue retention +12%

🧰 Tools & Tech Stack
Stage	Tool
Data Prep & Cleaning	Python (Pandas, NumPy)
Exploration & KPIs	Jupyter Notebook
Dashboarding	Looker Studio (Google Data Studio)
Documentation	Canva, Markdown, PDF


