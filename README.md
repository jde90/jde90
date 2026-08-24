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
| Screen time (Mac) | 6.4h | 37.2h | 128.8h | ~1920h* |
| Interactive human attention | 3.0h | 30.4h | 113.8h | 228.5h |
| Interactive AI generation | 3.0h | 28.5h | 116.6h | 361.6h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.1h | 2.3h | 25.2h | 53.1h |
| Additive observed work | 6.0h | 61.2h | 255.5h | 643.2h |
| Interactive sessions | 12 | 27 | 83 | 167 |
| Worker sessions | 28 | 135 | 757 | 1,517 |

_Screen time from macos-knowledge-db:/app/usage-union; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 60 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 12,220 | 24K | 7.7M | 4,073.2M | $1,930.25 | $54,988.48 | $0.00 |
| claude-sonnet-5 | 7,278 | 14K | 4.0M | 2,392.8M | $1,169.67 | $6,460.83 | $3,115.53 |
| claude-opus-4-8 | 888 | 1K | 717K | 342.4M | $730.00 | $4,623.44 | $0.00 |
| gpt-5.6-sol | 7,022 | 30.7M | 1.4M | 571.7M | $515.78 | $1,543.81 | $1,139.53 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| big-pickle | 2,771 | 9.5M | 690K | 258.2M | $125.48 | $0.00 | $581.63 |
| deepseek-v4-flash-free | 530 | 3.0M | 297K | 55.6M | $33.22 | $150.33 | $120.91 |
| gpt-5.6-terra | 721 | 5.0M | 159K | 39.4M | $21.49 | $106.57 | $117.89 |
| gpt-5.5 | 410 | 2.1M | 111K | 51.6M | $20.43 | $139.40 | $93.97 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| gpt-5.6-luna | 194 | 2.7M | 23K | 5.2M | $0.73 | $14.05 | $40.47 |
| **Total** | **32,329** | **53.4M** | **15.4M** | **7,845.0M** | **$4,690.69** | **$68,729.65** | **$5,220.74** |

_8,188.4M total tokens processed. 95.8% cache hit rate._

_$73,950.39 total saved ($68,729.65 caching + $5,220.74 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | $4,778.46 | $21,693.86 | $0.00 |
| claude-opus-5 | 12,220 | 24K | 7.7M | 4,073.2M | $1,930.25 | $54,988.48 | $0.00 |
| claude-sonnet-5 | 10,060 | 20K | 6.1M | 3,181.8M | $1,602.63 | $8,590.87 | $4,190.21 |
| gpt-5.6-sol | 13,088 | 55.2M | 2.5M | 941.8M | $884.57 | $2,542.87 | $1,947.47 |
| big-pickle | 5,979 | 20.8M | 1.4M | 540.9M | $259.68 | $0.00 | $1,229.55 |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | $158.30 | $894.53 | $594.45 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | $65.29 | $379.59 | $298.33 |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | $35.54 | $169.21 | $90.45 |
| gpt-5.6-terra | 722 | 5.1M | 159K | 39.4M | $21.57 | $106.57 | $118.36 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| gpt-5.6-luna | 194 | 2.7M | 23K | 5.2M | $0.73 | $14.05 | $40.47 |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | $0.46 | $7.64 | $20.76 |
| **Total** | **54,383** | **105.0M** | **27.1M** | **10,982.4M** | **$9,881.12** | **$90,090.41** | **$8,540.86** |

_11,526.0M total tokens processed. 95.3% cache hit rate._

_$98,631.26 total saved ($90,090.41 caching + $8,540.86 model routing vs all-Opus)._

_Model savings are modest because ~95.3% of tokens are cache reads, where price differences between models are small._

## Top Apps by Screen Time

| App | Yesterday | Prior 7 Days | Prior 28 Days |
| --- | ---: | ---: | ---: |
| Tabby | 80% | 83% | 85% |
| Safari | 20% | 15% | 13% |
| app | -- | -- | 1% |
| TextEdit | -- | 1% | -- |
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
_Stats auto-updated 2026-08-24 14:17 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/jde90?theme=dark" />
    <img alt="jde90's commit history" src="https://commit-history.com/embed/jde90" />
  </picture>
</div>
