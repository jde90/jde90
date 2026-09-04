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
| Screen time (Mac) | 6.3h | 26.6h | 127.9h | ~1805h* |
| Interactive human attention | 5.9h | 23.5h | 113.3h | 261.0h |
| Interactive AI generation | 9.0h | 34.3h | 116.1h | 401.2h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.3h | 0.8h | 9.8h | 54.3h |
| Additive observed work | 15.2h | 58.6h | 239.2h | 716.5h |
| Interactive sessions | 6 | 20 | 86 | 190 |
| Worker sessions | 20 | 135 | 654 | 1,724 |

_Screen time from macos-knowledge-db:/app/usage-union; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 71 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-5 | 11,256 | 23K | 6.3M | 4,099.1M | $1,958.38 | $11,067.60 | $5,299.50 |
| claude-opus-5 | 8,749 | 17K | 5.6M | 2,899.6M | $1,341.27 | $39,144.67 | $0.00 |
| gpt-5.6-sol | 3,704 | 21.2M | 1.2M | 497.7M | $409.98 | $1,344.01 | $924.78 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| big-pickle | 2,485 | 9.8M | 724K | 246.2M | $122.23 | $0.00 | $570.94 |
| muse-spark-1.2-contributor-free | 228 | 1.7M | 47K | 59.0M | $24.14 | $159.52 | $94.57 |
| deepseek-v4-flash-free | 339 | 2.5M | 227K | 39.1M | $23.22 | $105.61 | $91.55 |
| gpt-5.6-terra | 744 | 5.5M | 161K | 40.2M | $22.74 | $108.75 | $125.19 |
| gpt-5.6-luna | 672 | 12.7M | 99K | 46.2M | $3.77 | $125.00 | $215.05 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| **Total** | **28,456** | **54.2M** | **14.6M** | **7,980.7M** | **$4,044.51** | **$52,754.49** | **$7,329.88** |

_8,323.8M total tokens processed. 95.9% cache hit rate._

_$60,084.37 total saved ($52,754.49 caching + $7,329.88 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | $4,778.46 | $21,693.86 | $0.00 |
| claude-sonnet-5 | 14,936 | 31K | 8.9M | 5,082.3M | $2,477.14 | $13,722.26 | $6,636.39 |
| claude-opus-5 | 13,665 | 27K | 8.7M | 4,567.8M | $2,159.24 | $61,666.62 | $0.00 |
| gpt-5.6-sol | 14,262 | 62.2M | 3.0M | 1,104.7M | $1,017.53 | $2,982.74 | $2,253.69 |
| big-pickle | 6,475 | 23.2M | 1.5M | 587.0M | $283.46 | $0.00 | $1,348.12 |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | $158.30 | $894.53 | $594.45 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | $65.29 | $379.59 | $298.33 |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | $35.54 | $169.21 | $90.45 |
| muse-spark-1.2-contributor-free | 228 | 1.7M | 47K | 59.0M | $24.14 | $159.52 | $94.57 |
| gpt-5.6-terra | 745 | 5.6M | 161K | 40.2M | $22.82 | $108.75 | $125.66 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| gpt-5.6-luna | 700 | 12.8M | 102K | 47.0M | $3.81 | $127.09 | $217.40 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | $0.46 | $7.64 | $20.76 |
| **Total** | **63,136** | **127.0M** | **31.5M** | **13,688.6M** | **$11,170.46** | **$102,615.11** | **$11,693.08** |

_14,346.1M total tokens processed. 95.4% cache hit rate._

_$114,308.19 total saved ($102,615.11 caching + $11,693.08 model routing vs all-Opus)._

_Model savings are modest because ~95.4% of tokens are cache reads, where price differences between models are small._

## Top Apps by Screen Time

| App | Yesterday | Prior 7 Days | Prior 28 Days |
| --- | ---: | ---: | ---: |
| Tabby | 71% | 79% | 80% |
| Safari | 27% | 21% | 19% |
| app | -- | -- | 1% |
| Finder | 1% | 1% | -- |
| QuickTimePlayerX | -- | -- | -- |
| Preview | -- | -- | -- |
| TextEdit | -- | -- | -- |
| Messages | -- | -- | -- |
| System Settings | -- | -- | -- |
| macsys | -- | -- | -- |
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
_Stats auto-updated 2026-09-04 11:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/jde90?theme=dark" />
    <img alt="jde90's commit history" src="https://commit-history.com/embed/jde90" />
  </picture>
</div>
