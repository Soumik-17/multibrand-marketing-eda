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

## Challenges Faced

- **Duplicate-looking columns**: Target_Audience and Customer_Segment both used the exact same five categories (Youth, College Students, Working Women, Premium Shoppers, Tier 2 City Customers). I had to decide whether to treat them as two different things or one — I chose to analyze only Customer_Segment to avoid repeating the same breakdown twice under different names.
- **Multi-value column**: Channel_Used had comma-separated values (e.g. "Email, Instagram"), so a single campaign could belong to more than one channel. I had to split and explode this column before I could group by channel correctly — a straightforward groupby() would have undercounted every multi-channel campaign.
- **Unrealistic cost-to-revenue ratio**: When I calculated ROAS (Revenue ÷ Acquisition Cost) myself, the numbers came out at roughly 1,300x, which isn't realistic for any real marketing campaign. This suggested the Revenue and Acquisition_Cost columns were likely on different scales. Instead of reporting a misleading ratio, I decided to rely on the dataset's own ROI column and other normalized metrics (CTR%, Conversion Rate%) that don't depend on comparing those two columns directly.
- **Near-identical brand performance**: All three brands came out almost the same on every top-level metric (revenue, ROI, CTR), which made it clear this is a synthetic/practice dataset rather than real business data. This changed how I framed the insights — instead of saying "Brand X is better," I focused on smaller, more specific differences (like campaign type or channel) where real patterns did show up.
- **Kaggle access from a sandboxed environment**: I originally tried to pull the dataset directly using kagglehub inside a restricted environment, which failed due to network/auth restrictions. I worked around this by downloading the CSVs locally first and loading them directly with pandas.read_csv().

## Note

The dataset used in this project is taken from [Kaggle](https://www.kaggle.com/datasets/sshriya08/multi-brand-marketing-campaign-performance-dataset), and the business problem described above is a hypothetical scenario created for practice purposes only.
