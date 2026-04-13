# Available .PRO One-Word Domains (65,635)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-65%2C635%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .pro one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **65,635 domains** on the canonical page below.

**Public extract:** 10,000 rows · **Live catalog:** 65,635 domains

**Last updated:** 2026-04-13  
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

- `pro.csv` — public CSV extract (10,000 rows)
- `pro.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/pro-oneword-domains/main/pro.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain                | status    | ask_price | renewal_price | attractiveness | demand | length | registrar               |
| --------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------- |
| AbeLincoln.pro        | available | $30.98    | —             | 68             | 80     | 11     | namecheap               |
| training.pro          | resell    | $9,459.90 | $33.99        | 70             | 88     | 8      | Porkbun LLC             |
| aah.pro               | premium   | $500      | $500          | 114            | 92     | 3      | name.com                |
| hosiery.pro           | available | $30.98    | —             | 64             | 80     | 7      | namecheap               |
| textbook.pro          | resell    | —         | —             | 84             | 98     | 8      | Epik LLC                |
| zzz.pro               | premium   | $1,300    | $1,300        | 88             | 88     | 3      | namecheap               |
| airtrafficcontrol.pro | available | $30.98    | —             | 62             | 80     | 19     | namecheap               |
| rude.pro              | resell    | —         | —             | 68             | 98     | 4      | Unstoppable Domains Inc |
| ore.pro               | premium   | $520      | $520          | 58             | 76     | 3      | namecheap               |
| drinkingwater.pro     | available | $30.98    | —             | 60             | 80     | 14     | namecheap               |
| bare.pro              | resell    | —         | —             | 66             | 98     | 4      | Unstoppable Domains Inc |
| PBX.pro               | premium   | $1,300    | $1,300        | —              | 64     | 3      | namecheap               |
| canvassing.pro        | available | $30.98    | —             | 56             | 80     | 10     | namecheap               |
| motto.pro             | resell    | —         | —             | 86             | 96     | 5      | Dynadot Inc             |
| like.pro              | premium   | $11,500   | $35.99        | 84             | 35     | 4      | NameCheap, Inc.         |
| abbot.pro             | available | $4.99     | $33.99        | 50             | 80     | 5      | name.com                |
| subway.pro            | resell    | —         | —             | 84             | 96     | 6      | Sav.com, LLC - 42       |
| sly.pro               | premium   | $500      | $500          | 60             | 19     | 3      | name.com                |
| armedforces.pro       | available | $30.98    | —             | 50             | 80     | 12     | namecheap               |
| gadget.pro            | resell    | —         | —             | 74             | 96     | 6      | Porkbun LLC             |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract           | Unique Domains                                   |
| ------------------------ | ------------------------------------------------ |
| 10,000-row public sample | 65,635 live domains                              |
| Static CSV / JSON        | live search and daily refresh                    |
| Basic exported fields    | deeper price, demand, risk, and workflow context |
| No persistence           | Radar, saved search, and alerts                  |
| No founder workflow      | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/pro?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/pro?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PRO One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PRO page](https://unique.domains/domains/tld/pro?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_pro_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
