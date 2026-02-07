# Metric Definitions

## Churn

A customer is considered churned if their status is marked as inactive in the dataset.
This represents customers who have stopped engaging with the platform within the observed period.


## Retention

A customer is considered retained if their status is marked as active in the dataset.
Retention is calculated directly at the customer level, ensuring accurate separation between churned and retained users.


## RFM Metrics

- **Recency:** Days since the customer's last order

- **Frequency:** Number of orders placed by the customer

- **Monetary:** Total spend across all orders



## RFM Segments

- **High RFM:** Loyal, high-value customers with strong engagement

- **Mid RFM:** Moderately engaged, price-or-convenience-sensitive users

- **Low RFM:** At-risk or low-engagement customers with hih churn likelihood

## Performance Metrics

- **AOV (Average Order Value):** Average reveue per order

- **Revenue:** Total order value across all transactions

- **Delivery Success:** Orders successfully delivered (non-cancelled)

- **Rating:** Customer feedback score (excluding cancelled orders where rating = -1)



## Notes

All metric definitions are designed to reflect real-world marketplace analytics, using customer-level churn and retention signals to ensure clarity, consistency, and business relevance.
