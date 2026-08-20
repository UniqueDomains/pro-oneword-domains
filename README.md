# Available .PRO One-Word Domains (69,328)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-69%2C328%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .pro one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **69,328 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 69,328 domains · **Median ask:** $95.24 · **High-demand under $2,500:** 112

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/pro`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/pro?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./pro.csv">CSV</a> / <a href="./pro.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PRO search](https://unique.domains/domains/tld/pro?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PRO search](https://unique.domains/domains/tld/pro?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PRO one-word domain catalog.

### Files

- `pro.csv`, public CSV extract (1,000 rows)
- `pro.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/pro-oneword-domains/main/pro.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                            |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------ |
| auld.pro   | available | $3.48     | $33.98        | low            | low    | 4      | namecheap                            |
| acre.pro   | resell    | —         | —             | medium         | low    | 4      | AccentDomains LLC                    |
| but.pro    | premium   | $242      | $242          | high           | low    | 3      | namesilo                             |
| lvii.pro   | available | $3.48     | $33.98        | low            | low    | 4      | namecheap                            |
| airy.pro   | resell    | —         | —             | high           | low    | 4      | Epik LLC                             |
| day.pro    | premium   | $3,125    | —             | high           | low    | 3      | name.com                             |
| tush.pro   | available | $3.48     | $33.98        | low            | low    | 4      | namecheap                            |
| clam.pro   | resell    | —         | —             | high           | low    | 4      | Unstoppable Domains Inc              |
| DJI.pro    | premium   | $500      | —             | high           | low    | 3      | name.com                             |
| abbot.pro  | available | $4.99     | $33.99        | medium         | high   | 5      | name.com                             |
| flag.pro   | resell    | —         | —             | high           | high   | 4      | Registrar of Domain Names REG.RU LLC |
| hic.pro    | premium   | $242      | $242          | high           | low    | 3      | namesilo                             |
| damned.pro | available | $3.58     | $29.49        | medium         | low    | 6      | namesilo                             |
| kill.pro   | resell    | —         | —             | medium         | low    | 4      | Sav.com, LLC - 8                     |
| docile.pro | available | $3.48     | $33.98        | low            | low    | 6      | namecheap                            |
| oslo.pro   | resell    | —         | —             | medium         | low    | 4      | Sav.com, LLC - 35                    |
| gaslit.pro | available | $4.99     | —             | medium         | low    | 6      | name.com                             |
| pass.pro   | resell    | —         | —             | high           | medium | 4      | Dynadot3 LLC                         |
| getto.pro  | available | $3.58     | $29.49        | high           | low    | 6      | namesilo                             |
| rail.pro   | resell    | —         | —             | high           | low    | 4      | Dynadot Inc                          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 69,328 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 112 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/pro?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/pro?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=related_pricing)

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

This is a list of one-word .PRO domain names, spanning everyday words, action verbs, and short brandable terms such as clay.pro, sauce.pro, and understand.pro. The .PRO extension began as a professional-focused alternative to .com and now hosts a wide range of ownable, single-word names. Across this set of 66,334 domains, the median asking price is about $184.40, giving both founders and investors a consistent reference point for comparing value across listings.

- 66,334 one-word .PRO domain names in this set
- Median asking price: $184.40
- Short, brandable names like clay.pro and facts.pro
- Updated daily to reflect current availability and pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PRO One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PRO page](https://unique.domains/domains/tld/pro?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
