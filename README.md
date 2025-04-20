# 📊 Sentiment Analysis Dashboard using Power BI

This project presents a **Power BI dashboard** built using social media data to analyze user sentiment, platform engagement, and regional trends. It provides insights into how users express their thoughts across different platforms, locations, and time periods.

## 📁 Files Included
- `data.pbix`: The Power BI report file containing all visuals and data transformations.
- `sentimentdataset.csv`: The raw dataset used for analysis. It contains labeled social media posts with timestamps, user details, platform, and engagement metrics (likes, retweets, hashtags, etc.).

## 📌 Dataset Overview
The dataset includes 130 records and the following key features:

| Column        | Description |
|---------------|-------------|
| `Text`        | The social media post content. |
| `Sentiment`   | The sentiment label — **Positive**, **Negative**, or **Neutral**. |
| `Timestamp`   | Date and time the post was made. |
| `User`        | User identifier (anonymized). |
| `Platform`    | Social media platform (e.g., Twitter, Facebook, Instagram). |
| `Hashtags`    | Hashtags used in the post. |
| `Retweets`    | Number of retweets (where applicable). |
| `Likes`       | Number of likes. |
| `Country`     | Origin country of the user. |
| `Year`, `Month`, `Day`, `Hour` | Extracted from the timestamp for time-based analysis. |

## 📊 Power BI Visualizations
The dashboard includes:
- **Sentiment distribution** pie chart.
- **Engagement by platform** bar chart (likes, retweets).
- **Hourly activity trends** line chart.
- **Geographic sentiment map** (based on country).
- **Top hashtags** and their relation to sentiment.

## 🔍 Insights Gained
- Most users shared **positive** sentiments across platforms.
- Engagement (likes/retweets) was highest on **Instagram** and **Twitter**.
- Peak activity times were between **12 PM to 7 PM**.
- Users from **USA, Canada, and Australia** showed different sentiment trends.




