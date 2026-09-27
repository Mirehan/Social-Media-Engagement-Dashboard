# Social Media Engagement Dashboard

A Power BI dashboard analyzing social media engagement across 10+ global brands 
(Adidas, Apple, Amazon, Samsung, Nike, Pepsi, Coca-Cola, Toyota, Google, Microsoft), 
tracking post volume, engagement, sentiment, and platform performance across 
pre-launch, launch, and post-launch campaign phases.

## Tools Used
- Power BI (data modeling, DAX measures, interactive visuals)
- Excel / CSV for source data

## Dataset
~12K social media posts across 5 platforms (Reddit, Facebook, Instagram, Twitter, 
YouTube), tagged with brand, product, campaign phase, keywords, hashtags, emotion 
type, location, and language.

## Key Insights

- **Scale:** The dataset covers ~12K posts generating 48.0M engagements and 597.74M 
  impressions, for an overall engagement rate of 8%.
- **Platform performance is uneven:** Reddit and Facebook post the highest engagement 
  rates (~5%), while YouTube, Twitter, and Instagram trail closer to 2%, suggesting 
  discussion-driven platforms outperform passive-content ones for this brand set.
- **Engagement is spike-driven, not steady:** the time-series shows sharp spikes 
  (up to 3,000%+) against a near-zero baseline, pointing to a small number of viral 
  posts driving most engagement rather than consistent organic growth.
- **Brand engagement is tightly clustered:** most brands sit in a narrow 57M–63M 
  engagement band, no single brand dominates, worth investigating as a possible 
  normalization artifact in the source data.
- **Emotion split is evenly distributed:** Sad, Excited, Happy, Angry, and Confused 
  each represent ~20% of tagged posts, a near-perfectly even split that (combined 
  with flat sentiment/toxicity scores) suggests this is a simulated dataset rather 
  than live scraped data.
- **Topic-level buzz varies sharply:** "Marketing" and "Delivery" topics show the 
  highest impressions and buzz swings, useful for prioritizing where a brand's 
  social team should focus response efforts.

## Dashboard Pages
1. **Overview** — high-level KPIs and the full post-level data table
2. **Details** — engagement trends, platform comparison, emotion breakdown, and 
   per-brand/per-product engagement

## How to Use
1. Download `Social Media Engagement.pbix` from this repo
2. Open in Power BI Desktop
3. Use the filter panel (left sidebar) to slice by brand, platform, or campaign phase
