# Analysis Methodology

This project applies a **customer-centric analytics framework** to understand churn, retention, and revenue behaviour in food delivery platforms.


# Step 1: Data Preparation

- Removed duplicates and inconsistencies

- Standardised date formats and categorical values

- Handled missing values and outliers

- Ensured schema consistency across cities



# Step 2: RFM Analysis

RFM (Recency, Frequency, Monetary) scoring was used to quantify customer value and engagement.

- Customers scored on a 1–5 scale per dimension

- Combined RFM scores used for behavioural segmentation

- K-Means clustering applied to identify customer groups

**Why RFM?**

- Interpretable for business stakeholders

- Effective when lifecycle data is limited

- Directly links behaviour to revenue



# Step 3: Churn Analysis

Churn was analysed using an explicit customer churn flag dervied from platform activity status.


- Churn rates analysed across:

  - Demographics

  - RFM segments

  - Cities

  - Delivery and rating features

This enabled preciseidentification of churned vs retained customers at a customer level.

# Step 4: Retention Measurement

Retention was measured directly using retained customer status.

- Retention analysed across:

  - RFM segments
 
  - Demographics
 
  - Cities
 
  - Order and delivery features

This reflects realistic business scenarios where retention is tracked throuh customer activity rather than perfect lifecycle data.

# Step 5: Performance Analysis

Operational and revenue metrics analysed include:

- Revenue

- Average Order Value (AOV)

- Ratings

- Delivery success, delays and cancellations

- Restaurant-level performance

Customer-level churn and retention metrics were linked with operational KPIs to identify revenue leakage drivers.


# Step 6: Insight Synthesis

All analytical outputs were translated into:

- Business insights

- Segment-level strategies

- Actionable recommendations

Insights were consolidated into a real-time Power BI dashboard connected to a PostgreSQL backend, enabling continuous monitoring and decision-making.
