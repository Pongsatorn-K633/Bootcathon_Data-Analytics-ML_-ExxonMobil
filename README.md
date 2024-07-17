# Hyperlube ExxonMobil

## Dashboard 
### RFM Analysis Dashboard
![RFM_White](https://github.com/user-attachments/assets/cd44e8a7-5fb3-464d-a798-63f445094a29)

The Retail RFM (Recency, Frequency, Monetary) Analysis Dashboard evaluates the retail/resale performance based on recency of transactions, frequency of purchases, and monetary value, helping to understand customer behavior and segment the shops accordingly.

Key Components:

Metrics:

Amount of Liter: 49M liters of lubricant sold.
Amount of Retail/Resale: 637 retail/resale transactions.
Amount of Transactions: 9429 total transactions.
Amount of Points in System: 25K points accumulated in the loyalty system.
Filters:

Segment: Filter by different customer segments.
Month: Filter transactions by month.
Province: Filter by geographic province.
Distributor: Filter by different distributors.
Visualizations:

Segment of Retail/Resale: Bar chart showing the proportion of low-value (57.30%), mid-value (31.87%), and high-value (10.83%) segments.
Factor that Affects Segmentation: Scatter plot illustrating the relationship between recency and frequency for high-value, mid-value, and low-value segments.
Map of Distributors: Displays the geographical distribution of shops by different distributors (A, B, C, D).
Shop Rankings:

Shop Ranking by Frequency: Bar chart ranking shops based on the count of transactions (NaNo).
Shop Ranking by Volume: Bar chart ranking shops based on the volume of lubricant purchased.
Shop Ranking by Points: Bar chart ranking shops based on the points accumulated per liter-point.
Shop Details Table:

Lists Group ID, latest order date, and datediff (days since the last order), highlighting the recency of each shop's last transaction.

### Churn Prediction Dashboard
![Churn_White](https://github.com/user-attachments/assets/76276069-78d4-4c3c-9323-6b1e942af2f4)

The Retail/Resale Churn Prediction Dashboard aims to identify shops at risk of discontinuing their purchases in the future, allowing the business to take proactive measures such as targeted promotions to retain these customers.

Key Components:

Churn Status Definition:

True: Indicates shops that have a high chance of not buying in the future. Recommended to send promotions to these shops.
False: Indicates shops that frequently buy the lubricant, considered good shops.
Metrics:

Estimated Volume Lost: 13M liters, representing the potential volume lost if the at-risk shops churn.
Amount of Risk Shops: 141 shops identified as high-risk for churn.
Filters:

Segment: Allows filtering by different customer segments.
Distributor: Filter by different distributors.
Province: Filter by geographic province.
Visualizations:

Map of Distributors: Displays the geographical distribution of shops by different distributors (A, B, C, D).
Status Segmentation Pie Chart: Shows the proportion of shops at risk (True) vs. good shops (False). Currently, 22.14% of shops are at risk (141 shops), while 77.86% are good shops (496 shops).
Shop Details Table:

Lists Group ID, Segment, and Churn Status for each shop, highlighting those at risk (True) and those not at risk (False).
