# Available .CASA One-Word Domains (16,635)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C635%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .casa one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,635 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,635 domains · **Median ask:** $16.18 · **High-demand under $2,500:** 11

**Last updated:** 2026-08-21
**Canonical page:** `https://unique.domains/domains/tld/casa`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/casa?utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./casa.csv">CSV</a> / <a href="./casa.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CASA search](https://unique.domains/domains/tld/casa?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CASA search](https://unique.domains/domains/tld/casa?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CASA one-word domain catalog.

### Files

- `casa.csv`, public CSV extract (1,000 rows)
- `casa.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/casa-oneword-domains/main/casa.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| able.casa    | available | $2.19     | $12.99        | high           | low    | 4      | namesilo         |
| romance.casa | resell    | $17.98    | —             | high           | low    | 7      | Spaceship, Inc.  |
| and.casa     | premium   | $96       | $11.80        | high           | medium | 3      | namesilo         |
| asat.casa    | available | $1.98     | $17.98        | low            | low    | 4      | namecheap        |
| dock.casa    | resell    | —         | —             | high           | low    | 4      | Dynadot Inc      |
| ant.casa     | premium   | $2,500    | —             | high           | medium | 3      | name.com         |
| blob.casa    | available | $1.99     | —             | medium         | low    | 4      | name.com         |
| food.casa    | resell    | —         | —             | high           | medium | 4      | Spaceship, Inc.  |
| ass.casa     | premium   | $96       | $11.80        | low            | low    | 3      | namesilo         |
| brie.casa    | available | $17.98    | —             | high           | low    | 4      | namecheap        |
| http.casa    | resell    | —         | —             | high           | high   | 4      | Porkbun          |
| ate.casa     | premium   | $96       | $11.80        | high           | low    | 3      | namesilo         |
| buns.casa    | available | $1.98     | $17.98        | low            | low    | 4      | namecheap        |
| king.casa    | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC |
| beg.casa     | premium   | $96       | $11.80        | medium         | low    | 3      | namesilo         |
| clxx.casa    | available | $1.98     | $17.98        | low            | low    | 4      | namecheap        |
| life.casa    | resell    | —         | —             | high           | medium | 4      | Spaceship, Inc.  |
| cxv.casa     | premium   | $47.20    | $11.80        | low            | low    | 3      | namesilo         |
| cyan.casa    | available | $1.99     | —             | high           | low    | 4      | name.com         |
| link.casa    | resell    | —         | —             | medium         | high   | 4      | Dynadot Inc      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,635 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 11 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/casa?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/casa?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=related_pricing)

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

This list of .casa domain names spans 11,596 options, from lifestyle terms like jewels.casa and ladies.casa to service-oriented names such as primarycare.casa and shoparound.casa. With a median ask near $24, the set stays affordable for founders building a home, wellness, or local-service brand, while investors can scan pricing across a large pool of names for potential value. Since ".casa" reads as "house" in Spanish and Italian, many names in this selection carry a warm, residential or lifestyle tone suited to real estate, home goods, and family-focused projects.

- 11,596 .casa domain names in this selection, updated daily
- Median ask near $24 across the set
- Lifestyle and home-themed names like jewels.casa, ladies.casa
- Service-style names such as primarycare.casa, shoparound.casa

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CASA One-Word Domains*. Version 2026-08-21. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CASA page](https://unique.domains/domains/tld/casa?utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_casa_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
