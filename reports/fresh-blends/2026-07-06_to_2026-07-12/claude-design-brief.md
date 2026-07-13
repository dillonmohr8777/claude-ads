# Fresh Blends Ã— Kwik Trip â€” Claude design brief

Use `report-data.json` as the source of truth for this week's July 6â€“12, 2026 report.

## How to retrieve the data

From the GitHub repository root, fetch the raw JSON and save it locally:

```bash
curl -L "https://raw.githubusercontent.com/dillonmohr8777/claude-ads/main/reports/fresh-blends/2026-07-06_to_2026-07-12/report-data.json" -o report-data.json
```

Then read `report-data.json` before writing any slide copy. Do not infer current metrics from the old PowerPoint or from the historical rows.

## Core story

This is a pause-state report, not an active-delivery performance report:

- All four Fresh Blends Ã— Kwik Trip locations are paused: #1110, #1161, #573, and #633.
- Mia confirmed the pause on July 9, 2026.
- The connected current-week export was not verified.
- Current-week CPC, CTR, spend, impressions, clicks, Get Directions, and cost per direction must display as `N/A`.

## Required benchmark hero

Include a large, visually dominant benchmark comparison slide or card using the historical label exactly:

> Last verified CPC was 79.5% below the $2.05 Restaurants & Food benchmark.

This compares the Fresh Blends-only June 29â€“July 5 verified CPC of $0.42 with the $2.05 industry benchmark. It is historical context only. Do not write that July 6â€“12 performance was 79.5% better, because the campaigns were paused and this week's export is unverified.

If the secondary comparison is used, label it historical too: June cost per Get Direction was $2.71 versus an approximately $21 benchmark, or about 87.1% below benchmark.

## Slide direction

Reuse the prior paid-media visual system: dark green/white foundation, orange emphasis for the main action KPI, large numeric cards, compact campaign/location table, and clean white M logo only. Do not place the word Momentum beside the logo.

Recommended sequence:

1. Cover: `Fresh Blends Ã— Kwik Trip` and `Campaigns paused Â· July 6â€“12 delivery unverified`.
2. At-a-glance pause state: `PAUSED`, `N/A CPC / CTR`, `N/A Get Directions`, `N/A verified spend`.
3. Benchmark hero: historical 79.5% below benchmark, with the date range and $0.42 versus $2.05 shown directly under the headline.
4. Location status: four rows, all `PAUSED`.
5. Restart readiness: confirm locations, offer, budget, dates, and restore a verified export before relaunch.
6. Closing recap: campaigns remain paused; resume verified reporting only after seven complete days of delivery.

## Guardrails

- Keep Fresh Blends / Kwik Trip / Ice Box separate from Replenish / 7-Eleven.
- Do not reuse the old 166 Get Directions total or the old six-campaign totals as current Fresh Blends truth.
- Do not replace missing data with zero.
- Keep historical benchmark comparisons clearly labeled as historical.
- Do not claim a current-week performance lift while current-week delivery is unverified.
