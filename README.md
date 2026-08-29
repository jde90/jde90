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
| Screen time (Mac) | 0h | 25.1h | 116.9h | ~1860h* |
| Interactive human attention | 0.0h | 19.1h | 101.2h | 237.5h |
| Interactive AI generation | 0.0h | 12.1h | 96.8h | 366.9h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.1h | 0.8h | 14.5h | 53.6h |
| Additive observed work | 0.1h | 32.0h | 212.5h | 658.0h |
| Interactive sessions | 0 | 22 | 77 | 175 |
| Worker sessions | 24 | 144 | 627 | 1,613 |

_Screen time from macos-knowledge-db:/app/usage-union; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 65 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 9,563 | 19K | 6.1M | 3,231.5M | $1,523.28 | $43,626.37 | $0.00 |
| claude-sonnet-5 | 8,338 | 16K | 4.6M | 2,788.3M | $1,362.46 | $7,528.49 | $3,624.02 |
| gpt-5.6-sol | 5,193 | 24.8M | 1.2M | 521.4M | $450.05 | $1,407.82 | $996.18 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| big-pickle | 2,198 | 8.1M | 584K | 215.0M | $106.22 | $0.00 | $489.26 |
| deepseek-v4-flash-free | 530 | 3.0M | 297K | 55.6M | $33.22 | $150.33 | $120.91 |
| gpt-5.6-terra | 725 | 5.1M | 160K | 39.6M | $21.65 | $106.96 | $118.73 |
| claude-fable-5 | 9 | 18 | 32K | 1.0M | $4.43 | $2.93 | $3.26 |
| gpt-5.6-luna | 471 | 9.4M | 57K | 25.8M | $2.59 | $69.90 | $147.74 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| gpt-5.5 | 6 | 94K | 771 | 93K | $0.29 | $0.25 | $1.30 |
| **Total** | **27,312** | **51.1M** | **13.3M** | **6,931.8M** | **$3,642.97** | **$53,592.39** | **$5,509.70** |

_7,244.5M total tokens processed. 95.7% cache hit rate._

_$59,102.09 total saved ($53,592.39 caching + $5,509.70 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | $4,778.46 | $21,693.86 | $0.00 |
| claude-opus-5 | 12,220 | 24K | 7.7M | 4,073.2M | $1,930.25 | $54,988.48 | $0.00 |
| claude-sonnet-5 | 11,137 | 22K | 6.7M | 3,577.8M | $1,796.55 | $9,660.21 | $4,700.69 |
| gpt-5.6-sol | 13,118 | 55.6M | 2.5M | 945.2M | $888.54 | $2,552.28 | $1,956.80 |
| big-pickle | 6,118 | 21.4M | 1.4M | 553.1M | $265.66 | $0.00 | $1,259.10 |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | $158.30 | $894.53 | $594.45 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | $65.29 | $379.59 | $298.33 |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | $35.54 | $169.21 | $90.45 |
| gpt-5.6-terra | 726 | 5.1M | 160K | 39.6M | $21.72 | $106.96 | $119.20 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| gpt-5.6-luna | 471 | 9.4M | 57K | 25.8M | $2.59 | $69.90 | $147.74 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | $0.46 | $7.64 | $20.76 |
| **Total** | **55,915** | **113.0M** | **27.7M** | **11,415.2M** | **$10,087.63** | **$91,225.96** | **$9,200.79** |

_11,985.1M total tokens processed. 95.2% cache hit rate._

_$100,426.75 total saved ($91,225.96 caching + $9,200.79 model routing vs all-Opus)._

_Model savings are modest because ~95.2% of tokens are cache reads, where price differences between models are small._

## Top Apps by Screen Time

| App | Yesterday | Prior 7 Days | Prior 28 Days |
| --- | ---: | ---: | ---: |
| Tabby | -- | 73% | 81% |
| Safari | -- | 25% | 17% |
| app | -- | -- | 1% |
| Finder | -- | 1% | -- |
| QuickTimePlayerX | -- | 1% | -- |
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
_Stats auto-updated 2026-08-29 08:07 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/jde90?theme=dark" />
    <img alt="jde90's commit history" src="https://commit-history.com/embed/jde90" />
  </picture>
</div>
