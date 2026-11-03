# jde90

<!-- aidevops:badges:start -->
<!-- managed by aidevops badges; edit the template, not this block -->

[![Lines of code](docs/metrics/badges/loc.svg)](docs/metrics/repo-metrics.md)
[![Dependencies](docs/metrics/badges/dependencies.svg)](docs/metrics/repo-metrics.md)

[![Languages by lines of code](docs/metrics/badges/languages.svg)](docs/metrics/repo-metrics.md)
<!-- aidevops:badges:end -->

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
| Screen time (Mac) | 1h | 14.2h | 110.8h | ~1787h* |
| Interactive human attention | 0.0h | 6.1h | 62.5h | 438.5h |
| Interactive AI generation | 0.3h | 10.5h | 135.2h | 710.0h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.9h |
| Worker/headless AI generation | 1.8h | 11.2h | 58.3h | 166.9h |
| Additive observed work | 2.1h | 27.8h | 255.9h | 1,316.0h |
| Interactive sessions | 15 | 43 | 177 | 622 |
| Worker sessions | 66 | 258 | 855 | 3,552 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 131 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 20,851 | 41K | 5.7M | 3,588.1M | 123.3M | 96.7% | 848 | 70.1h |
| claude-opus-5-5 | 8,646 | 22K | 3.2M | 1,877.7M | 66.2M | 96.6% | 27 | 47.3h |
| claude-sonnet-5-5 | 5,948 | 14K | 2.2M | 1,247.0M | 64.9M | 95.0% | 51 | 22.2h |
| gpt-5.6-luna | 5,912 | 43.4M | 5.9M | 14.1M | 0 | 24.6% | 221 | 19.6h |
| gpt-6.1-sol | 3,305 | 10.9M | 737K | 515.1M | 0 | 97.9% | 16 | 22.4h |
| gpt-5.6-terra | 1,331 | 14.8M | 406K | 101.6M | 0 | 87.3% | 96 | 9.6h |
| gpt-6-luna | 885 | 6.7M | 146K | 120.8M | 0 | 94.7% | 25 | 3.7h |
| claude-sonnet-5 | 819 | 1K | 270K | 173.5M | 6.6M | 96.3% | 6 | 2.8h |
| big-pickle | 745 | 5.3M | 170K | 92.3M | 0 | 94.5% | 6 | 3.8h |
| deepseek-v4-pro | 190 | 538K | 71K | 35.2M | 0 | 98.5% | 1 | 0.6h |
| deepseek-v4.1-flash-free | 150 | 1.7M | 30K | 19.9M | 0 | 92.0% | 5 | 0.4h |
| nemotron-3-ultra-free | 43 | 940K | 2K | 4.7M | 0 | 83.6% | 2 | 0.1h |
| gpt-6.1-terra | 24 | 67K | 3K | 1.4M | 0 | 95.4% | 1 | 0.0h |
| claude-haiku-5-5 | 9 | 20 | 1K | 551K | 72K | 88.3% | 1 | 0.0h |
| glm-5.3-flash-free | 8 | 152K | 342 | 1.0M | 0 | 87.1% | 1 | 0.0h |
| pool-account-management | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **48,867** | **84.7M** | **19.0M** | **7,793.4M** | **261.2M** | **95.7%** | **1,072** | **202.7h** |

