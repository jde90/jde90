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
| Screen time (Mac) | 4.8h | 38.5h | 131.1h | ~1917h* |
| Interactive human attention | 4.6h | 33.0h | 116.4h | 233.1h |
| Interactive AI generation | 2.7h | 25.7h | 117.3h | 364.3h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.1h | 2.1h | 23.6h | 53.2h |
| Additive observed work | 7.4h | 60.7h | 257.3h | 650.6h |
| Interactive sessions | 12 | 29 | 85 | 171 |
| Worker sessions | 24 | 144 | 728 | 1,534 |

_Screen time from macos-knowledge-db:/app/usage-union; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 61 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 12,125 | 24K | 7.6M | 4,058.3M | $1,919.54 | $54,787.43 | $0.00 |
| claude-sonnet-5 | 7,425 | 14K | 4.1M | 2,458.1M | $1,200.69 | $6,637.13 | $3,197.61 |
| gpt-5.6-sol | 6,767 | 30.1M | 1.3M | 565.8M | $508.53 | $1,527.89 | $1,124.04 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| big-pickle | 2,692 | 9.4M | 673K | 253.1M | $123.44 | $0.00 | $572.47 |
| claude-opus-4-8 | 30 | 60 | 29K | 20.9M | $47.38 | $282.21 | $0.00 |
| deepseek-v4-flash-free | 530 | 3.0M | 297K | 55.6M | $33.22 | $150.33 | $120.91 |
| gpt-5.6-terra | 725 | 5.1M | 160K | 39.6M | $21.65 | $106.96 | $118.73 |
| gpt-5.5 | 409 | 2.1M | 111K | 51.6M | $20.43 | $139.40 | $93.97 |
| claude-fable-5 | 11 | 22 | 34K | 1.1M | $4.70 | $3.07 | $3.46 |
| gpt-5.6-luna | 349 | 6.3M | 43K | 20.7M | $1.80 | $56.06 | $103.31 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| **Total** | **31,342** | **56.7M** | **14.6M** | **7,578.4M** | **$4,020.16** | **$64,389.81** | **$5,342.80** |

_7,917.8M total tokens processed. 95.7% cache hit rate._

_$69,732.61 total saved ($64,389.81 caching + $5,342.80 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | $4,778.46 | $21,693.86 | $0.00 |
| claude-opus-5 | 12,220 | 24K | 7.7M | 4,073.2M | $1,930.25 | $54,988.48 | $0.00 |
| claude-sonnet-5 | 10,208 | 20K | 6.2M | 3,247.1M | $1,633.65 | $8,767.17 | $4,272.29 |
| gpt-5.6-sol | 13,102 | 55.4M | 2.5M | 943.2M | $886.69 | $2,546.85 | $1,952.44 |
| big-pickle | 6,115 | 21.3M | 1.4M | 552.8M | $265.21 | $0.00 | $1,256.93 |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | $158.30 | $894.53 | $594.45 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | $65.29 | $379.59 | $298.33 |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | $35.54 | $169.21 | $90.45 |
| gpt-5.6-terra | 726 | 5.1M | 160K | 39.6M | $21.72 | $106.96 | $119.20 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| gpt-5.6-luna | 349 | 6.3M | 43K | 20.7M | $1.80 | $56.06 | $103.31 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | $0.46 | $7.64 | $20.76 |
| **Total** | **54,845** | **109.6M** | **27.2M** | **11,077.1M** | **$9,921.64** | **$90,313.67** | **$8,721.43** |

_11,628.1M total tokens processed. 95.3% cache hit rate._

_$99,035.09 total saved ($90,313.67 caching + $8,721.43 model routing vs all-Opus)._

_Model savings are modest because ~95.3% of tokens are cache reads, where price differences between models are small._

## Top Apps by Screen Time

| App | Yesterday | Prior 7 Days | Prior 28 Days |
| --- | ---: | ---: | ---: |
| Tabby | 64% | 81% | 84% |
| Safari | 34% | 18% | 14% |
| app | -- | -- | 1% |
| TextEdit | -- | 1% | -- |
| Terminal | -- | -- | -- |
| Finder | 1% | -- | -- |
| Preview | 1% | -- | -- |
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
_Stats auto-updated 2026-08-25 09:41 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/jde90?theme=dark" />
    <img alt="jde90's commit history" src="https://commit-history.com/embed/jde90" />
  </picture>
</div>
