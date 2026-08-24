# jde90

![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Mac) | 6.6h | 37.9h | 128.9h | ~1911h* |
| Interactive human attention | 7.0h | 35.3h | 117.6h | 225.5h |
| Interactive AI generation | 3.8h | 33.3h | 120.0h | 358.6h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.3h | 2.6h | 26.2h | 53.1h |
| Additive observed work | 11.1h | 71.2h | 263.8h | 637.2h |
| Interactive sessions | 11 | 30 | 82 | 164 |
| Worker sessions | 38 | 128 | 793 | 1,507 |

_Screen time from macos-knowledge-db:/app/usage-union; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 59 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 12,220 | 24K | 7.7M | 4,073.2M | $1,930.25 | $54,988.48 | $0.00 |
| claude-sonnet-5 | 7,093 | 14K | 3.9M | 2,348.5M | $1,149.07 | $6,341.02 | $3,056.58 |
| claude-opus-4-8 | 1,007 | 2K | 876K | 360.9M | $793.81 | $4,872.87 | $0.00 |
| gpt-5.6-sol | 7,002 | 30.4M | 1.4M | 568.2M | $512.70 | $1,534.33 | $1,132.38 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| big-pickle | 2,889 | 9.8M | 718K | 270.6M | $130.73 | $0.00 | $607.05 |
| deepseek-v4-flash-free | 705 | 3.5M | 336K | 74.6M | $41.55 | $201.42 | $152.39 |
| gpt-5.5 | 628 | 3.1M | 156K | 81.4M | $31.36 | $219.98 | $144.82 |
| gpt-5.6-terra | 721 | 5.0M | 159K | 39.4M | $21.49 | $106.57 | $117.89 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| gpt-5.6-luna | 157 | 2.0M | 17K | 2.3M | $0.53 | $6.45 | $28.73 |
| nemotron-3.5-lightning-free | 3 | 3K | 2K | 150K | $0.11 | $0.41 | $0.35 |
| **Total** | **32,701** | **54.1M** | **15.5M** | **7,872.6M** | **$4,753.69** | **$68,970.21** | **$5,245.14** |

_8,216.6M total tokens processed. 95.8% cache hit rate._

_$74,215.35 total saved ($68,970.21 caching + $5,245.14 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | $4,778.46 | $21,693.86 | $0.00 |
| claude-opus-5 | 12,220 | 24K | 7.7M | 4,073.2M | $1,930.25 | $54,988.48 | $0.00 |
| claude-sonnet-5 | 9,873 | 20K | 6.1M | 3,137.4M | $1,582.03 | $8,471.06 | $4,131.26 |
| gpt-5.6-sol | 13,053 | 54.9M | 2.5M | 937.8M | $880.91 | $2,532.26 | $1,939.02 |
| big-pickle | 5,979 | 20.8M | 1.4M | 540.9M | $259.68 | $0.00 | $1,229.55 |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | $158.30 | $894.53 | $594.45 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | $65.29 | $379.59 | $298.33 |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | $35.54 | $169.21 | $90.45 |
| gpt-5.6-terra | 722 | 5.1M | 159K | 39.4M | $21.57 | $106.57 | $118.36 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| gpt-5.6-luna | 157 | 2.0M | 17K | 2.3M | $0.53 | $6.45 | $28.73 |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | $0.46 | $7.64 | $20.76 |
| nemotron-3.5-lightning-free | 3 | 3K | 2K | 150K | $0.11 | $0.41 | $0.35 |
| **Total** | **54,108** | **103.8M** | **26.9M** | **10,929.9M** | **$9,855.22** | **$89,948.75** | **$8,456.22** |

_11,470.6M total tokens processed. 95.3% cache hit rate._

_$98,404.96 total saved ($89,948.75 caching + $8,456.22 model routing vs all-Opus)._

_Model savings are modest because ~95.3% of tokens are cache reads, where price differences between models are small._

## Top Apps by Screen Time

| App | Yesterday | Prior 7 Days | Prior 28 Days |
| --- | ---: | ---: | ---: |
| Tabby | 83% | 82% | 85% |
| Safari | 16% | 17% | 13% |
| app | -- | -- | 1% |
| TextEdit | 1% | 1% | -- |
| Terminal | -- | -- | -- |
| Finder | -- | -- | -- |
| Preview | -- | -- | -- |
| QuickTimePlayerX | -- | -- | -- |
| app | -- | -- | -- |
| System Settings | -- | -- | -- |
_Top 10 apps by foreground time share across completed local calendar days. Mac only._
<!-- STATS-END -->

## Projects

- **[huszka-weightlifting](https://github.com/jde90/huszka-weightlifting)** -- No description
- **[expired-gmb-domains](https://github.com/jde90/expired-gmb-domains)** -- Expired GMB Domains finds registerable and auction domains, verifies their availability, and surfaces exact Google Business Profile signals, so you can focus on names with evidence behind them.
- **[concrete-contractors-kenosha](https://github.com/jde90/concrete-contractors-kenosha)** -- Concrete Contractors Kenosha - static site for Cloudflare Pages
- **[concrete-contractors-dayton](https://github.com/jde90/concrete-contractors-dayton)** -- Concrete Contractors Dayton Ohio - static site
<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jde90)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-24 01:10 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/jde90?theme=dark" />
    <img alt="jde90's commit history" src="https://commit-history.com/embed/jde90" />
  </picture>
</div>
