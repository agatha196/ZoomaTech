# ZoomaTech Sales Performance Dashboard

## Overview

ZoomaTech is a growing provider of video calling solutions for small businesses. As ZoomaTech expands its presence in the business communications market, leadership has identified a growing need to evaluate sales effectiveness across customer segments, products, and individual sales reps. Prior reporting methods were decentralized and operational in nature, limiting the team’s ability to surface trends, identify inefficiencies, or make data-informed strategic decisions.

To address this gap, a centralized dashboard was developed to bring together key sales performance metrics and support quarterly reviews, rep coaching, and product focus decisions.

---

## Objective

The primary goal of this initiative is to provide leadership with a real-time, self-serve view of sales performance across the firm. The dashboard enables leadership to:

- Track sales conversion and average time to close
- Identify top-performing reps, industries, and products
- Use data to guide strategic planning, coaching, and resource allocation

---

## Dataset

### Data Sources
- **Sales Transactions** — including engage date, close date, status, product, and quantity
- **Customers** — including customer name and industry
- **Employees** — identifying the sales rep responsible
- **Products** — with pricing data
![Data Model drawio](https://github.com/user-attachments/assets/71549f47-77f4-43bc-a92b-c385cda54ec5)


### Key Metrics
- **Sales Conversion Rate** = # Won Leads / # Total Leads (based on engage date)
- **Average Days to Close** = Average time to close for **won** deals only
- **Revenue** = Quantity × Price for won opportunities
- **Segment Analysis** = Performance breakdown by industry, product, and rep

---

## Dashboard Features 
[ZoomaTech Sales Dashboard Preview](https://public.tableau.com/views/Sales_17462088266400/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

- **Filters** — by sales rep, industry, product, engage date, and close date
- **Monthly Trends** — for both conversion rate and time to close
- **Leaderboard Views** — revenue and efficiency metrics by rep and product
- **Industry Performance** — insights into customer segment effectiveness
- **Responsive Layout** — designed for executive visibility and drill-down exploration
![dashboard](https://github.com/user-attachments/assets/7cead179-df19-475d-b293-fcd712963103)

---

## Key Insights

### Sales Rep Performance
- Eli Grant and Kenzie Rhode demonstrated consistently high effectiveness, converting over 60% of their leads—well above the team average of 48%.
- In contrast, Carline Lee, Chloe Bennett, and Julie Jones converted fewer than 41% of their leads, despite handling high volumes.
- This discrepancy suggests an opportunity for targeted coaching and performance enablement.

### Industry Trends
- The Medical, Finance, and Marketing sectors had the highest conversion rates, each exceeding 64%.
- Leads categorized under “Unknown Industry” underperformed, with conversion closer to 53%, indicating potential gaps in data quality or fit.
- Prioritizing known high-performing segments could improve efficiency and revenue outcomes.

### Product Performance
- ZoomaConnect, ZoomaMeet Pro, and ZoomaWebinars accounted for the majority of closed-won revenue, performing strongly across both volume and win rate.
- Products like ZoomaRecording and ZoomaSync showed limited sales success and may require repositioning or bundling.
- The concentration of revenue in top products highlights an opportunity to streamline focus and marketing strategy.

### Time to Close
- The overall average time to close a deal was 69 days. However, some reps—including Max Harper, Chloe Bennett, and Nina Petrouf—averaged 74+ days.
- Top-performing reps closed deals in under 60 days, suggesting that best practices can be standardized across the team to accelerate cycle time.

---

## Recommendations

- ###Coach Underperforming Reps with High Lead Volume
Several reps are managing a large number of leads but converting at or below 41%, well below the firm average of 48%. Targeted coaching can help improve qualification and close rates.
- ###Prioritize High-Converting Industry Segments
The Medical, Marketing, and Finance sectors consistently convert above 64%, while the lowest-performing group lags at 53%. Focus marketing and outreach on proven verticals.
- ### Double Down on Top-Performing Products
ZoomaConnect, ZoomaMeet Pro, and ZoomaWebinars outperform other offerings in both win rate and revenue. Strategic bundling, feature expansion, or targeted promotions may increase returns further.
- ### Reduce Deal Cycle Times in Lagging Segments
While the overall average time to close is 69 days, some reps and segments exceed 74 days. Standardizing follow-up processes and adopting best practices from high performers can help accelerate deal velocity.

## Next Steps

The recommended next steps would include:

- Establishing a monthly review cadence using the dashboard during sales leadership meetings
- Rolling out targeted coaching plans for underperforming reps based on conversion rate trends
- Prioritizing marketing and outreach efforts in high-performing industry segments
- Refining CRM data hygiene practices to reduce ambiguity in “engaging” and “lost” leads
- Continuing iteration of the dashboard by adding funnel visualizations and forecast views
