# Available .INC One-Word Domains (12,318)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C318%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .inc one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,318 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,318 domains · **Median ask:** $1,353.47 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-17  
**Canonical page:** `https://unique.domains/domains/tld/inc`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/inc?utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./inc.csv">CSV</a> / <a href="./inc.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .INC search](https://unique.domains/domains/tld/inc?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .INC search](https://unique.domains/domains/tld/inc?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .INC one-word domain catalog.

### Files

- `inc.csv` — public CSV extract (1,000 rows)
- `inc.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/inc-oneword-domains/main/inc.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Acup.inc         | available | $2,798    | —             | 80             | 5      | 5      | namecheap |
| barup.inc        | available | $350      | —             | 82             | 2      | 6      | name.com  |
| useit.inc        | available | $350      | —             | 94             | 7      | 6      | name.com  |
| gearup.inc       | available | $350      | —             | 80             | 16     | 7      | name.com  |
| QandA.inc        | available | $2,798    | —             | 80             | 10     | 7      | namecheap |
| hangon.inc       | available | $350      | —             | 82             | 6      | 7      | name.com  |
| stirup.inc       | available | $350      | —             | 82             | 3      | 7      | name.com  |
| leaveon.inc      | available | $350      | —             | 80             | 1      | 8      | name.com  |
| FabFour.inc      | available | $279      | $2,099        | 82             | 3      | 8      | namesilo  |
| chaitea.inc      | available | $350      | —             | 86             | 3      | 8      | name.com  |
| CocaCola.inc     | available | $2,798    | —             | 92             | 82     | 9      | namecheap |
| thing.inc        | resell    | —         | —             | 84             | 26     | 5      | Namecheap |
| nets.inc         | premium   | $2,170    | $2,800        | 54             | 81     | 4      | namecheap |
| motorsport.inc   | available | $350      | —             | 74             | 23     | 10     | name.com  |
| deposits.inc     | resell    | —         | —             | 54             | 6      | 8      | Namecheap |
| online.inc       | premium   | $2,170    | $2,800        | 70             | 62     | 7      | namecheap |
| deeplearning.inc | available | $350      | —             | 74             | 23     | 13     | name.com  |
| regions.inc      | premium   | $2,170    | $2,800        | 64             | 59     | 7      | namecheap |
| inhouse.inc      | available | $350      | —             | 70             | 23     | 8      | name.com  |
| Books.inc        | premium   | $2,170    | $2,800        | 52             | 49     | 5      | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,318 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/inc?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/inc?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=related_pricing)

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

These domains are all .inc names, with one-word constructions that often read like short commands, phrases, or compact brand terms. Examples such as Acup.inc, geton.inc, useit.inc, gearup.inc, and hangon.inc show a practical, action-led style rather than abstract coinages. For founders, the main question is whether the word feels memorable, easy to say, and strong enough to stand alone. For investors, the key test is whether the ask leaves room for realistic resale interest within the .inc niche. With a median ask of $1,353, this set sits in a range where pricing discipline matters more than hype.

- Most names are short, action-led, and brandable in .inc
- Median ask is $1,353 across this selection
- Check whether the word stands alone without extra context
- Prioritize clean spelling and low trademark ambiguity

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .INC One-Word Domains*. Version 2026-05-17. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .INC page](https://unique.domains/domains/tld/inc?utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_inc_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
