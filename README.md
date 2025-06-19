# E-Commerce-Business-Analysis-Project

## Project Overview
This Power BI dashboard presents a detailed, end-to-end analysis of an e-commerce business, focusing on essential performance metrics that drive growth and efficiency. It provides a data-rich view of the company’s operations, aimed at uncovering trends, identifying gaps, and supporting strategic decisions.
The dashboard explores a range of critical areas, starting with overall business performance, including revenue trends and growth metrics. It dives into customer demographics, analyzing segments by age, gender, marital status, and education level to better understand customer behavior and churn patterns.

Additionally, it visualizes revenue contributions from products and categories, helping highlight top-performing items and identify areas for potential expansion or adjustment. The dashboard also examines the effectiveness of marketing efforts, revealing how campaigns influence revenue over time and across product lines.
A key component of the analysis includes assessing the performance of various sales channels—such as online, retail, mobile, and marketplace—offering insights into which platforms are most effective in generating revenue. It also monitors inventory flow, allowing for better stock management and fulfillment efficiency.
Beyond financials and marketing, the dashboard sheds light on operational performance, spotting patterns and performance shifts over time. This multi-dimensional view empowers stakeholders to make informed, data-driven decisions across departments.
Ultimately, the dashboard serves as a strategic tool to support decision-makers, uncover hidden opportunities, and optimize business operations across the entire value chain. Its dynamic visuals and interactive elements make it not only informative but also easy to navigate and explore.

## Problem Statement
J & J is a retail business operating in a competitive and fast-paced market. Although the company has recorded consistent revenue and growth across multiple states and sales channels, it continues to face challenges in achieving sustained profitability, optimizing marketing efforts, and improving operational efficiency. The business recognizes the need for a data-driven approach to uncover hidden patterns, reduce inefficiencies, and maximize return on investment.

To guide strategic decision-making, the business seeks to explore the following critical questions:

#### **Product Performance**

* Which product categories and individual products are driving the most revenue?
* Which products are underperforming, and what factors may be contributing to low sales or high return rates?
* How can inventory usage be better aligned with actual customer demand?

#### **Customer Behavior and Retention**

* Which customer segments contribute most to revenue, and which segments are at risk of churn?
* What patterns exist in product returns that may indicate dissatisfaction or delivery issues?
* How can customer retention be improved, particularly for high-value segments?

#### **Marketing Strategy and Efficiency**

* Which marketing campaign types are generating the most clicks and conversions?
* What is the current return on advertising spend (ROAS), and how can it be improved?
* How effective are individual marketing channels in driving revenue compared to their costs?
* What strategies can increase conversion rates and reduce customer acquisition costs?

#### **Sales Channel Optimization**

* Which sales channels yield the highest revenue and best customer engagement?
* How balanced is the distribution of revenue across online, retail, mobile, and other channels?
* Are there emerging or underutilized channels with potential for growth?

#### **Geographic Performance**

* Which regions and states are top-performing in terms of revenue, conversions, and delivery efficiency?
* Where are the gaps in market coverage, and which regions show potential for expansion or improved performance?
* How do return rates and delivery issues vary by state?

#### **Operational Improvement**

* How efficient are current delivery operations, and where are the key bottlenecks?
* What is the relationship between product return rates and operational costs?
* How can inventory and logistics be optimized to reduce waste and increase efficiency?

By answering these questions, J & J aims to gain actionable insights that will enable smarter business decisions, improve customer satisfaction, and drive long-term growth.

## Data Structure

The data is organized across multiple tables:

* `Sales`: Sales data including date, product ID, customer ID, transaction_id, revenue, and profit, discount category.
* `Customers`: Name, churn flag, demographics including gender, age, marital status, income, education, state.
* `Products`: Product details including product name,category, brand, and store/channel.
* `Marketing`: Customer_ID, campaign_id, conversion, impression, clicks, campaign_type.
* `Operations`: Operational data covering order_date, delivery_date, delivery status, order status, inventory_used.

## Tool Used

* Microsoft Power BI (Desktop)

## Data Analysis Process

