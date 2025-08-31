# Twitter-Data-Analytics
Power BI Twitter Analytics Dashboard with advanced filters, time-based visual restrictions, and engagement insights. Includes pie, bar, scatter, line, and dual-axis charts to analyze impressions, clicks, engagements, and trends with odd/even logic and dynamic rules for social media performance.
Pie Chart – Proportion of total clicks (URL, profile, hashtag) for tweets with >500 impressions. Includes drill-down to view clicks at the tweet level.

Top 10 Tweets Chart – Identifies tweets with the highest combined retweets and likes. Excludes weekends and applies strict filters (even impressions, odd dates, word count <30). Visible only 3–5 PM IST.

Clustered Bar Chart – Breaks down URL clicks, profile clicks, and hashtag clicks by tweet category (media, links, hashtags). Requires interactions >0 and applies filters (even dates, word count >40). Visible only 3–5 PM IST.

Scatter Chart – Analyzes media engagements vs media views for tweets with >10 replies. Highlights tweets with engagement rate >5%. Visible only 6–11 PM IST.

Dual-Axis Chart – Compares media views and engagements by day of the week for the last quarter. Highlights spikes with filters (even impressions, odd dates, char count >30, words without “H”). Visible only 3–5 PM IST & 7–11 AM IST.

Line Chart – Tracks average engagement rate trends monthly, split between tweets with media vs without. Filters applied (even engagements, odd dates, char count >20, words without “C”). Visible only 3–5 PM IST & 7–11 AM IST.

Engagement Comparison – Compares engagement rate for tweets with vs without app opens. Restricted to weekday hours (9 AM–5 PM) with filters (even impressions, odd dates, char count >30, words without “D”). Visible only 12–6 PM IST & 7–11 AM IST.

Highlights-
Built with Power Query + Power BI

Implements conditional filters, odd/even data logic, dynamic visibility based on IST time ranges

Demonstrates complex transformations and advanced visualization techniques for tweet engagement analysis
