# Available .DAY One-Word Domains (12,265)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C265%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .day one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,265 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,265 domains · **Median ask:** $69.85 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
**Canonical page:** `https://unique.domains/domains/tld/day`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/day?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./day.csv">CSV</a> / <a href="./day.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DAY search](https://unique.domains/domains/tld/day?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DAY search](https://unique.domains/domains/tld/day?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DAY one-word domain catalog.

### Files

- `day.csv` — public CSV extract (1,000 rows)
- `day.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/day-oneword-domains/main/day.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| keepthechange.day | available | $16.98    | —             | 46             | 59     | 15     | namecheap |
| insight.day       | premium   | $161.25   | —             | 76             | 69     | 8      | name.com  |
| commonground.day  | available | $16.98    | —             | 74             | 28     | 13     | namecheap |
| farmers.day       | premium   | $161.25   | —             | 54             | 59     | 7      | name.com  |
| motorsport.day    | available | $16.98    | —             | 74             | 23     | 10     | namecheap |
| skills.day        | premium   | $623.75   | —             | 58             | 47     | 6      | name.com  |
| HarryPotter.day   | available | $16.98    | —             | 72             | 20     | 12     | namecheap |
| jobs.day          | premium   | $1,248.75 | —             | 79             | 42     | 4      | name.com  |
| smartest.day      | available | $16.98    | —             | 64             | 20     | 8      | namecheap |
| whynot.day        | premium   | $161.25   | —             | 74             | 39     | 7      | name.com  |
| whitewater.day    | available | $16.98    | —             | 82             | 17     | 11     | namecheap |
| WiFi.day          | premium   | $698.60   | $698.60       | 83             | 37     | 5      | namecheap |
| Automobiles.day   | available | $16.98    | —             | 62             | 17     | 11     | namecheap |
| teams.day         | premium   | $161.25   | —             | 62             | 32     | 5      | name.com  |
| bonvoyage.day     | available | $16.98    | —             | 88             | 16     | 10     | namecheap |
| partners.day      | premium   | $311.25   | —             | 61             | 32     | 8      | name.com  |
| gearup.day        | available | $16.98    | —             | 80             | 16     | 7      | namecheap |
| William.day       | premium   | $348.60   | $348.60       | 74             | 31     | 7      | namecheap |
| runners.day       | available | $16.98    | —             | 78             | 16     | 7      | namecheap |
| solutions.day     | premium   | $623.75   | —             | 56             | 31     | 9      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,265 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/day?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/day?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is entirely focused on one-word .day domains. The naming style is concise and easy to scan, but the extension gives each term a time-based or event-driven feel. That can work well for campaigns, editorial concepts, recurring experiences, and brands that want a distinctive ending. In this selection, examples range from broad words such as wise.day and care.day to sharper terms like analyst.day, breakeven.day, and evil.day. When comparing these domains, start with word strength first: clarity, memorability, and fit with the meaning created by .day. Then check ask price, renewal terms, pronunciation, and any trademark conflicts around the exact word in your target market.

- One-word .day names with concise, memorable wording
- Median ask across this selection is $69.85
- Strong fits include editorial, event, and campaign concepts
- Check exact-word trademark risk before committing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DAY One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DAY page](https://unique.domains/domains/tld/day?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
