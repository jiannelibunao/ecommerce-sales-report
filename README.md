# E-Commerce Sales Report
Tools and Techniques: **Power BI, Power Query, Data Modeling, DAX, Dashboard Development**

![ecommerce-page](https://github.com/jiannelibunao/ecommerce-sales-report/blob/c3c247f453f0cc1173d2746f5ab4e4743c1fb05e/Assets/header.png)

## Table of Contents
1. Project Background
2. Data Structure and Initial Checks
3. Executive Summary
4. Insights Deep Dive
5. Recommendations

## Project Background
A global software retailer sells subscriptions and add-ons across analytics, design, collaboration, and AI. They have two years of historical sales data that needs to be analyzed for smarter, customer-focused decisions.
This project provided a detailed multi-page report highlighting factors that impact customer loyalty under different factors.
Insights and recommendations are provided on the following key areas:
-	**Revenue Trend (Regular vs. Loyal Customers):** Comparison between two customer bases in terms of revenue impact.
-	**Top Drivers of Sales:** Exploration of different areas of revenue growth focusing on sales channel, product category, payment method, and geographical presence. This helped in understanding each influence on sales.
-	**Customer Lifecycle:** Breakdown of customer tiers in terms of purchased items.
-	**Repeat Purchase Rate via Acquisition Channel:** Identify best channels in engaging repeat customers who have made more than 10 purchases.
-	**Price vs. Revenue on Loyalty:** Analysis on the performance of Repeat Purchase Rate between price and sales of products.

## Data Structure and Initial Checks
The company dataset structure as seen below consists of three (3) sheets, [Events], [Products], and [Customers]. [Events] has 20 native columns with one primary key connected [Products] and [Customers]. [Product] has 13 columns while [Customers] has 10. 

![dataset-structure](https://github.com/jiannelibunao/ecommerce-sales-report/blob/c3c247f453f0cc1173d2746f5ab4e4743c1fb05e/Assets/data-structure.png)

Prior to beginning the analysis, an inspection was conducted in Power Query to check any data errors. No issues were found and familiarization of the dataset was established.

## Executive Summary
The business shows strong year‑over‑year growth across sales, transactions, and loyalty, though recent months reflect a temporary 18–27% decline. Loyal customers now make up the majority of the base, with 73% purchasing 10+ products and many returning sooner than the 47‑day average to repurchase. Revenue is driven primarily through the website, with Developer Tools as the top category and Azure AI Studio Annual leading in product revenue. Annual billing dominates at 88%, reinforcing long‑term customer commitment, while mid‑range product prices correlate most strongly with loyalty. Credit cards remain the preferred payment method, and the EU leads in customer volume while the US generates the highest revenue. Social channels deliver the strongest repeat purchase rates, and discount usage is led by WELCOME10, which drove 3K orders and significant customer savings. Add‑ons contribute meaningfully, with Advanced Reports Add‑on Annual as the top performer despite a modest 3% refund rate.

## Insights Deep Dive
### Performance Overview

![overview-page](https://github.com/jiannelibunao/ecommerce-sales-report/blob/c3c247f453f0cc1173d2746f5ab4e4743c1fb05e/Assets/v0_overview.png)

####	Yearly Growth vs. Monthly Volatility
-  **Sales, transactions, and loyalty metrics have grown steadily from 2024 to 2025.** However, recent monthly data reveals a noticeable dip:
    -	Revenue dropped 25.03% in October 2025
    -	Orders declined by 27.29%
    -	Loyal customers fell by 18.68%
- These dips suggest seasonal or campaign-related fluctuations that may need closer investigation.

#### Top Product and Channel Synergy
- Microsoft 365 Business Standard Annual is the top-performing product, generating $1.63M from 484 orders.
- The website channel drove the highest revenue ($14.42M) and order volume (22K), confirming its dominance in reach and conversion.
####	Customer Loyalty Funnel
- **Social channels are the most effective for acquisition**, converting 537 customers with a repeat purchase rate of 75.85%. This indicates strong engagement and retention potential through social-driven campaigns.
####	Geographic Strength
-  **The EU region leads in both revenue ($13.69M) and customer count (4K)**, making it a strategic priority for expansion or tailored offerings.
    -	Insight Panel Highlights
    -	Revenue peaked in July 2025 at $1.93M
    -	Orders peaked in August 2024 at 2,824
    -	Loyalty peaked in May 2024 at 1,625
- These peaks can guide future campaign timing and promotional strategies.

### Ecommerce Performance 

![ecommerce-page](https://github.com/jiannelibunao/ecommerce-sales-report/blob/c3c247f453f0cc1173d2746f5ab4e4743c1fb05e/Assets/v1_ecommerce.png)

#### Customer Loyalty and Behavior
-	**Loyalty Dominance:** Loyal customers make up almost 75% of the total customer base (3K out of 4K), with a strong repeat purchase rate of 73.15%. This indicates high retention and brand trust.
-	**Revenue Distribution:** Monthly revenue trends show consistent growth, peaking at $1.9M in June 2025. Loyal customers contribute significantly to this upward trajectory.
#### Channel and Category Performance
-	**Website as Primary Driver:** The website channel generated $14.42M in sales from 22K orders, outperforming all other channels including Direct Sales, Reseller, and Marketplace.
-	**Top Product Category:** Developer Tools led with $4.82M in revenue and 5K orders, suggesting strong demand among technical users or business clients.
#### Payment Preferences
- **Credit Card Dominance:** Credit cards accounted for 54.88 percent of all orders (26K), followed by Invoice (25.11%), PayPal (15.03%), and Wire (4.98%). This highlights the importance of maintaining seamless card-based payment experiences.
#### Geographic Reach
-	**EU vs. US:** The EU region shows the largest customer presence and broad reach ($13.69M), but the United States tops individual country revenue with $8.58M. This suggests the EU is a strategic volume market while the US drives high-value transactions.

### Customer Loyalty

![customer-page](https://github.com/jiannelibunao/ecommerce-sales-report/blob/c3c247f453f0cc1173d2746f5ab4e4743c1fb05e/Assets/v2_loyalty.png)

#### Loyalty Strength and Purchase Behavior
-	**High Loyalty Engagement:** 73% of customers purchased 10 or more products, qualifying as champions in the loyalty lifecycle. This reflects deep product engagement and strong brand affinity.
-	**Accelerated Second Purchases:** More than half of customers made their second purchase faster than the average interval of 47 days, indicating effective onboarding and early retention.
#### Acquisition Channel Performance
-	**Loyalty Dominance Across Channels:** Repeat purchase rates across all acquisition channels exceeded 70%, with Social (75.85%), Email (74.40%), and Organic (73.06%) leading. This confirms that loyalty conversion is consistently strong regardless of entry point.
#### Segment-Level Value
-	**Consumer Segment Leads:** Among all segments, Consumer customers showed the highest performance across:
    -	Repeat Purchase Rate (RPR): 73.74%
    -	Average Order per Customer (AOC): 12
    -	Average Revenue per Customer (ARC): $10,871. 
- This makes them a prime target for personalized campaigns and premium offerings.
#### Campaign Effectiveness
-	**Student Discounts Drive Loyalty:** Discount codes like EDU20, SAVE5, and SALE15 all achieved repeat rates above 80%. EDU20 led with an 81.34% RPR and an average spend of $238, suggesting strong traction among student buyers and educational segments.

### Product Performance

![product-page](https://github.com/jiannelibunao/ecommerce-sales-report/blob/c3c247f453f0cc1173d2746f5ab4e4743c1fb05e/Assets/v3_product.png)

#### Category and Product Leaders
-	**Top Category:** Developer Tools led all product categories with 17.25% of total revenue, confirming strong demand among technical users.
-	**Top Product:** Azure AI Studio Annual generated the highest revenue, outperforming other AI and productivity tools.
#### Discount and Promotion Impact
-	**WELCOME10 Dominance:** This discount code was used in 3K orders, saving customers $479M. Its popularity suggests strong onboarding success and effective first-purchase incentives.
#### Billing Cycle Preference
-	**Annual Plans Drive Revenue:** 88.3% of revenue came from annual billing, far surpassing monthly and one-time options. This reflects customer preference for long-term value and subscription stability.
#### Loyalty and Pricing Dynamics
-	**Positive Correlation:** The scatter plot shows that higher product prices tend to generate more revenue, with loyalty clustering around mid-range price points. This suggests that customers are most loyal to products offering balanced value and affordability.
#### Add-on Performance
-	**Top Add-on:** Advanced Reports Add-on Annual led with $378.6M in revenue and 461 orders. Despite having the highest refund rate at 3%, it's still relatively low and not a major concern.
-	**Overall Refund Rate:** At just 2.09%, the low refund rate indicates strong product-market fit and minimal issues in order handling or customer satisfaction.

## Recommendations
Here are actionable recommendations for optimization in the business:
1. **Strengthen Loyalty Programs**
-	**Champion Conversion:** With 73% of customers buying 10+ products, reinforce loyalty tiers with exclusive perks, early access, and milestone rewards.
-	**Accelerate Second Purchases:** Launch time sensitive nudges and personalized follow ups within the first 40 days to capitalize on early repeat behavior.
-	Segment Targeting: Prioritize the Consumer segment for premium bundles and upsell campaigns, given their high RPR, AOC, and ARC.
2. **Optimize Channel Strategy**
-	**Website as Core Driver:** Invest in UX enhancements, SEO, and conversion rate optimization for the website, which leads in both revenue and order volume.
-	**Social for Loyalty:** Use social channels for retention campaigns, loyalty storytelling, and referral programs, leveraging their 75.85% repeat rate.
3. **Refine Product and Pricing Strategy**
-	**Mid Range Loyalty Sweet Spot:** Focus product development and bundling around mid range price points where loyalty is strongest.
-	**Annual Billing Emphasis:** Promote annual plans with value messaging and loyalty tie ins, as they drive 88.3% of revenue.
-	**Add on Upsell Strategy:** Highlight top performing add ons like Advanced Reports, while monitoring refund trends to improve satisfaction.
4. **Leverage Promotions and Discounts**
-	**Student Focused Campaigns:** Scale EDU20 and similar codes across educational channels and back to school seasons to boost early retention.
-	**Welcome Offers:** Use WELCOME10 as a proven onboarding tool, paired with personalized product recommendations to increase AOV.
5. **Geographic Expansion and Localization**
-	**EU for Volume, US for Value:** Localize messaging and product bundles for EU markets to scale reach, while tailoring high value offerings for US customers.
-	**Regional Campaigns:** Align promotions with regional peaks such as July for revenue and August for orders to maximize seasonal impact.
6. **Monitor and Maintain Operational Excellence**
-	**Low Refund Rate as a Strength:** Maintain fulfillment quality and post purchase support to preserve the 2.09% refund rate.
-	**Feedback Loops:** Use refund data from top add ons to refine onboarding, documentation, and customer education.

## Let's Connect 🔗
[LinkedIn](https://www.linkedin.com/in/jiannelibunao/ "LinkedIn")  |  Digital Portfolio
