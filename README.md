# Available .SEXY One-Word Domains (12,713)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C713%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .sexy one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,713 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,713 domains · **Median ask:** $4,510.66 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/sexy`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/sexy?utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./sexy.csv">CSV</a> / <a href="./sexy.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SEXY search](https://unique.domains/domains/tld/sexy?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SEXY search](https://unique.domains/domains/tld/sexy?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SEXY one-word domain catalog.

### Files

- `sexy.csv` — public CSV extract (1,000 rows)
- `sexy.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/sexy-oneword-domains/main/sexy.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| insight.sexy  | available | $2,999    | —             | 76             | 69     | 8      | name.com  |
| Cats.sexy     | resell    | —         | —             | 59             | 33     | 4      | NAMECHEAP |
| nets.sexy     | premium   | $12,500   | —             | 54             | 81     | 4      | name.com  |
| makers.sexy   | available | $2,749.99 | $2,749.99     | 62             | 67     | 6      | namesilo  |
| knows.sexy    | resell    | —         | —             | 48             | 20     | 5      | NAMECHEAP |
| jobs.sexy     | premium   | $12,500   | —             | 79             | 42     | 4      | name.com  |
| online.sexy   | available | $2,999    | —             | 70             | 62     | 7      | name.com  |
| coins.sexy    | premium   | $12,500   | —             | 56             | 41     | 5      | name.com  |
| RedSox.sexy   | available | $3,298    | —             | 72             | 60     | 7      | namecheap |
| lets.sexy     | premium   | $12,500   | —             | 77             | 39     | 4      | name.com  |
| skills.sexy   | available | $2,999    | —             | 58             | 47     | 6      | name.com  |
| teams.sexy    | premium   | $12,500   | —             | 62             | 32     | 5      | name.com  |
| whynot.sexy   | available | $2,999    | —             | 74             | 39     | 7      | name.com  |
| pages.sexy    | premium   | $12,500   | —             | 52             | 28     | 5      | name.com  |
| tokens.sexy   | available | $2,749.99 | $2,749.99     | 51             | 36     | 6      | namesilo  |
| KFC.sexy      | premium   | $35,000   | $35,000       | 74             | 27     | 3      | namecheap |
| aliens.sexy   | available | $2,749.99 | $2,749.99     | 56             | 35     | 6      | namesilo  |
| sites.sexy    | premium   | $12,500   | —             | 53             | 26     | 5      | name.com  |
| partners.sexy | available | $2,999    | —             | 61             | 32     | 8      | name.com  |
| Keith.sexy    | premium   | $14,000   | $14,000       | 66             | 25     | 5      | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,713 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/sexy?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/sexy?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of one-word .sexy domains. The names range from clean dictionary words such as care.sexy and influence.sexy to more specific terms like antiseptic.sexy and adjunct.sexy. That makes the selection broad in tone and commercial fit. For founders, the main question is whether the word becomes more memorable or more limiting when paired with .sexy. For investors, the key is price discipline against likely buyer depth for this extension. The median ask is 4,510.66, so selection matters. Generic words can read clearly, but trademark-sensitive names such as twitter.sexy need extra caution.

- One-word .sexy domains only
- Median ask across this set: 4,510.66
- Generic words vary widely in commercial fit
- Check trademark risk before judging price

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SEXY One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SEXY page](https://unique.domains/domains/tld/sexy?utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sexy_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
