# E-commerce Customer Segmentation (RFM Analysis & K-Means)

## Objective
The goal of this project is to apply clustering algorithms to segment an e-commerce company's customer base into distinct groups based on their purchasing behavior (Recency, Frequency, Monetary value). This enables targeted and efficient marketing strategies.

## Tech Stack
- Python (Pandas, NumPy)
- Scikit-learn (K-Means, StandardScaler)
- Matplotlib & Seaborn

## Key Insights & Marketing Recommendations
Based on the K-Means clustering (K=3), we identified three distinct customer segments:

1. **Cluster 2 (The VIPs / Whales):**
   - **Profile:** Smallest group (only 18 customers) but with massive spending and high frequency. They purchased recently.
   - **Recommendation:** Assign dedicated account managers, enroll them in exclusive loyalty programs, and provide premium support to ensure retention.

2. **Cluster 1 (The Regulars):**
   - **Profile:** The largest active segment (approx. 3,848 customers). They buy consistently with moderate spending.
   - **Recommendation:** Implement upselling and cross-selling campaigns. Offer volume-based discounts to increase their average order value.

3. **Cluster 0 (The Churned / At-Risk):**
   - **Profile:** Customers who haven't purchased in over a year (avg. 461 days) with low spending and frequency.
   - **Recommendation:** Launch aggressive re-engagement campaigns. Send personalized "We Miss You" emails containing high-value discount codes for their next purchase.