_8,158.5M total tokens processed. 95.7% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 50,806 | 101K | 18.9M | 10,907.6M | 421.0M | 96.3% | 1,575 | 205.6h |
| claude-sonnet-5 | 32,839 | 67K | 15.8M | 11,513.9M | 467.5M | 96.1% | 292 | 152.1h |
| gpt-5.6-sol | 15,334 | 70.0M | 3.4M | 1,270.5M | 0 | 94.8% | 800 | 80.3h |
| claude-opus-5-5 | 11,390 | 28K | 4.7M | 2,427.9M | 88.6M | 96.5% | 48 | 61.5h |
| big-pickle | 10,413 | 52.1M | 4.0M | 1,023.3M | 0 | 95.2% | 147 | 53.6h |
| gpt-5.6-luna | 7,736 | 74.4M | 6.3M | 163.5M | 0 | 68.7% | 747 | 29.9h |
| claude-sonnet-5-5 | 5,948 | 14K | 2.2M | 1,247.0M | 64.9M | 95.0% | 51 | 22.2h |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | 98.3M | 94.2% | 46 | 42.5h |
| gpt-6.1-sol | 4,800 | 14.3M | 1.0M | 750.0M | 0 | 98.1% | 20 | 32.7h |
| gpt-5.6-terra | 3,471 | 35.0M | 1.0M | 265.9M | 0 | 88.3% | 320 | 19.6h |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | 0 | 96.9% | 37 | 14.8h |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | 0 | 94.1% | 301 | 9.8h |
| gpt-6-luna | 885 | 6.7M | 146K | 120.8M | 0 | 94.7% | 25 | 3.7h |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | 3.4M | 94.8% | 3 | 1.8h |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | 2.5M | 95.3% | 2 | 1.6h |
| muse-spark-1.2-contributor-free | 228 | 1.7M | 47K | 59.0M | 0 | 97.1% | 1 | 0.5h |
| deepseek-v4-pro | 211 | 951K | 81K | 41.3M | 0 | 97.8% | 3 | 0.8h |
| gpt-6-astra | 210 | 1.5M | 68K | 23.9M | 0 | 94.0% | 5 | 1.3h |
| claude-fable-5 | 187 | 374 | 159K | 32.6M | 2.8M | 91.9% | 6 | 1.2h |
| deepseek-v4.1-flash-free | 150 | 1.7M | 30K | 19.9M | 0 | 92.0% | 5 | 0.4h |
| nemotron-3-ultra-free | 109 | 3.0M | 8K | 9.3M | 0 | 75.6% | 5 | 0.8h |
| longcat-2.5-preview-free | 102 | 149K | 9K | 12.3M | 0 | 98.8% | 1 | 0.3h |
| deepseek-v4-flash | 71 | 178K | 26K | 13.5M | 0 | 98.7% | 1 | 0.1h |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | 0 | 75.1% | 1 | 1.2h |
| nemotron-3.5-lightning-free | 29 | 930K | 12K | 1.7M | 0 | 65.5% | 6 | 0.3h |
| muse-spark-1.3-contributor-free | 27 | 114K | 4K | 2.2M | 0 | 95.1% | 2 | 0.0h |
| gpt-6.1-terra | 24 | 67K | 3K | 1.4M | 0 | 95.4% | 1 | 0.0h |
| claude-haiku-5-5 | 9 | 20 | 1K | 551K | 72K | 88.3% | 1 | 0.0h |
| glm-5.3-flash-free | 8 | 152K | 342 | 1.0M | 0 | 87.1% | 1 | 0.0h |
| claude-haiku-4-5 | 5 | 17 | 1K | 103K | 415K | 20.0% | 4 | 0.0h |
| mimo-v2.5-free | 5 | 454K | 3K | 16K | 0 | 3.5% | 5 | 0.0h |
| qwen2.5:14b-instruct-q4_K_M | 3 | 6K | 408 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.6 | 2 | 0 | 0 | 0 | 0 | 0.0% | 2 | 0.0h |
| gpt-5.6-fast | 2 | 0 | 0 | 0 | 0 | 0.0% | 2 | 0.0h |
| pool-account-management | 2 | 0 | 0 | 0 | 0 | 0.0% | 2 | 0.0h |
| claude-fable-5-1 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.1h |
| claude-opus-4-8-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **157,088** | **284.7M** | **67.2M** | **32,107.1M** | **1,149.8M** | **95.7%** | **3,979** | **738.9h** |

_33,609.1M total tokens processed. 95.7% cache hit rate._
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
_Stats auto-updated 2026-11-03 23:52 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<!-- TOTAL-CONTRIBUTIONS-START -->
<div align="center">
  <a href="https://commit-history.com/jde90?metric=total" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contributions/total-dark.svg" />
      <img alt="jde90's cumulative total GitHub contributions" src="assets/contributions/total-light.svg" width="960" />
    </picture>
  </a>
</div>

[Verify on commit-history.com](https://commit-history.com/jde90?metric=total) · [Chart data](assets/contributions/total.json)

Includes commits, issues, pull requests, reviews, repositories, and restricted contributions. Refreshed daily through the prior UTC day; commit-history.com may use a different refresh cutoff. GitHub controls link navigation—Ctrl/Cmd-click opens verification in a new tab.
<!-- TOTAL-CONTRIBUTIONS-END -->
