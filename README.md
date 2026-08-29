# Multi-Brand Marketing Campaign Performance Analysis

Exploratory data analysis of digital marketing campaign performance across three online beauty and personal care brands — **Nykaa**, **Purplle**, and **Tira**.

## Scenario

Imagine you're a data analyst working with a company that owns three online beauty and personal care brands: Nykaa, Purplle, and Tira. Each brand runs its own digital marketing campaigns independently, across channels like Email, Instagram, Facebook, Google, YouTube, and WhatsApp.

Right now, each brand's marketing team only tracks its own campaigns. Nobody has looked at all three brands together to see which one is using its marketing budget more wisely, and which campaign types, channels, or customer segments are actually driving results.

Marketing leadership has asked for one year of campaign data (July 2024 to June 2025) to be studied across all three brands, so the team can understand where the marketing spend is working, and where it isn't, before planning next quarter's budget.

## Business Problem

The analysis was built to answer the following questions:

1. Which brand is currently getting better results from its marketing spend, and by how much?
2. Within each brand, which campaign type (Influencer, Paid Ads, Email, SEO, Social Media) brings in the most revenue, and is that the same campaign type that gives the best ROI?
3. Which marketing channel should each brand push more budget into, and which channel is underperforming?
4. Which customer segment should each brand focus on going forward, and is there a segment that gets a lot of spend but gives a weak return?
5. Does campaign duration (short vs long) actually affect performance?
6. Is there a real connection between customer engagement and how much revenue or ROI a campaign generates?
7. Based on all of the above, what should each brand's marketing team actually do differently next quarter?

## About the Dataset

- **3 CSV files**, one per brand: Nykaa, Purplle, and Tira campaign data
- **166,665 total records** combined (about 55,555 campaigns per brand)
- No missing values, no duplicate rows
- **Date range:** 1 July 2024 to 24 June 2025
- **Key columns:** Campaign Type, Target Audience, Customer Segment, Channel Used, Language, Duration, Impressions, Clicks, Leads, Conversions, Revenue, Acquisition Cost, ROI, Engagement Score

## Tools and Requirements

- **Python 3**
- **pandas** — data loading, cleaning, and aggregation
- **matplotlib** and **seaborn** — visualizations and missing value checks
- **Jupyter Notebook** — for running the EDA step by step
- **kagglehub** — to download the dataset directly from Kaggle

## Project Files

| File | Description |
|---|---|
| `notebooks/marketing-eda.ipynb` | Full exploratory data analysis notebook |
| `Business_Problem_Statement.md` | Scenario, dataset overview, and business questions |
| `Marketing_Insights_and_Solutions.md` | Answers to each business question with data, insights, and recommendations |

## Note

The dataset used in this project is taken from [Kaggle](https://www.kaggle.com/datasets/sshriya08/multi-brand-marketing-campaign-performance-dataset), and the business problem described above is a hypothetical scenario created for practice purposes only.
