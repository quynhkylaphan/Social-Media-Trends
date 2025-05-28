# Social Media Trends & Engagement Dashboard

**Data Source**  
“Viral Social Media Trends and Engagement Analysis” by Atharva Soundankar (Kaggle)  
<https://www.kaggle.com/datasets/atharvasoundankar/viral-social-media-trends-and-engagement-analysis>

---

## Overview

This Power BI dashboard synthesizes detailed performance metrics from over **12 billion views** and **1.6 billion engagements** across four major platforms: Instagram, TikTok, Twitter, and YouTube. By combining high‑level KPIs with granular breakdowns by platform, hashtag, content format, and region, it enables stakeholders to:

1. Identify which channels deliver the greatest audience reach.  
2. Evaluate how effectively each channel converts views into likes, shares, and comments.  
3. Diagnose the optimal mix of content formats for each network.  
4. Target geographies with the strongest local engagement.  
5. Refine hashtag and call‑to‑action strategies for maximal impact.

---

## Key Performance Indicators

| Metric                   | Value           | Description                                 |
|--------------------------|-----------------|---------------------------------------------|
| **Total Views**          | 12,470,332,220  | Cumulative number of times content was seen.|
| **Total Engagements**    | 1,634,414,928   | Sum of likes, shares, and comments.         |
| **Average Engagement Rate** | 56.76 %       | (Total Engagements ÷ Total Views) × 100.    |

These KPIs provide an immediate snapshot of both scale (reach) and intensity (engagement efficiency), setting the context for deeper analysis.

---

## Visualizations & Insights

### 1. Platform Efficiency  
**Chart type:** Horizontal bar (Engagement rate per 100 views, by platform)  
- **Purpose:** Compare each network’s ability to convert views into meaningful interactions.  
- **Insight:** Instagram leads at 13.83 %, closely followed by YouTube at 13.11 %. TikTok and Twitter register slightly lower rates (12.74 % and 12.79 % respectively), indicating opportunities to refine content or targeting on these channels.

### 2. Hashtag Performance  
**Chart type:** Clustered columns (Total views, engagements, shares, and avg. engagement rate per hashtag)  
- **Purpose:** Evaluate which hashtags drive volume versus those that inspire engagement relative to their reach.  
- **Insight:** #Fitness and #Education generate the highest raw views (over 1 billion each), while #Music and #Challenge deliver above‑average engagement rates despite smaller audiences. This split informs a balanced hashtag strategy that prioritizes both scale and efficiency.

### 3. Content‑Format Mix  
**Chart type:** Matrix (percentage distribution of content types by platform)  
- **Purpose:** Reveal the predominant formats—Reels, Live streams, Shorts, Posts, Tweets, Videos—on each network.  
- **Insight:** Instagram’s content is 67.9 % Reels and 53.6 % Posts, yielding a 66.2 % engagement rate. YouTube emphasizes Live streams (86.8 %) with a 50.6 % rate, while TikTok is dominated by Shorts (over 90 %), guiding format‑specific resource allocation.

### 4. Regional Footprint  
**Chart type:** Bubble map (bubble size = total views; colour = engagement rate)  
- **Purpose:** Identify geographic markets with the heaviest traffic and the strongest engagement.  
- **Insight:** North America and Europe account for the bulk of views, whereas India and Brazil exhibit higher engagement rates relative to their audience size. These patterns support decisions on localization, language customization, and regional ad spend.

### 5. Engagement Composition  
**Chart type:** 100 % stacked bar (likes vs. shares vs. comments by platform)  
- **Purpose:** Understand the qualitative mix of engagement actions to tailor calls‑to‑action and creative prompts.  
- **Insight:** Across all platforms, likes represent the majority (≈ 76 %), shares account for 15–16 %, and comments make up 7–8 %. Notably, TikTok shows a marginally higher comment share, suggesting potential to encourage user discussion in future campaigns.

---

## Strategic Recommendations

1. **Optimize Budget Allocation**  
   - Increase creative investment on platforms with both high reach and superior engagement rates (e.g., Instagram, YouTube).  
2. **Refine Hashtag Selection**  
   - Combine broad‑reach tags (e.g., #Fitness) with niche, high‑efficiency tags (e.g., #Challenge) to maximize overall campaign ROI.  
3. **Align Content Formats**  
   - Double down on Reels for Instagram and Live streams for YouTube, while experimenting with Shorts‑style clips on TikTok.  
4. **Localize for High‑Engagement Regions**  
   - Customize messaging, language, and scheduling for audiences in India and Brazil to capitalize on strong engagement.  
5. **Targeted Calls‑to‑Action**  
   - On platforms where shares lag, explicitly prompt users to share; on networks with higher comment rates, encourage community discussion or feedback.

---

## Implementation Notes

- **Filters & Interactivity:** Slicers for platform, hashtag, content type, and date allow on‑the‑fly segmentation and comparison.  
- **Performance Index Scatter Plot:** Highlights over‑ and under‑performing posts or regions relative to the median engagement rate.  
- **Data Refresh:** Connects to the Kaggle CSV via Power BI Gateway for scheduled daily updates.  

---

_This dashboard transforms raw social engagement data into actionable insights, empowering marketing teams to make data‑driven decisions, optimize content strategy, and allocate resources for maximal impact._  
