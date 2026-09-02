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
| Screen time (Mac) | 7.2h | 17.1h | 121.3h | ~1801h* |
| Interactive human attention | 6.6h | 14.4h | 106.4h | 251.5h |
| Interactive AI generation | 10.1h | 20.0h | 105.3h | 386.7h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.1h | 0.5h | 9.4h | 53.9h |
| Additive observed work | 16.8h | 34.9h | 221.1h | 692.1h |
| Interactive sessions | 6 | 17 | 86 | 186 |
| Worker sessions | 26 | 146 | 626 | 1,696 |

_Screen time from macos-knowledge-db:/app/usage-union; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 69 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-5 | 9,481 | 20K | 5.3M | 3,495.9M | $1,668.69 | $9,439.06 | $4,518.52 |
| claude-opus-5 | 8,197 | 16K | 5.2M | 2,745.9M | $1,270.67 | $37,070.35 | $0.00 |
| gpt-5.6-sol | 3,607 | 20.8M | 1.1M | 489.9M | $403.35 | $1,322.83 | $909.56 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| big-pickle | 2,291 | 9.1M | 675K | 228.6M | $114.10 | $0.00 | $530.28 |
| deepseek-v4-flash-free | 356 | 2.7M | 233K | 39.5M | $24.05 | $106.82 | $94.15 |
| gpt-5.6-terra | 744 | 5.5M | 161K | 40.2M | $22.74 | $108.75 | $125.19 |
| gpt-5.6-luna | 634 | 12.5M | 96K | 45.2M | $3.69 | $122.11 | $210.76 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| claude-fable-5 | 3 | 6 | 7K | 433K | $1.07 | $1.17 | $0.96 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| **Total** | **25,592** | **51.3M** | **13.1M** | **7,139.1M** | **$3,647.14** | **$48,870.42** | **$6,397.71** |

_7,448.3M total tokens processed. 95.8% cache hit rate._

_$55,268.13 total saved ($48,870.42 caching + $6,397.71 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | $4,778.46 | $21,693.86 | $0.00 |
| claude-sonnet-5 | 13,113 | 27K | 7.9M | 4,475.6M | $2,185.10 | $12,084.20 | $5,849.64 |
| claude-opus-5 | 13,044 | 26K | 8.2M | 4,398.1M | $2,081.32 | $59,375.08 | $0.00 |
| gpt-5.6-sol | 14,165 | 61.8M | 2.9M | 1,096.8M | $1,010.90 | $2,961.56 | $2,238.46 |
| big-pickle | 6,281 | 22.5M | 1.5M | 569.4M | $275.33 | $0.00 | $1,307.46 |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | $158.30 | $894.53 | $594.45 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | $65.29 | $379.59 | $298.33 |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | $35.54 | $169.21 | $90.45 |
| gpt-5.6-terra | 745 | 5.6M | 161K | 40.2M | $22.82 | $108.75 | $125.66 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| gpt-5.6-luna | 662 | 12.6M | 99K | 45.9M | $3.74 | $124.20 | $213.11 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | $0.46 | $7.64 | $20.76 |
| **Total** | **60,135** | **124.0M** | **30.0M** | **12,826.6M** | **$10,761.53** | **$98,501.92** | **$10,751.59** |

_13,448.9M total tokens processed. 95.4% cache hit rate._

_$109,253.50 total saved ($98,501.92 caching + $10,751.59 model routing vs all-Opus)._

_Model savings are modest because ~95.4% of tokens are cache reads, where price differences between models are small._

## Top Apps by Screen Time

| App | Yesterday | Prior 7 Days | Prior 28 Days |
| --- | ---: | ---: | ---: |
| Tabby | 82% | 80% | 80% |
| Safari | 17% | 19% | 18% |
| app | -- | -- | 1% |
| Finder | 1% | 1% | -- |
| QuickTimePlayerX | -- | -- | -- |
| Preview | -- | -- | -- |
| TextEdit | -- | -- | -- |
| Messages | -- | -- | -- |
| System Settings | -- | -- | -- |
| AppStore | -- | -- | -- |
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
_Stats auto-updated 2026-09-02 17:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/jde90?theme=dark" />
    <img alt="jde90's commit history" src="https://commit-history.com/embed/jde90" />
  </picture>
</div>
