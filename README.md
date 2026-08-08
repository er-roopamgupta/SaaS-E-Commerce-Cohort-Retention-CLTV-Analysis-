SaaS & E-Commerce Cohort Retention & CLTV Analysis
Executive Summary
Acquiring new customers costs up to five times more than retaining existing ones. This project performs an end-to-end cohort analysis on transactional data to identify user retention decay patterns, compute Customer Lifetime Value (CLTV), and deliver data-backed recommendations to minimize early churn.

Technical Stack & Skills
Language: Python 3.x

Data Processing: Pandas, NumPy

Data Visualization: Seaborn, Matplotlib

Database & Querying: SQL (Aggregation, Window Functions)

Analytics Concepts: Cohort Analysis, Retention Decay, CLTV, AOV, Purchase Frequency

Project Architecture & Roadmap
Week 1: Data Cleaning & Wrangling
Cleaned raw transactional logs by filtering out refunded, cancelled, and failed transactions.

Handled null/missing User ID values and formatted purchase timestamps.

Calculated the Cohort Month (the month of a user's initial transaction) for each unique customer.

Week 2: Cohort Retention Matrix
Utilized Pandas groupby() and pivot_table() to generate a relative cohort retention matrix.

Computed absolute user counts and retention percentages across cohort indices (Month 0 through Month 6).

Week 3: Customer Lifetime Value (CLTV) Calculation
Segmented cohorts across acquisition channels (e.g., Google Ads, Organic Search, Amazon) and regions.

Calculated Average Order Value (AOV) and Purchase Frequency per segment.

Modeled historical CLTV to measure long-term user revenue contribution.

Week 4: Visualization & Strategic Insights
Visualized retention matrices using Seaborn heatmap annotations and decay line plots.

Built revenue breakdown charts by acquisition channel.

Key Findings & Strategic Insights
1. The Month-1 Retention Drop
Observation: On average, user retention drops steeply from 100% to ~44% in Month 1 (a 56% churn rate immediately after the initial purchase).

Business Impact: High early drop-off indicates friction during initial onboarding or a lack of post-purchase engagement.

Recommendation: Implement an automated onboarding email flow and issue time-sensitive discount triggers 14 days post-purchase to drive a second transaction.

2. Acquisition Channel Performance
Observation: Google Ads, Amazon, and Organic Search generated the highest overall revenue (~$1.4M+ each), while Email and YouTube trailed behind (~$1.05M).


Strategic Business Implications & Recommendations
1. Addressing Early Onboarding Drop-Off
Finding: Retention drops significantly within the first month (e.g., dropping by over 50% from Month 0 to Month 1).

Business Impact: The company loses the majority of newly acquired users before they experience long-term product value, leading to high Customer Acquisition Cost (CAC) inefficiency.

2. Optimizing Marketing Budget Across Acquisition Channels
Finding: High-volume channels like Google Ads and Amazon drive the majority of top-line revenue, whereas email and video channels show lower conversion density.

Business Impact: Over-allocating ad spend to lower-performing channels yields lower Lifetime Value (LTV) relative to acquisition cost.

Actionable Recommendation: Reallocate marketing budget toward top-tier acquisition channels (Google Ads and Organic Search optimization) while setting up targeted re-engagement campaigns for email cohorts.

Recommendation: Reallocate ad spend toward high-performing channels (Google Ads) and re-evaluate YouTube targeting or creative messaging.


3. Mitigating Long-Term Churn (Months 3 to 6)
Finding: Retention decay approaches zero by Month 6 across nearly all cohorts.

Business Impact: High churn in later months prevents stable recurring revenue and reduces long-term Customer Lifetime Value (CLTV).

Actionable Recommendation: Introduce a loyalty/subscription program or recurring replenishment incentives prior to Month 3 to lock in repeat customer commitments before decay sets in.

Recommendation: Introduce a loyalty/subscription program prior to Month 3 to lock in recurring repeat buyers.
