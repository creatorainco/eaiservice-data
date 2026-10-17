# Evaluate AI Service: AI software review and price data

Review records and plan prices for AI software used by restaurants and small businesses: cold email tools, AI voice agents, influencer marketing platforms, restaurant marketing platforms and workflow automation. This repository mirrors the open data published at https://eaiservice.com/data/. The same two files are archived on Zenodo (DOI 10.5281/zenodo.23210349, always the latest version) and on Kaggle (https://www.kaggle.com/datasets/evaluateaiservice/ai-software-review-and-price-data).

**Ownership.** Evaluate AI Service is published by Midwest AI Solution Inc. (Atlanta, Georgia). We also make CreatoRain (https://www.creatorain.com/), one of the tools in this data. CreatoRain is listed but never scored, and its price rows carry `is_our_product=true`. Tools made by business partners of CreatoRain are marked in the `relationship` column. More at https://eaiservice.com/ownership/.

## Files

| File | What it holds |
|---|---|
| `data/reviews.json` | One record per review: evidence score and criterion scores (1-5), plan prices as the review words them, free plan or trial, sources with the dates we read them, and a count of the Reddit threads we read. |
| `data/prices.csv` | One row per published plan price: tool, category, plan, billing, price_usd, unit, read_date, source_url, price_text, period, is_our_product, relationship, disclosure, review_url. |

Scores are evidence scores built from vendor pages, pricing and public user reports, not hands-on tests. The method is at https://eaiservice.com/methodology/.

## Updates

The source of truth is https://eaiservice.com/data/. Both files there are rebuilt from the review files every time the site is published, so a figure always matches the review page it came from. This mirror is refreshed when prices are re-read. Last refreshed from the site: 2026-10-17.

Found a wrong price or a dead source? Email corrections@eaiservice.com.

## License and citation

CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Credit: "Evaluate AI Service (eaiservice.com), published by Midwest AI Solution Inc."

```
Evaluate AI Service. (2026). AI software review and price data [Data set]. Midwest AI Solution Inc. https://doi.org/10.5281/zenodo.23210349
```
