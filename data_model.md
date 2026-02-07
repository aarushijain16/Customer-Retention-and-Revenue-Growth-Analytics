# Data Model 

This project follows a **modular, city-level analytical data model** designed to support scalable customer behaviour analysis for a food delivery platform.

The analysis uses Python for data preparation and feature engineering, a centralized PostgreSQL analytical table for SQL-based analysis, and Power BI for real-time reporting and visualisation.


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

Using Python, the raw dataset is processed to create a unified analytical dataset:

- Data cleaning and standardisation

- Feature engineering

- RFM metric calculation:

  - **Recency** → Time since last order

  - **Frequency** → Number of orders
    
  - **Monetary** → Total order value

- Customer-level analytical revords are created at the customer-order grain, covering all cities:

   - Islamabad
 
   - Lahore
 
   - Karachi
 
   - Multan
 
   - Peshawar

This step produces a clean, analysis-ready dataset with consistent schema across cities.



## 3. SQL (PostgreSQL) Analysis Layer

The processed dataset is stored in a PostgreSQL database and queried using SQL to generate:

- Churn metrics

- Retention metrics

- RFM-based segmentation outputs

- Demographic and feature-level breakdowns

- Restaurant-level performance metrics

Customer churn and retention are calculated directly using customer status, ensuring accurate customer-level analysis.

## 4. Consolidation Layer

All city-level and segment-level metrics are derived from the centralized analytical table, enabling:

- Croos-city comparisons

- Consistent churn and retention calculations

- Relaiable aggregation across segments

This approach preserves local behavioural patterns while supporting platforms-wide insights.


## 5. Reporting Layer

The PostgreSQL analytical table is connected to Power BI in real time for:

- Churn analysis

- Retention analysis

- Operational performance monitoring

- Business insight delivery

Dashboards refresh automatically as new data is appended to the database.

# Why this Model Works

- Scales easily across cities

- Maintains customer-level accuracy

- Avoids over-aggregation bias

- Mirrors real-world marketplace analytics pipelines

- Supports real-time monitoring and decision-making
