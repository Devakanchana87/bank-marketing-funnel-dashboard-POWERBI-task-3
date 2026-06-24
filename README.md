# bank-marketing-funnel-dashboard-POWERBI-task 3
# Bank Marketing Funnel & Conversion Performance Dashboard
### Future Interns – Data Science & Analytics Internship | Task 3

## Overview
Marketing funnel and conversion performance dashboard built using Power BI,
analyzing how bank clients move from being targeted to subscribing a term
deposit — covering funnel drop-offs, channel performance, and segment insights.

## Tools Used
- Power BI Desktop
- Power Query
- Python (pandas) — data cleaning & feature engineering

## Dataset
- **Name:** Bank Marketing Dataset (UCI Machine Learning Repository)
- **File used:** bank-full.csv → cleaned to bank_marketing_funnel.csv
- **Size:** 45,211 clients | 28 features (after transformation)
- **Target variable:** y — Has the client subscribed? (Yes/No)
- **Period:** May 2008 – November 2010

## Key Insights
1. Overall conversion rate is 11.7%, with a major drop-off between
   Responsive (36K) and Converted (5K) clients
2. Prior campaign success is the strongest predictor — 64.7% conversion
   vs ~9–17% for all other outcomes (5x the average)
3. Cellular channel outperforms telephone (14.9% vs 13.4%) and
   unspecified contact methods (4.1%)
4. More follow-up calls reduce conversion — first contact converts at
   14.6% vs only 7.4% for 4+ contacts (diminishing returns)
5. Students and retirees are the highest-converting job segments (~25%+)
6. High-balance clients (2000+) convert at nearly 2x the rate of
   negative-balance clients
7. Conversion rate trended upward from 2008 to 2010

## Recommendations
1. Prioritize cellular as the primary contact channel
2. Limit follow-up attempts to 2–3 contacts per client
3. Build a re-engagement list targeting clients with prior campaign success
4. Focus outreach on students, retirees, and high-balance customers
5. Time campaigns toward year-end based on upward conversion trend

## Dashboard Pages
- **Page 1:** Marketing Funnel & Conversion Performance
- **Page 2:** Segment Analysis & Recommendations

## Dashboard PDF
- [Marketing_Funnel_Dashboard.pdf](your-pdf-link-here)

## Dashboard Link
- [Power BI File](your-pbix-link-here)
