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
| Screen time (Mac) | 4.8h | 38.5h | 129.4h | ~1917h* |
| Interactive human attention | 4.6h | 33.0h | 116.4h | 233.1h |
| Interactive AI generation | 2.7h | 25.7h | 117.3h | 364.3h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.1h | 2.1h | 23.6h | 53.2h |
| Additive observed work | 7.4h | 60.7h | 257.3h | 650.6h |
| Interactive sessions | 15 | 32 | 88 | 174 |
| Worker sessions | 38 | 158 | 742 | 1,548 |

_Screen time from macos-knowledge-db:/app/usage-union; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 61 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 11,592 | 23K | 7.2M | 3,896.7M | $1,833.07 | $52,605.92 | $0.00 |
| claude-sonnet-5 | 8,218 | 16K | 4.5M | 2,721.8M | $1,317.87 | $7,349.03 | $3,540.72 |
| gpt-5.6-sol | 6,530 | 29.3M | 1.3M | 560.1M | $500.08 | $1,512.30 | $1,105.50 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| big-pickle | 2,615 | 9.3M | 664K | 244.9M | $120.27 | $0.00 | $556.91 |
| deepseek-v4-flash-free | 530 | 3.0M | 297K | 55.6M | $33.22 | $150.33 | $120.91 |
| gpt-5.6-terra | 725 | 5.1M | 160K | 39.6M | $21.65 | $106.96 | $118.73 |
| gpt-5.5 | 409 | 2.1M | 111K | 51.6M | $20.43 | $139.40 | $93.97 |
| claude-fable-5 | 9 | 18 | 32K | 1.0M | $4.43 | $2.93 | $3.26 |
| gpt-5.6-luna | 406 | 7.2M | 55K | 24.7M | $2.11 | $66.91 | $119.88 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| **Total** | **31,313** | **56.6M** | **14.6M** | **7,649.5M** | **$3,991.91** | **$62,633.11** | **$5,668.19** |

_7,987.7M total tokens processed. 95.8% cache hit rate._

_$68,301.30 total saved ($62,633.11 caching + $5,668.19 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | $4,778.46 | $21,693.86 | $0.00 |
| claude-opus-5 | 12,220 | 24K | 7.7M | 4,073.2M | $1,930.25 | $54,988.48 | $0.00 |
| claude-sonnet-5 | 11,002 | 22K | 6.7M | 3,510.7M | $1,751.11 | $9,479.07 | $4,615.62 |
| gpt-5.6-sol | 13,102 | 55.4M | 2.5M | 943.2M | $886.69 | $2,546.85 | $1,952.44 |
| big-pickle | 6,118 | 21.4M | 1.4M | 553.1M | $265.66 | $0.00 | $1,259.10 |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | $158.30 | $894.53 | $594.45 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | $65.29 | $379.59 | $298.33 |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | $35.54 | $169.21 | $90.45 |
| gpt-5.6-terra | 726 | 5.1M | 160K | 39.6M | $21.72 | $106.96 | $119.20 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| gpt-5.6-luna | 406 | 7.2M | 55K | 24.7M | $2.11 | $66.91 | $119.88 |
| nemotron-3.5-lightning-free | 19 | 284K | 10K | 1.4M | $1.55 | $4.05 | $5.84 |
| nemotron-3-ultra-free | 5 | 174K | 1K | 211K | $0.63 | $0.57 | $2.46 |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | $0.46 | $7.64 | $20.76 |
| **Total** | **55,699** | **110.6M** | **27.6M** | **11,345.0M** | **$10,039.86** | **$91,036.41** | **$9,083.50** |

_11,906.0M total tokens processed. 95.3% cache hit rate._

_$100,119.91 total saved ($91,036.41 caching + $9,083.50 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-26 02:03 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/jde90?theme=dark" />
    <img alt="jde90's commit history" src="https://commit-history.com/embed/jde90" />
  </picture>
</div>
