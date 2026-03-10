
# Meta Ad Performance Dashboard (Power BI)

## Project Overview
This project analyzes advertising campaign performance across Meta platforms (Facebook & Instagram) using Power BI.

The dashboard provides insights into campaign reach, engagement, conversion funnel, and audience behavior.

## Business Objective
The goal is to help marketing teams:
- Track campaign performance
- Optimize budget allocation
- Identify high-performing ad formats and audiences

## Dataset
The dataset contains four tables:

1. ad_events – event-level interactions (impressions, clicks, purchases)
2. ads – ad creative and targeting details
3. campaigns – campaign budget and duration
4. users – demographic and geographic user information

## Data Model
Star Schema:

Fact Table
- ad_events

Dimension Tables
- ads
- campaigns
- users

## KPIs Used
- Impressions
- Clicks
- Engagements
- Purchases
- CTR (Click Through Rate)
- Engagement Rate
- Conversion Rate
- Purchase Rate
- Total Budget

## Key Insights
- High CTR (~11.7%) shows strong ad creatives
- Engagement rate (~13.5%) indicates strong audience interest
- Purchase rate (~0.6%) suggests drop in the conversion funnel
- Females aged 18–30 show highest engagement
- Video and Story ads perform best

## Tools Used
- Power BI
- Data Modeling
- DAX
- Data Visualization
