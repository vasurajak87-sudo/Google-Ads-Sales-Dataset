# Google-Ads-performance-analysis

Problem statement=
Analyze Google Ads campaign data to identify performance trends, optimize ad spend, and improve conversions.

Data cleaning=
- Removed duplicate rows
- Handled missing values:
- Filled clicks, conversions, leads with 0
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

Recommendation=
- Allocate budget to high-performing campaigns
- Reduce spend on low-ROAS campaigns
- Optimize campaigns with low CTR

