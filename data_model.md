# Data Model 

This project follows a **modular, city-level analytical data model** designed to support scalable customer behaviour analysis for a food delivery platform.

Due to the absence of a unified relational database, the analysis uses **city-specific analytical datasets** generated in Python, queried using SQL (DuckDB), and consolidated for reporting and visualisation.



# Data Architecture

## 1. Source Layer

- Publicly available Foodpanda transactional dataset

- Raw data includes:

  - Orders

  - Customers

  - Restaurants

  - Ratings

  - Delivery and order status information



## 2. Python Processing Layer

For each city (Islamabad, Karachi, Lahore, Multan, Peshawar):

- Data cleaning and standardisation

- Feature engineering

- RFM metric calculation:

  - **Recency** → Time since last order

  - **Frequency** → Number of orders
  - **Monetary** → Total order value

- Customer-level analytical dataset creation 

Each city dataset functions as an **analytical fact table** at the customer–order grain.



## 3. SQL (DuckDB) Analysis Layer

City-level datasets are queried independently to generate:

- Churn metrics

- Retention proxies

- RFM-based segmentation outputs

- Demographic and feature-level breakdowns

- Restaurant-level performance metrics


## 4. Consolidation Layer

City-wise outputs are aggregated into:

- overall_churn
  
- overall_retention

- retention_by_city

This allows **cross-city comparison** while preserving local behavioural characteristics.


## 5. Reporting Layer

Final datasets are consumed in **Power BI** for:

- Churn analysis

- Retention analysis

- Operational performance monitoring

- Business insight delivery


# Why this Model Works

- Scales easily across cities

- Avoids over-aggregation bias

- Mirrors real-world marketplace analytics

- Clearly separates data engineering from insight generation
