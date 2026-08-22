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
| Screen time (Mac) | 4.5h | 35.8h | 127.6h | ~1901h* |
| Interactive human attention | 3.8h | 33.0h | 116.6h | 218.4h |
| Interactive AI generation | 3.0h | 34.5h | 122.6h | 354.8h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.5h | 2.8h | 26.4h | 52.8h |
| Additive observed work | 7.3h | 70.3h | 265.6h | 625.9h |
| Interactive sessions | 8 | 31 | 78 | 159 |
| Worker sessions | 37 | 138 | 790 | 1,484 |

_Screen time from macos-knowledge-db:/app/usage-union; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 58 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 12,200 | 24K | 7.7M | 4,067.8M | $1,925.81 | $54,915.73 | $0.00 |
| claude-sonnet-5 | 6,821 | 13K | 3.8M | 2,238.8M | $1,091.58 | $6,044.77 | $2,914.96 |
| claude-opus-4-8 | 1,366 | 2K | 1.1M | 404.3M | $911.47 | $5,459.18 | $0.00 |
| gpt-5.6-sol | 7,210 | 31.5M | 1.4M | 533.7M | $500.98 | $1,441.13 | $1,102.92 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| big-pickle | 2,982 | 10.4M | 726K | 275.1M | $134.21 | $0.00 | $624.31 |
| deepseek-v4-flash-free | 961 | 4.1M | 396K | 99.1M | $52.00 | $267.84 | $192.38 |
| gpt-5.5 | 885 | 4.4M | 220K | 112.6M | $43.71 | $304.09 | $201.82 |
| gpt-5.6-terra | 721 | 5.0M | 159K | 39.4M | $21.49 | $106.57 | $117.89 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| gpt-5.6-luna | 134 | 944K | 16K | 2.3M | $0.29 | $6.45 | $15.18 |
| **Total** | **33,556** | **56.6M** | **15.8M** | **7,826.5M** | **$4,823.63** | **$69,244.47** | **$5,174.42** |

_8,168.2M total tokens processed. 95.8% cache hit rate._

_$74,418.88 total saved ($69,244.47 caching + $5,174.42 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | $4,778.46 | $21,693.86 | $0.00 |
| claude-opus-5 | 12,200 | 24K | 7.7M | 4,067.8M | $1,925.81 | $54,915.73 | $0.00 |
| claude-sonnet-5 | 9,401 | 19K | 5.7M | 2,976.6M | $1,496.54 | $8,037.03 | $3,917.78 |
| gpt-5.6-sol | 12,674 | 53.7M | 2.4M | 882.2M | $843.34 | $2,382.00 | $1,852.48 |
| big-pickle | 5,873 | 20.3M | 1.3M | 531.1M | $254.55 | $0.00 | $1,205.05 |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | $158.30 | $894.53 | $594.45 |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | $136.60 | $694.71 | $0.00 |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | $65.29 | $379.59 | $298.33 |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | $35.54 | $169.21 | $90.45 |
| gpt-5.6-terra | 722 | 5.1M | 159K | 39.4M | $21.57 | $106.57 | $118.36 |
| claude-fable-5 | 21 | 42 | 53K | 1.4M | $5.49 | $3.98 | $4.96 |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | $0.46 | $7.64 | $20.76 |
| gpt-5.6-luna | 134 | 944K | 16K | 2.3M | $0.29 | $6.45 | $15.18 |
| **Total** | **53,105** | **100.9M** | **26.5M** | **10,698.2M** | **$9,722.24** | **$89,291.30** | **$8,117.80** |

_11,226.3M total tokens processed. 95.3% cache hit rate._

_$97,409.11 total saved ($89,291.30 caching + $8,117.80 model routing vs all-Opus)._

_Model savings are modest because ~95.3% of tokens are cache reads, where price differences between models are small._

## Top Apps by Screen Time

| App | Yesterday | Prior 7 Days | Prior 28 Days |
| --- | ---: | ---: | ---: |
| Tabby | 72% | 82% | 86% |
| Safari | 25% | 17% | 12% |
| app | -- | -- | 1% |
| TextEdit | 3% | -- | -- |
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
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jde90)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-22 23:18 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/jde90?theme=dark" />
    <img alt="jde90's commit history" src="https://commit-history.com/embed/jde90" />
  </picture>
</div>
