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
![Image](https://github.com/user-attachments/assets/460b25fe-cf86-433b-a4ec-74bbd0a7e6cf)
| Metric                        | Description                                                                             |
|-------------------------------|-----------------------------------------------------------------------------------------|
| **Total Views**               | Cumulative content impressions                                                          |
| **Total Engagements**         | Sum of likes, shares, and comments                                                      |
| **Average Engagement Rate**   | (Total Engagements ÷ Total Views) × 100                                                 |
| **Performance Index**         | Engagement Rate ÷ Median Engagement Rate (values > 1 indicate above‑median performance) |

These KPIs provide an immediate snapshot of both scale (reach) and efficiency (how posts perform relative to the median), setting the context for deeper analysis.

---

## Metric & Hashtag Filters

- **Metric Selector:** Switch among Total Views, Total Engagement, Total Shares, and Avg. Engagement Rate to repurpose the bar chart without rebuilding visuals.  
- **Hashtag Slicer:** Choose any hashtag to isolate its performance across all charts in real-time.

These controls give on‑the‑fly diagnostics without navigating menus.

---

## Visualizations & Insights

### 1. Engagement Rate by Platform  
![Image](https://github.com/user-attachments/assets/ecc4958a-afb3-4716-b8de-39e7870e361b)
**Chart type:** Horizontal bar of engagement rate per 100 views by platform 
- **Purpose:** Compare each network’s ability to convert views into meaningful interactions.  
- **Insight:** Instagram leads at 13.83 %, closely followed by YouTube at 13.11 %. TikTok and Twitter register slightly lower rates (12.74 % and 12.79 % respectively). These differences, while numerically modest, signal where investment in creative formats and ad spend may yield the highest return in viewer engagement.

### 2. Content‑Format Mix across Platforms
![Image](https://github.com/user-attachments/assets/de4baea8-ee2e-429a-ac03-3de6da0035aa)
**Chart type:** Matrix (percentage distribution of content types by platform)  
- **Purpose:** Reveal which formats dominate each network and their associated engagement outcomes.  
- **Insight:** Instagram’s feed is dominated by **Reels (68 %)** and **Posts (54 %)**, correlating with a high overall engagement rate. YouTube’s emphasis on **Live Streams (87 %)** delivers sustained viewer interaction but a lower rate (50.6 %), indicating potential to diversify with shorter clips. TikTok’s **Shorts (92 %)** format performs consistently well, validating continued investment in bite‑sized content.

### 3. Performance Index Scatter  
![image](https://github.com/user-attachments/assets/8e8ca88d-3511-41c2-b74e-ee35d486e6d5)
**Chart type:** Scatter plot of Views (X‑axis) vs. Engagement Rate (Y‑axis), bubble size = shares, bubble color = Performance Index  
- **Purpose:** Surface individual posts or regions that outperform or underperform relative to the overall median engagement rate.  
- **Insight:** Bubbles in the **upper‑right quadrant** (high reach, high rate) represent “best‑in‑class” content worth replicating. Those in the **lower‑right** (high reach, low rate) signal under‑leveraged reach. Regions or hashtags falling **below the median** warrant creative or targeting adjustments.  

### 4. Global Reach: Views & Engagement by Region
![image](https://github.com/user-attachments/assets/b803ad0a-7b48-43da-bb2d-1de9200c74bd)
**Chart type:** Bubble map where bubble size = total views and tooltips include first platform, first content type, first hashtag, and engagement rate.
- **Purpose:** Pinpoint geographic markets that generate volume versus those that drive strong per‑viewer engagement.  
- **Insight:** **North America** (USA & Canada) and **Europe** lead with the largest volume of views, reflecting mature social ecosystems. However, **India** and **Brazil** exhibit above‑median engagement rates (> 60 %), highlighting them as high‑potential markets for localized campaigns and partnerships

### 5. Top Hashtag: Reach vs. Engagement Quality
![image](https://github.com/user-attachments/assets/7ca02ddb-e587-4797-a64b-9fa8e9ec919b)
**Chart type:** Clustered columns (Total views, engagements, shares, and avg. engagement rate per hashtag)  
- **Purpose:** Evaluate which hashtags drive volume versus those that inspire engagement relative to their reach.  
- **Insight:** High‑reach tags such as **#Fitness** (1.2 billion views) and **#Education** (1.1 billion views) deliver massive scale but moderate rates (approx. 11–12 %). In contrast, niche tags like **#Music** and **#Challenge** generate fewer views (300–500 million) yet achieve engagement rates above **16 %**, marking them as high‑value additions to any campaign toolkit.

### 6. Engagement Composition  
![image](https://github.com/user-attachments/assets/0d65854e-d549-44c9-99e2-42990c0fa315)

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
