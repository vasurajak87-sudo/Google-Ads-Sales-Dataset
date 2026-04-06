Title=
Google-Ads-performance-analysis

Problem statement=
Analyze Google Ads campaign data to identify performance trends, optimize ad spend, and improve conversions.

Data cleaning=
- Removed duplicate rows
- Handled missing values:
- Filled clicks, conversions, leads with 0 which are null
- Imputed impressions and cost using median 
- Removed rows with missing sales values (~5%)
- Removed inconsistent "Conversion Rate" column and recalculated it
- Standardized data types and formats

Feature engineering=
- Created new metrics:
- CTR (Clicks / Impressions)
- CPC (Cost / Clicks)
- Conversion Rate (Conversions / Clicks)
- Cost Per Conversion
- ROAS (Sales / Cost)

Analysis=
- Compared campaign performance using sales and conversions
- Evaluated efficiency using ROAS and CPC
- Analyzed time trends in sales

Dashboard=
Built an interactive Power BI dashboard including:
- KPIs: Sales, Cost, Conversions, ROAS
- Campaign performance charts
- Trend analysis
- Filters for campaign and date

Key insights=
- Certain campaigns generate high cost but low ROAS
- Some campaigns show strong conversion efficiency
- Sales trends vary significantly over time
- - The campaign generated $3.65M in sales with a ROAS of 7.03, indicating highly profiable ad campaign.								
- Total conversion reached 15,585 showing strong user enagagement.								
- The campaign maintained strong balance between cost ($529K) and revenue ($3.65M).								
- Sales show fluctuations across dates, with noticeable peaks around mid-month, indicating possible seasonal or campaign-driven demand spikes.								
- Despite having only one campaign, performance analysis through time-based trends and efficiency metrics provides meaningful insights into campaign effectiveness.


Recommendation=
- Allocate budget to high-performing campaigns
- Reduce spend on low-ROAS campaigns
- Optimize campaigns with low CTR



