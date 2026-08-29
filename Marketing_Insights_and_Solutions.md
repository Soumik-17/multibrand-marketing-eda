# Marketing Insights and Solutions

**Answers to the Business Problems — Nykaa vs Purplle vs Tira**

Prepared by: Soumik Bhul, Data Analyst (Fresher)
Date: August 2026

---

## A Quick Note Before the Insights

This looks like a practice / sample dataset rather than a brand's real financial data — for example, the three brands perform almost identically overall, which is unlikely in real life. So instead of leaning on absolute revenue or cost figures, I focused on things that are safe to compare: ROI (already given in the data), Click-Through Rate, Conversion Rate, and relative cost-per-conversion. These tell a more reliable story than raw currency numbers, and the same approach would still work if this were replaced with real brand data.

---

## 1. Which brand is performing better?

I compared all three brands on the metrics that matter most: how many people click, how many convert, and the average ROI per campaign.

| Brand | Campaigns | Avg ROI | CTR % | Conversion Rate % |
|---|---|---|---|---|
| Nykaa | 55,555 | 2.71 | 8.51% | 55.02% |
| Purplle | 55,555 | 2.68 | 8.50% | 54.98% |
| Tira | 55,555 | 2.67 | 8.50% | 54.97% |

> **What this means:** All three brands are running roughly the same number of campaigns and getting very similar results. Nykaa is marginally ahead on ROI (2.71 vs 2.68 and 2.67), but the gap is small — not something to make a big strategic call on by itself. The real differences show up when we break things down by campaign type, channel, and segment (next sections).

**Recommendation:** Don't treat this as "Nykaa is winning, copy everything Nykaa does." Instead, look inside each brand for the specific campaign types and channels that are actually pulling their numbers up or down — that's where the real opportunity is.

---

## 2. Best campaign type: revenue vs ROI

For each brand, I checked which campaign type brought in the most revenue, and separately, which one had the best average ROI. They are not always the same campaign type.

| Brand | Highest Revenue | Highest ROI |
|---|---|---|
| Nykaa | Influencer | Social Media (2.75) |
| Purplle | Email | Email (2.70) |
| Tira | Paid Ads | Paid Ads (2.72) |

> **What this means:** For Purplle and Tira, the campaign type bringing the most revenue also gives the best ROI — that's a good sign, it means their top revenue driver is also efficient. For Nykaa, Influencer campaigns bring the most total revenue, but Social Media campaigns are actually more efficient per rupee spent (higher ROI). Nykaa is likely spending more on Influencer campaigns simply because they scale up revenue, not because they are the most efficient.

**Recommendation:** Nykaa's team should test shifting a portion of the Influencer budget into Social Media campaigns and track if overall ROI improves, since Social Media already shows better returns per campaign.

---

## 3. Which channel to push, and which to pull back on

I looked at cost per conversion for each channel within each brand (lower cost per conversion = more efficient channel).

| Brand | Best Channel (most efficient) | Weakest Channel (least efficient) |
|---|---|---|
| Nykaa | Email | Google |
| Purplle | Email | YouTube |
| Tira | Facebook | YouTube |

> **What this means:** Email is the strongest channel for both Nykaa and Purplle. YouTube shows up as the weakest channel for two out of three brands (Purplle and Tira), and Google is the weakest for Nykaa. This is consistent enough across brands to be a real pattern, not noise.

**Recommendation:** Shift a small, test portion of YouTube and Google budget toward Email (and Facebook for Tira) for one quarter, and compare conversion rates before rolling out a bigger budget change. Since all channels are fairly close in performance, this should be tested gradually rather than all at once.

---

## 4. Which customer segment to prioritize

Each brand's customers were grouped into five segments: Youth, College Students, Working Women, Premium Shoppers, and Tier 2 City Customers. I compared segments by total revenue and by average ROI.

