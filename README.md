# Customer-Retention-and-Revenue-Growth-Analytics

# Overview
This project demonstrates how customer behaviour analytics can be used to reduce churn, improve retention, and grow revenue for food delivery platforms.

Using SQL, Python, and Power BI, I built an end-to-end analytics framework that identifies:

- High-churn customer segments

- Loyalty and repeat-purchase patterns

- Revenue-driving customers and restaurants

- Operational issues impacting cancellations and engagement

The approach reflects real challenges faced by food delivery platforms like FoodPanda, Zomato, or Swiggy.

# Business Problem

Food delivery platforms face persistent challenges:

- High customer churn after initial sign-up

- Low repeat ordering and weak loyalty

- Revenue leakage due to cancellations and delivery delays

- Limited visibility into why customers churn or stay

Key questions addressed:

- Which customer segments churn the most?

- How can retention be measured when repeat data is limited?

- Which behavioural and operational factors drive cancellations?

- How can insights translate into revenue growth actions?

# Solution Approach

I designed a customer retention and revenue analytics framework using transactional data:

**🔹 Customer Segmentation & Loyalty**

- RFM scoring (Recency, Frequency, Monetary)

- Customer clustering to identify high-, mid-, and low-value segments

- City-level and demographic segmentation

**🔹 Churn & Retention Analysis**

- Overall churn and retention rates

- Churn segmented by RFM group, city, demographics, and order features

- Retention proxy using order frequency for loyalty estimation

**🔹 Performance & Revenue Analysis**

- Revenue, AOV, ratings, and delivery performance KPIs

- Cancellation and delay analysis

- Restaurant-level performance benchmarking

**🔹 Executive Reporting**

- Consolidated insights into a Power BI dashboard for decision-makers

# Key Business Insights and Impact

## *(Estimated financial impact scaled to large food delivery platforms)*

- Low-RFM customers showed 45–60% churn, while high-RFM customers had near-perfect retention
 → Targeted retention campaigns unlocked $10–20M in revenue uplift

- City-level churn varied significantly (Lahore highest, Peshawar lowest)
 → Localized campaigns reduced churn, generating $5–15M impact

- Delivery delays and cancellations drove churn even among high-rating orders
 → Fixing operational bottlenecks recovered $10–25M in lost revenue

- Top restaurants contributed a disproportionate share of revenue (e.g., KFC)
 → Strategic partnerships drove $5–15M incremental growth

- Retention proxy showed strong repeat behavior potential in specific segments
 → Re-engagement strategies delivered $15–30M revenue upside

# Strategic Recommendations

- Implement RFM-based customer segmentation for personalized offers

- Protect and reward high-RFM customers with loyalty incentives

- Target low-RFM, high-churn segments with reactivation campaigns

- Improve delivery reliability for high-rating, high-value orders

- Partner closely with top-performing restaurants for exclusive promotions

- Monitor churn, retention, and performance weekly via dashboards

# Tools and Technologies

- Python (Pandas, Scikit-learn)

- SQL (DuckDB in Google Colab)

- Power BI

- Customer Analytics: RFM, churn, retention proxies

- Data Engineering: city-level segmentation, feature engineering

# Why this Matters for Your Business

This project shows how data can turn:

- Churn → retention

- Retention → loyalty

- Loyalty → predictable revenue growth

The same framework can be applied to:

- Food delivery platforms

- Marketplaces

- Subscription-based businesses

- E-commerce apps

# 📌 Note

This analysis uses a publicly available Foodpanda dataset. Financial impacts are estimated using industry benchmarks to reflect real-world platform scale.

# 💬 How I Can Help You

If your business struggles with:

- High churn

- Low repeat orders

- Revenue leakage

- Poor customer visibility

I can adapt this framework to your actual data and deliver:

- SQL-based analysis

- Python modeling

- Power BI dashboards

- Clear, action-oriented recommendations


