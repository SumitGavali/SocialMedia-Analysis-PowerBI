# SocialMedia-Analysis-PowerBI
📌 Project Overview<br>
This Power BI report analyzes social media engagement by visualizing interactions such as clicks, replies, retweets, and likes. The insights help in understanding user behavior and optimizing content strategies.

📌 Tasks & Visualizations<br>
🔹 Task 1: Clicks Breakdown - Pie Chart
📍 Objective:<br>
Analyze the proportion of total clicks (URL clicks, profile clicks, and hashtag clicks) for tweets with more than 500 impressions.
Enable drill-down functionality to view specific types of clicks for each tweet.<br>

📊 Visualization:<br>
Pie Chart: Shows the distribution of total clicks.
💡 Filter Applied: Only tweets with impressions > 500 are included.

🔹 Task 2: Clicks by Tweet Category - Clustered Bar Chart<br>
📍 Objective:<br>
Compare the sum of URL clicks, profile clicks, and hashtag clicks across different tweet categories:
Tweets with media
Tweets with links
Tweets with hashtags

Only include tweets where:

Tweet date is even-numbered.
Tweet word count is above 40.<br>

📊 Visualization:

Clustered Bar Chart: Compares total clicks across tweet categories.
Time-Based Visibility: The chart appears only during the specified time range.
💡 Filters Applied:
<br>
Display tweets with at least one type of interaction.
Only include tweets posted on even dates.
Word count must be greater than 40.<br>

🔹 Task 3: Engagement vs. Media Performance - Comparison Chart<br>
📍 Objective:<br>
Compare replies, retweets, and likes for tweets that have media engagements greater than the median.
Apply a filter for tweets posted between June - August 2020.

Additional filters:<br>
Tweet date must be odd.
Media views must be even.
Remove words that contain the letter ‘S’ from tweets.
Tweet character count must be above 20.<br>

📊 Visualization:
<br>
Bar Chart: Displays the engagement metrics for qualified tweets.
Time-Based Visibility: The chart appears only during the specified time ranges.<br>

💡 Filters Applied:<br>
Tweets with media engagements > median value.
Tweets posted between June - August 2020.
Tweet date must be odd & media views must be even.<br>
📌 Key Performance Indicators (KPIs) Used<br>
Total Clicks = URL Clicks + Profile Clicks + Hashtag Clicks
Impressions-to-Engagement Ratio
Median Media Engagement<br>
🚀 Built using: Power BI | Power Query | DAX
