# ZoomaTech Sales Performance Dashboard
**This analysis uncovers key sales trends and provides insights to improve conversion, reduce cycle time, and focus strategic efforts.**

## Overview

ZoomaTech is a growing provider of video calling solutions for small businesses. As ZoomaTech expands its presence in the business communications market, leadership has identified a growing need to evaluate sales effectiveness across customer industries, products, and individual sales representatives. Prior reporting methods were decentralized and operational in nature, limiting leadership's ability to surface trends, identify inefficiencies, or make data-informed strategic decisions.

To address this gap, a centralized dashboard was developed to bring together key sales performance metrics and support quarterly reviews, coaching for sales representatives, and product focus decisions.

## Objective

The primary goal of this initiative is to provide leadership with a real-time, self-serve view of sales performance across the organization. The dashboard enables leadership to:

- Track sales conversion and average time to close
- Identify top-performing sales representatives, industries, and products
- Use data to guide strategic planning, coaching, and resource allocation

## Data Model & Sources

The data model below is sourced from the CRM and includes engaged sales activity from the past 12 months (July 2024 to May 2025).
- **Customers** - unique list of all customers
- **Sales** - all leads in the pipeline, including key fields such as engage date, close date, status, product, and quantity.
- **Products** - unique list of all products with pricing
  
![Data Model drawio](https://github.com/user-attachments/assets/71549f47-77f4-43bc-a92b-c385cda54ec5)


## Key Metrics
The following KPIs were used to assess sales representative efficiency, product effectiveness, and sales pipeline performance across the organization.

- **Sales Conversion Rate** = # Won Leads / # Total Leads (based on engage date). Measures overall sales representative effectiveness and supports benchmarking across products and industries.
- **Average Days to Close** = Average time to close for **won** deals only. Use as a benchmark for sales representative efficiency and uncover delays in the sales process.
- **Revenue** = Quantity × Price. Track sales representative and product performance.

## Dashboard Features 
[ZoomaTech Sales Dashboard](https://public.tableau.com/views/Sales_17462088266400/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

- **Filters** - by industry, sales representative, product
- **Monthly Trends** - for both conversion rate and time to close
- **Leaderboard Views** - revenue and efficiency metrics by sales representative and product
- **Industry Performance** - insights into performance by customer industry
- **Responsive Layout** - designed for executive visibility and drill-down exploration
  
![dashboard](https://github.com/user-attachments/assets/7cead179-df19-475d-b293-fcd712963103)

## Key Insights

### Sales Representative Performance
- Jake Linwood and Zara Almasi demonstrated consistently high effectiveness, converting over 59% of their leads (average over the last 12 months was 48%).
- In contrast, Carrie Reese and Jasmine Rowe converted 41% of their leads, despite handling high volumes.
- This suggests an opportunity for targeted coaching and performance enablement.

### Industry Trends
- The Medical and Entertainment industries had the highest conversion rates, each exceeding 64%.
- Leads categorized under “Unknown Industry” converted at lower rates (53%), suggesting gaps in data quality or fit.
- Prioritizing known high-performing industries could improve efficiency and revenue outcomes.

### Product Performance
- ZoomaClass and ZoomaMeet Pro accounted for the majority of closed-won revenue, performing strongly across both volume and conversion rate.
- Products like ZoomaConnect and ZoomaWebinars underperformed and may benefit from repositioning, bundling, or closer market fit analysis.
- The concentration of revenue in top products highlights an opportunity to streamline focus and marketing strategy.

### Time to Close
- The overall average time to close a deal was 69 days. However, some sales representatives including Cassie Voss and Jasmin Rowe averaged 74+ days.
- The top-performing sales representative closed deals in an average of 60 days, suggesting that best practices can be standardized to accelerate cycle time.

## Recommendations
These strategic recommendations are based on key trends observed in the data.

- **Coach Underperforming Sales Representatives with High Lead Volume** - Several sales representatives are managing a large number of leads but converting at or below 41%, well below the firm average of 48%. Targeted coaching can help improve qualification and close rates.
- **Prioritize High-Converting Industries** - Focus outreach on Medical and Entertainment (65%+ conversion) to maximize marketing ROI and lead efficiency.
- **Focus on Top-Performing Products** - ZoomaClass and ZoomaMeet Pro outperform other offerings in both conversion rate and revenue. Strategic bundling, feature expansion, or targeted promotions may increase returns further.
- **Reduce Deal Cycle Times in Lagging Segments** - While the overall average time to close is 69 days, some sales representatives and industries exceed 74 days. Standardizing follow-up processes and adopting best practices from high performers can help accelerate deal velocity.

## Next Steps
These next steps outline future opportunities for deeper analysis, assuming access to additional data.

- **Evaluate the impact of coaching** by tracking whether conversion rates improve for underperforming sales representatives after targeted training.
- **Identify high-performing lead sources** by analyzing conversion rates and deal velocity by marketing channel (e.g., email, ads, events).
- **Build lead scoring and funnel visualizations** to help sales teams prioritize high-potential leads and monitor deal progression more effectively.
