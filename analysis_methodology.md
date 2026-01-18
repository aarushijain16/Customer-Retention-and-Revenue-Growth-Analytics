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

As explicit churn labels were unavailable:

- Churn defined using customer inactivity thresholds

- Churn rates analysed across:

  - Demographics

  - RFM segments

  - Cities

  - Delivery and rating features



# Step 4: Retention Proxy

Retention was approximated using:

- Order frequency

- Repeat purchase behaviour within the observation window

This mirrors real-world scenarios where perfect lifecycle data is unavailable.

# Step 5: Performance Analysis

Operational metrics analysed include:

- Revenue

- Average Order Value (AOV)

- Ratings

- Delivery success

- Restaurant-level performance



# Step 6: Insight Synthesis

All analytical outputs were translated into:

- Business insights

- Segment-level strategies

- Actionable recommendations