1. Data Cleaning using Power Query
2. Data Modeling by establishing relationships between tables
3. DAX Measures for calculating KPIs (YoY Growth, delivery efficiency, ROAS, return rate, Churn Rate, etc.)
4. Figma for Dashboard Design with interactive visuals 
5. Insight Extraction to inform business decisions.

## Insight Deep Dive – J & J Business Analysis
![Screenshot 2025-06-16 004757](https://github.com/user-attachments/assets/0b1059f9-d227-47b8-ab67-0439d8bd9470)

 ### Revenue Overview Dashboard

This dashboard provides a high-level view of how revenue is distributed across products, channels, categories, and geographies.

#### Key Insights:
**Total Revenue:** $12M generated with an average monthly revenue of $259K and 49K transactions.

**Top Performing Products:** Products such as HP Laptop, Maybelline Lipstick, and Panasonic Microphones consistently generate over $1.2M in revenue, reflecting strong brand demand.

**Channel Performance:** Revenue is evenly distributed across Online, Retail Stores, Marketing Events, and Mobile Platforms, each contributing approximately 25% of total revenue. This shows a healthy omnichannel strategy.

**Geographic Performance:** South Dakota leads with $267K in revenue, signaling a strong local presence or demand in that region.

**Category Trends:** Over the years, Apparel and Beauty consistently outperform Electronics in revenue, with noticeable seasonal peaks, especially during Q4 of each year.

**YoY Growth:** The business recorded a solid 33.3% YoY revenue growth, indicating successful scaling or market penetration efforts.


![Screenshot 2025-06-16 003234](https://github.com/user-attachments/assets/766bbd6b-3341-48c3-b316-89f5caa9b6c1)

### Marketing Overview Dashboard 

This dashboard evaluates the effectiveness of various marketing campaigns and spending.

#### Key Insights:
**Total Marketing Spend vs Revenue:** Total spend stands at $20M, generating $12M in revenue, resulting in a ROAS (Return on Ad Spend) of 0.62, which is below industry benchmarks.

**Conversion & Click Metrics:** While Email Campaigns led in clicks (9M) and conversions (196K), this hasn't translated proportionally into revenue — signaling a gap between engagement and monetization.

**Top Campaign by ROI Potential:** Email and Social Media are the best-performing campaign types in both revenue and conversion terms, suggesting room for optimization rather than replacement.

**Geographic Insights:** Oregon emerged as the top-performing state in terms of marketing conversions (10,449), offering a model for regional marketing strategies.

**Conversion Rate:** A relatively low conversion rate of 2% suggests a need to refine targeting, creatives, or funnel optimization.


![Screenshot 2025-06-16 004552](https://github.com/user-attachments/assets/e77dcdeb-8b06-4b5f-a806-0c7ff71c0e52)

### Operations Overview Dashboard
This dashboard explores delivery performance, return rates, and inventory usage across regions and products.

#### Key Insights:
**Fulfillment Volume:** Over 1 million units delivered with an 85% delivery efficiency, indicating strong supply chain performance.

**Product Returns:** Return volume is 45K, with a 3.6% return rate — relatively low, but products like HP Laptop and Dove Body Wash show slightly higher-than-average return rates (~3.8%).

**Return Loss:** Return losses are pegged at 3.1%, suggesting areas to further reduce costs by minimizing defective or misfit shipments.

**Inventory Usage:** Most used inventories include Maybelline Lipstick (151K) and Samsung Smart TV (149K) — indicating high product turnover and possible consumer preference.

**Return Rate by State:** Iowa and Georgia exhibit higher return rates (>4.9%), highlighting the need to investigate region-specific fulfillment or product issues.

**Usage Trend:** Product usage remains stable, with seasonal peaks in Q4 of each year — possibly tied to holiday promotions or end-of-year campaigns.

📌 Summary & Strategic Takeaways
Revenue Growth is strong, but marketing investment is underperforming. Refine strategy to improve ROAS.

High-performing states and products offer scalable models — leverage localized insights.

Operational metrics are solid, but there's room to improve delivery efficiency and reduce return impact.

Apparel and Beauty categories consistently outperform — consider expanding those lines.

Focus on improving conversion rates across campaigns through targeted customer engagement and better funnel design.




