# Business Problem Statement

**Multi-Brand Marketing Campaign Performance Analysis**

Prepared by: [Your Name], Data Analyst (Fresher)
Date: August 2026

---

## 1. Background

This project looks at digital marketing campaign data from three online beauty and personal care brands: Nykaa, Purplle, and Tira. Each brand runs its own marketing campaigns across different channels like Email, Instagram, Facebook, Google, YouTube, and WhatsApp.

Right now, each brand's marketing team tracks its own campaigns separately. Nobody has looked at all three brands together to see which one is spending its marketing budget more wisely, and which campaign types, channels, or customer groups are actually working.

As a data analyst, I was asked to study one year of campaign data (July 2024 to June 2025) across all three brands and figure out where the marketing money is working well, and where it isn't.

## 2. About the Data

The dataset has 3 files, one for each brand. After combining them, here is what the data looks like:

- 166,665 total campaign records (about 55,555 campaigns per brand)
- No missing values and no duplicate rows
- Date range: 1 July 2024 to 24 June 2025
- Key columns: Campaign Type, Target Audience, Customer Segment, Channel Used, Language, Duration, Impressions, Clicks, Leads, Conversions, Revenue, Acquisition Cost, ROI, Engagement Score

**Note:** The Target Audience and Customer Segment columns use the exact same categories (College Students, Working Women, Youth, Premium Shoppers, Tier 2 City Customers). So instead of analyzing both separately, I mainly used Customer Segment to avoid repeating the same analysis twice under a different name.

## 3. Business Problems to Solve

Marketing leadership wants clear, data-backed answers to the following questions, so the same budget can be used more effectively next quarter:

1. Which brand is currently getting better results from its marketing spend, and by how much?
2. Within each brand, which campaign type (Influencer, Paid Ads, Email, SEO, Social Media) brings in the most revenue, and is that the same campaign type that gives the best ROI?
3. Which marketing channel should each brand push more budget into, and which channel is underperforming and dragging down efficiency?
4. Which customer segment should each brand focus on going forward, and is there a segment that gets a lot of spend but gives a weak return?
5. Does the length of a campaign (short vs long) actually change how well it performs, or does duration not matter much?
6. Is there a real connection between how engaged customers are with a campaign and how much revenue or ROI that campaign generates?
7. Based on all of the above, what should each brand's marketing team actually do differently in the next quarter?

## 4. Goal of This Analysis

The end goal is not just to describe the data, but to turn it into a short list of practical recommendations that each brand's marketing team can act on — things like which channel to invest more in, which segment to target, and which campaign type to run more often.

## 5. What Comes Next

The answers to each of the questions above, along with the supporting numbers and recommendations, are documented in the companion file: [`Marketing_Insights_and_Solutions.md`](./Marketing_Insights_and_Solutions.md).
