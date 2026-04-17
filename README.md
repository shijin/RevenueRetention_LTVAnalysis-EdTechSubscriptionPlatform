# Revenue Retention & LTV Analysis - Ed-Tech Subscription Platform

## Product Analytics Case Study

### Overview

This case study analyzes 4 years and 10 months of real subscription data from an online ed-tech platform (IDALS), focusing on revenue retention, customer lifetime value (LTV), and repeat purchase behavior.

The goal of this analysis is not just to explore data, but to derive product and business insights that can inform retention, pricing, and growth decisions.

### Dataset Summary

- Total paid transactions: 2,016
- Unique customers: 1,401
- Repeat customers: 306
- Time span: Over 4 years (maximum customer age: 53 months)

Each row in the dataset represents a completed paid subscription and includes:

- Purchase date
- Plan and duration
- Fee
- Nationality (National / International)
- Customer identifier (Email ID)
- Location

### Key Questions Explored

1. How does revenue behave after a customer’s first purchase?
2. How much value do repeat customers generate compared to one-time buyers?
3. Is revenue concentrated among a small group of users?
4. Do different customer cohorts age differently over time?
5. What product strategies could improve long-term revenue?

### Key Insights
**1. Revenue is Front-Loaded, but Long-Term Value Exists**

Most revenue is generated at the time of first purchase, which is expected for an education subscription model.
However, revenue does not drop to zero. A small but consistent group of users continues to generate revenue for several years, creating a long tail of lifetime value.

**2. Repeat Customers Drive Disproportionate Value**

Although only 326 customers purchased more than once, they contributed 46% of total revenue.
- One-Time Buyers (1,075 users):
  - 54% of revenue
  - Lowest revenue per customer
- Repeat Buyers (204 users):
  - ~20% of revenue
  - Nearly double the average lifetime value
- High-Value Buyers (122 users):
  - 26% of revenue
  - Highest lifetime value per customer

This highlights the strong impact of retention and repeat purchases on business outcomes.

**3. Early Engagement Matters Most**

Most repeat purchases happen within the first few months after the initial purchase.
This suggests that early lifecycle experience plays a critical role in determining long-term value.

**4. Cohort Behavior Varies**

Cohort analysis shows that some customer groups continue to generate revenue even 40–50 months after joining, while others plateau much earlier.
This indicates differences in customer quality, engagement, or product experience across time.

### Product & Strategy Takeaways

- Improving second-purchase conversion has the highest leverage on revenue.
- Retention-focused initiatives may deliver better returns than acquisition alone.
- High-value users should be actively retained and rewarded.
- Predictive signals can be used to identify customers likely to repeat and trigger targeted interventions.

### Data Privacy and Anonymization

To protect user privacy, the dataset shared in this repository has been partially anonymized.

Personally identifiable information such as customer names and phone numbers has been removed. Email IDs are retained only as a unique identifier to accurately track repeat purchases and customer-level behavior, which is essential for retention and lifetime value analysis.

No sensitive personal data is included, and the dataset is used solely for analytical and educational purposes.

The analysis focuses on aggregate patterns and trends rather than individual user behavior.

### Tools Used

- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook

### Author
Shijin Ramesh  
[LinkedIn](https://www.linkedin.com/in/shijinramesh/) | [Portfolio](https://www.shijinramesh.co.in/)
