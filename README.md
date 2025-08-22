📊 B2B Marketing Revenue Insights
Sample Analysis for iHeartMedia – Data Analyst Exercise
🎯 Objective

Explore anonymized sales & revenue data (~300k rows) to identify performance trends and provide actionable insights for iHeartMedia’s B2B marketing and sales leadership.

The project uses both Python (EDA + AI-assisted anomaly detection) and Tableau (executive dashboards) to surface opportunities and risks.

❓ Key Business Questions
1. Which markets are stronger or weaker performers?

Top markets: Los Angeles, New York, Houston, Cincinnati.

Weaker markets: LaGrange, Gallup (NM), Defiance, New Haven (CT).

✅ Revenue is highly concentrated in a few major markets.

📈 Action: Prioritize mid-tier markets for growth potential.

2. Which products or sellers stand out?

Products: Broadcast dominates. Podcasts & Streaming show rapid growth.

Sellers: Sellers 467, 393, 1330 drive outsized performance; some underperformers present opportunities for enablement.

📈 Action: Cross-train underperforming sellers and double down on Podcast growth.

3. Do certain months perform better?

Clear Q4 holiday spikes.

January rollover effect → revenue carries over from prior campaigns.

February dip likely reflects seasonal slowdown.

📈 Action: Align marketing pushes with seasonal cycles & anticipate dips.

4. Are there products that consistently drive more revenue?

Broadcast: Stable, high volume.

Podcast + Streaming: Smaller base but strong growth trajectory.

📈 Action: Maintain Broadcast dominance while nurturing Podcast/Streaming.

🤖 AI-Assisted Insights

Anomaly detection (Isolation Forest) flagged unusual deals.

Most outliers appeared in Local Order Types, which makes sense—local deals have more variance due to ad hoc buys/events.

✅ AI acts as a “second set of eyes,” surfacing potential risks and overlooked opportunities.

📊 Tableau Dashboard

Interactive dashboard with drilldowns for:

Market performance

Product mix

Seller revenue

Seasonal trends

🔗 [View Dashboard on Tableau Public](https://public.tableau.com/views/B2BMarketingRevenueInsightsiHeartMediaSampleAnalysis/B2BMarketingRevenueInsightsiHeartMediaSampleAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

Screenshot of Dashboard <img width="1998" height="1598" alt="B2B Marketing   Revenue Insights – iHeartMedia (Sample Analysis)" src="https://github.com/user-attachments/assets/d743e8cb-257c-41ff-9f6b-83839c90644e" />


📘 Data & Methods
Data Cleaning

Dropped 2.77% rows with missing critical values (Markets, Products, Sales Order IDs).

Final dataset: 291,685 rows (~97% retained).

Python EDA

Grouped and ranked by Markets, Products, Sellers, Order Types.

Visualized top/bottom performers.

Applied AI anomaly detection to flag revenue outliers.

Tableau

Created clean, interactive dashboard for executives.

Breakdowns by Market, Product, Order Type, Advertiser.



🚀 Next Steps / Recommendations

Standardize & clean data inputs (esp. “Unknown” categories).

Double down on Podcast/Streaming as emerging revenue drivers.

Strengthen mid-tier market development to reduce over-reliance on top metros.

Scale AI-assisted anomaly detection into sales ops workflows for proactive opportunity spotting.