| Brand | Best Segment (Revenue) | Best Segment (ROI) | Weakest Segment (ROI) |
|---|---|---|---|
| Nykaa | Working Women | Working Women (2.77) | Youth (2.68) |
| Purplle | Youth | College Students (2.74) | Premium Shoppers (2.63) |
| Tira | Youth | Youth (2.72) | Premium Shoppers (2.61) |

> **What this means:** Premium Shoppers is the weakest segment on ROI for both Purplle and Tira, even though this segment still brings in decent revenue. That's a warning sign — the brand is spending money to reach these customers, but not getting the best return compared to other segments. For Nykaa, Youth is the underperforming segment instead.

**Recommendation:** Purplle and Tira should review what's being spent on Premium Shopper campaigns — either the messaging isn't landing with this group, or the acquisition cost for reaching them is too high. Nykaa should do the same check for its Youth segment. Meanwhile, Working Women (Nykaa), College Students (Purplle) and Youth (Tira) are the safest segments to increase spend on.

---

## 5. Does campaign duration affect ROI?

Campaigns were grouped into duration bands: 1–7 days, 8–14 days, and 15–30 days (very few campaigns ran longer than that). Here is the average ROI for each band, by brand:

| Brand | 1–7 Days | 8–14 Days | 15–30 Days | Best Band |
|---|---|---|---|---|
| Nykaa | 2.65 | 2.69 | 2.74 | 15–30 days |
| Purplle | 2.73 | 2.67 | 2.68 | 1–7 days |
| Tira | 2.66 | 2.72 | 2.66 | 8–14 days |

> **What this means:** There isn't one "right" campaign length that works for every brand — the best duration is different for each one, and the ROI differences between bands are small (roughly 2.6 to 2.75 across the board). So campaign duration on its own is not a major lever for improving ROI.

**Recommendation:** Don't force a single "ideal campaign length" rule across all three brands. Instead, each brand should keep running its current mix of durations, and focus improvement efforts on channel and segment choices instead, which show bigger, more consistent differences.

---

## 6. Does customer engagement predict revenue and ROI?

I checked how Engagement Score (a measure of how much customers interacted with a campaign) relates to Revenue, Conversions, and ROI, across all three brands combined.

| Relationship | Correlation Score | Strength |
|---|---|---|
| Engagement Score vs Conversions | 0.64 | Moderate to strong |
| Engagement Score vs Revenue | 0.56 | Moderate |
| Engagement Score vs ROI | 0.44 | Moderate |

> **What this means:** A correlation score closer to 1 means a stronger relationship. Here, campaigns with higher engagement scores do tend to get more conversions and more revenue — the link is real, just not perfect (other factors like channel and audience matter too).

**Recommendation:** Engagement Score is worth tracking as an early signal. If a campaign is live and its engagement score is trending low partway through, that's a sign it may under-deliver on revenue — worth reviewing the creative or targeting before the campaign ends, rather than waiting for final numbers.

---

## 7. Overall Recommendations for Next Quarter

- **Nykaa:** Shift some budget from Influencer to Social Media campaigns, and re-check spend on the Youth segment.
- **Purplle:** Protect and grow Email campaigns; review why Premium Shoppers give weaker ROI despite good revenue.
- **Tira:** Lean into Paid Ads and Facebook/Instagram; review Premium Shopper targeting, same as Purplle.
- **All brands:** Test moving a small share of YouTube (and Google, for Nykaa) budget into better-performing channels for one quarter before committing fully.
- **All brands:** Don't chase a single "best campaign duration" — the data doesn't support one. Focus optimization energy on channel and segment instead.
- **All brands:** Start tracking Engagement Score as an early warning signal during a campaign, not just after it ends.

## 8. Closing Note

Overall, the three brands are performing at a very similar level, so there is no single big fix. The real value here is in the smaller, specific patterns — like Nykaa's Influencer-vs-Social Media gap, or Premium Shoppers underperforming for two of the three brands. These are practical, testable changes each marketing team can try in the next quarter without needing a big budget increase.
