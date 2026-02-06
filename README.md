# SkyStep-Customer-Segmentation-Analysis
End-to-End Customer Segmentation Analysis using SQL, Python (K-Means), and Tableau. Features advanced outlier handling via Log Transformation to identify high-value retention risks in a dataset of 20,000+ e-commerce customers.

This project transforms raw transactional data into actionable marketing segments. By implementing a machine learning-based approach to RFM (Recency, Frequency, Monetary) analysis, I addressed the "whale outlier" problem—where a few high-spenders distort clustering results—using a Log1p Transformation.

The result: A 3-tier segmentation model that identifies "Slipping Loyalists"—customers who contribute the highest historical revenue ($1,496 avg.) but show a high risk of churn (120+ days since last purchase).
