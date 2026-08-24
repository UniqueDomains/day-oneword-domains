# Available .DAY One-Word Domains (18,735)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-18%2C735%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .day one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **18,735 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 18,735 domains · **Median ask:** $68.01 · **High-demand under $2,500:** 19

**Last updated:** 2026-08-24
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

- `day.csv`, public CSV extract (1,000 rows)
- `day.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/day-oneword-domains/main/day.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| boer.day  | available | $12.98    | $16.98        | low            | low    | 4      | namecheap   |
| dick.day  | resell    | —         | —             | medium         | low    | 4      | Porkbun LLC |
| add.day   | premium   | $623.75   | —             | high           | low    | 3      | name.com    |
| clxx.day  | available | $12.98    | $16.98        | low            | low    | 4      | namecheap   |
| bce.day   | premium   | $73.75    | —             | medium         | low    | 3      | name.com    |
| howl.day  | available | $16.98    | —             | high           | low    | 4      | namecheap   |
| btw.day   | premium   | $73.75    | —             | high           | low    | 3      | name.com    |
| lxxi.day  | available | $12.98    | $16.98        | low            | low    | 4      | namecheap   |
| dad.day   | premium   | $1,248.75 | —             | high           | low    | 3      | name.com    |
| torn.day  | available | $16.98    | —             | medium         | low    | 4      | namecheap   |
| dry.day   | premium   | $161.25   | $161.25       | high           | low    | 3      | name.com    |
| veal.day  | available | $16.98    | —             | medium         | low    | 4      | namecheap   |
| dvd.day   | premium   | $311.25   | —             | high           | low    | 3      | name.com    |
| xxxv.day  | available | $12.98    | $16.98        | low            | low    | 4      | namecheap   |
| ego.day   | premium   | $623.75   | —             | medium         | low    | 3      | name.com    |
| aftuh.day | available | $16.98    | —             | medium         | low    | 5      | namecheap   |
| fit.day   | premium   | $1,248.75 | —             | high           | medium | 3      | name.com    |
| anile.day | available | $12.98    | $16.98        | low            | low    | 5      | namecheap   |
| hug.day   | premium   | $161.25   | —             | high           | low    | 3      | name.com    |
| ashen.day | available | $12.98    | $16.98        | low            | low    | 5      | namecheap   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 18,735 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 19 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/day?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/day?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection covers one-word and short-phrase .day domain names such as jetblack.day, tips.day, and feel.day. With 12,266 domains and a median ask near $105, the set spans everyday verbs, niche activities, and calendar-inspired terms — offering both quick, ownable picks for founders and a broad base for investors scanning early TLD adoption.

- 12,266 one-word .day domains in this set
- Median ask near $105 — budget-friendly entry point
- Mix of short verbs, niche terms & calendar-style names
- Updated daily to reflect current listings

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DAY One-Word Domains*. Version 2026-08-24. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DAY page](https://unique.domains/domains/tld/day?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_day_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
