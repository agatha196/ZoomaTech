# ZoomaTech Sales Performance Dashboard

## Overview

ZoomaTech is a growing provider of video calling solutions for small businesses. As ZoomaTech expands its presence in the business communications market, leadership has identified a growing need to evaluate sales effectiveness across customer segments, products, and individual sales reps. Prior reporting methods were decentralized and operational in nature, limiting the team’s ability to surface trends, identify inefficiencies, or make data-informed strategic decisions.

To address this gap, a centralized dashboard was developed to bring together key sales performance metrics and support quarterly reviews, rep coaching, and product focus decisions.

---

## Objective

The primary goal of this initiative is to provide leadership with a real-time, self-serve view of sales performance across the company. The dashboard enables leadership to:

- Track sales conversion and average time to close
- Identify top-performing reps, industries, and products
- Use data to guide strategic planning, coaching, and resource allocation

---

## Dataset

### Data Sources
The data model below is sourced from the CRM and includes engaged sales activity from the past 12 months (July 2024 to May 2025).
- **Customers** — unique list of all customers
- **Sales** — all leads in the pipeline, including key fields such as engage date, close date, status, product, and quantity.
- **Products** — unique list of all products with pricing
  
![Data Model drawio](https://github.com/user-attachments/assets/71549f47-77f4-43bc-a92b-c385cda54ec5)


### Key Metrics
- **Sales Conversion Rate** = # Won Leads / # Total Leads (based on engage date). The percentage of engaged leads that were successfully closed.
- **Average Days to Close** = Average time to close for **won** deals only. Measures the average number of days it took to close won deals, from engagement to deal closure.
- **Revenue** = Quantity × Price. Total revenue generated from won opportunities.

---

## Dashboard Features 
[ZoomaTech Sales Dashboard](https://public.tableau.com/views/Sales_17462088266400/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

- **Filters** — by industry, sales rep, product
- **Monthly Trends** — for both conversion rate and time to close
- **Leaderboard Views** — revenue and efficiency metrics by rep and product
- **Industry Performance** — insights into customer segment effectiveness
- **Responsive Layout** — designed for executive visibility and drill-down exploration
  
![dashboard](https://github.com/user-attachments/assets/7cead179-df19-475d-b293-fcd712963103)

---

## Key Insights

### Sales Rep Performance
- Jake Linwood and Zara Almasi demonstrated consistently high effectiveness, converting over 59% of their leads — well above the team average of 48%.
- In contrast, Carrie Reese and Jasmine Rowe converted 41% of their leads, despite handling high volumes.
- This discrepancy suggests an opportunity for targeted coaching and performance enablement.

### Industry Trends
- The Medical and Entertainment industries had the highest conversion rates, each exceeding 64%.
- Leads categorized under “Unknown Industry” underperformed, with conversion closer to 53%, indicating potential gaps in data quality or fit.
- Prioritizing known high-performing segments could improve efficiency and revenue outcomes.

### Product Performance
- ZoomaClass and ZoomaMeet Pro accounted for the majority of closed-won revenue, performing strongly across both volume and conversion rate.
- Products like ZoomaConnect and ZoomaWebinars showed limited sales success and may require repositioning or bundling.
- The concentration of revenue in top products highlights an opportunity to streamline focus and marketing strategy.

### Time to Close
- The overall average time to close a deal was 69 days. However, some reps—including Cassie Voss and Jasmin Rowe averaged 74+ days.
- The top-performing rep closed deals in an average of 60 days, suggesting that best practices can be standardized to accelerate cycle time.

---

## Recommendations
The following are strategic opportunties:

- **Coach Underperforming Reps with High Lead Volume** - Several reps are managing a large number of leads but converting at or below 41%, well below the firm average of 48%. Targeted coaching can help improve qualification and close rates.
- **Prioritize High-Converting Industries** - The Medical and Entertainment industries consistently convert above 64%, while the lowest-performing group lags at 53%. Focus marketing and outreach on proven verticals.
- **Focus on Top-Performing Products** - ZoomaClass and ZoomaMeet Pro outperform other offerings in both conversion rate and revenue. Strategic bundling, feature expansion, or targeted promotions may increase returns further.
- **Reduce Deal Cycle Times in Lagging Segments** - While the overall average time to close is 69 days, some reps and industries exceed 74 days. Standardizing follow-up processes and adopting best practices from high performers can help accelerate deal velocity.

## Next Steps
To build on this analysis, the following areas could be explored with additional data:

- **Evaluate the impact of coaching** by tracking whether conversion rates improve for underperforming reps after targeted training.
- **Identify high-performing lead sources** by analyzing conversion rates and deal velocity by marketing channel (e.g., email, ads, events).
- **Build lead scoring and funnel visualizations** to help sales teams prioritize high-potential leads and monitor deal progression more effectively.
