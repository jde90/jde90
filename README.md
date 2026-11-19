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
| Screen time (Mac) | 5.3h | 20.9h | 82.8h | ~1712h* |
| Input activity (Mac) | 4h | 15.7h | 18.2h | ~772h* |
| Interactive human attention | 3.4h | 11.8h | 38.6h | 465.0h |
| Interactive AI generation | 1.3h | 10.3h | 80.5h | 736.2h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.9h |
| Worker/headless AI generation | 1.5h | 13.2h | 59.5h | 199.1h |
| Additive observed work | 6.2h | 35.4h | 178.6h | 1,400.9h |
| Interactive sessions | 12 | 41 | 149 | 705 |
| Worker sessions | 52 | 254 | 971 | 4,099 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Input activity from macos-input-activity:idle-cutoff-300s (time from each keyboard, mouse or trackpad input until 5 idle minutes); collection status: ok. Input sampling began 2026-11-10 (8.6 of 28 days sampled); earlier days are not counted. *365-day estimate uses sampled calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 147 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 19,069 | 38K | 5.1M | 2,327.2M | 96.0M | 96.0% | 991 | 69.9h |
| claude-opus-5-5 | 7,267 | 18K | 2.9M | 1,455.0M | 44.7M | 97.0% | 23 | 44.4h |
| claude-sonnet-5-5 | 4,029 | 9K | 1.5M | 670.8M | 37.9M | 94.6% | 56 | 11.6h |
| gpt-5.6-luna | 3,542 | 26.0M | 3.5M | 3.9M | 0 | 13.0% | 107 | 11.9h |
| gpt-6.1-sol | 1,846 | 6.4M | 368K | 289.1M | 0 | 97.8% | 11 | 13.5h |
| gpt-5.6-terra | 1,003 | 8.2M | 321K | 68.0M | 0 | 89.2% | 78 | 7.6h |
| claude-fable-5-2 | 962 | 2K | 618K | 156.4M | 8.1M | 95.1% | 3 | 6.6h |
| deepseek-v4.1-flash-free | 126 | 1.5M | 22K | 15.7M | 0 | 90.9% | 6 | 0.3h |
| gpt-6-luna | 48 | 313K | 4K | 3.7M | 0 | 92.2% | 3 | 0.2h |
| gpt-6.1-terra | 24 | 67K | 3K | 1.4M | 0 | 95.4% | 1 | 0.0h |
| glm-5.3-flash-free | 20 | 250K | 913 | 1.4M | 0 | 85.4% | 2 | 0.0h |
| claude-haiku-5-5 | 9 | 20 | 1K | 551K | 72K | 88.3% | 1 | 0.0h |
| nemotron-3.5-lightning-free | 3 | 64K | 601 | 88K | 0 | 57.6% | 1 | 0.0h |
| **Total** | **37,948** | **43.0M** | **14.4M** | **4,993.7M** | **186.8M** | **95.6%** | **1,169** | **166.1h** |

_5,238.1M total tokens processed. 95.6% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-5 | 58,898 | 117K | 21.1M | 11,589.2M | 461.5M | 96.2% | 2,106 | 238.6h |
| claude-sonnet-5 | 32,839 | 67K | 15.8M | 11,513.9M | 467.5M | 96.1% | 292 | 152.1h |
| gpt-5.6-sol | 15,334 | 70.0M | 3.4M | 1,270.5M | 0 | 94.8% | 800 | 80.3h |
| claude-opus-5-5 | 13,222 | 31K | 5.6M | 2,711.6M | 99.4M | 96.5% | 58 | 67.6h |
| big-pickle | 10,413 | 52.1M | 4.0M | 1,023.3M | 0 | 95.2% | 147 | 53.6h |
| claude-sonnet-5-5 | 7,871 | 19K | 3.1M | 1,494.3M | 85.6M | 94.6% | 81 | 28.0h |
| gpt-5.6-luna | 7,790 | 76.7M | 6.4M | 163.7M | 0 | 68.1% | 766 | 30.7h |
| claude-opus-4-8 | 5,837 | 11K | 6.9M | 1,606.9M | 98.3M | 94.2% | 46 | 42.5h |
| gpt-6.1-sol | 4,810 | 14.5M | 1.0M | 751.1M | 0 | 98.1% | 22 | 32.7h |
| gpt-5.6-terra | 3,902 | 38.7M | 1.1M | 295.5M | 0 | 88.4% | 364 | 21.9h |
| deepseek-v4-flash-free | 3,290 | 10.5M | 1.1M | 331.3M | 0 | 96.9% | 37 | 14.8h |
| gpt-5.5 | 2,285 | 8.8M | 389K | 140.5M | 0 | 94.1% | 301 | 9.8h |
| claude-fable-5-2 | 962 | 2K | 618K | 156.4M | 8.1M | 95.1% | 3 | 6.6h |
| gpt-6-luna | 885 | 6.7M | 146K | 120.8M | 0 | 94.7% | 25 | 3.7h |
| claude-sonnet-4-6 | 360 | 468 | 254K | 62.6M | 3.4M | 94.8% | 3 | 1.8h |
| claude-opus-4-6 | 255 | 305 | 160K | 51.4M | 2.5M | 95.3% | 2 | 1.6h |
| muse-spark-1.2-contributor-free | 228 | 1.7M | 47K | 59.0M | 0 | 97.1% | 1 | 0.5h |
| deepseek-v4-pro | 211 | 951K | 81K | 41.3M | 0 | 97.8% | 3 | 0.8h |
| gpt-6-astra | 210 | 1.5M | 68K | 23.9M | 0 | 94.0% | 5 | 1.3h |
| claude-fable-5 | 187 | 374 | 159K | 32.6M | 2.8M | 91.9% | 6 | 1.2h |
| deepseek-v4.1-flash-free | 154 | 1.7M | 30K | 20.0M | 0 | 91.8% | 6 | 0.4h |
| nemotron-3-ultra-free | 109 | 3.0M | 8K | 9.3M | 0 | 75.6% | 5 | 0.8h |
| longcat-2.5-preview-free | 102 | 149K | 9K | 12.3M | 0 | 98.8% | 1 | 0.3h |
| deepseek-v4-flash | 71 | 178K | 26K | 13.5M | 0 | 98.7% | 1 | 0.1h |
| gpt-5.4-mini | 53 | 1.3M | 4K | 4.0M | 0 | 75.1% | 1 | 1.2h |
| nemotron-3.5-lightning-free | 32 | 994K | 12K | 1.8M | 0 | 65.0% | 7 | 0.3h |
| muse-spark-1.3-contributor-free | 27 | 114K | 4K | 2.2M | 0 | 95.1% | 2 | 0.0h |
| gpt-6.1-terra | 24 | 67K | 3K | 1.4M | 0 | 95.4% | 1 | 0.0h |
| glm-5.3-flash-free | 20 | 250K | 913 | 1.4M | 0 | 85.4% | 2 | 0.0h |
| claude-haiku-5-5 | 9 | 20 | 1K | 551K | 72K | 88.3% | 1 | 0.0h |
| claude-haiku-4-5 | 5 | 17 | 1K | 103K | 415K | 20.0% | 4 | 0.0h |
| mimo-v2.5-free | 5 | 454K | 3K | 16K | 0 | 3.5% | 5 | 0.0h |
| qwen2.5:14b-instruct-q4_K_M | 3 | 6K | 408 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.6 | 2 | 0 | 0 | 0 | 0 | 0.0% | 2 | 0.0h |
| gpt-5.6-fast | 2 | 0 | 0 | 0 | 0 | 0.0% | 2 | 0.0h |
| pool-account-management | 2 | 0 | 0 | 0 | 0 | 0.0% | 2 | 0.0h |
| claude-fable-5-1 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.1h |
| claude-opus-4-8-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **170,411** | **291.1M** | **72.0M** | **33,508.0M** | **1,230.0M** | **95.7%** | **4,597** | **793.5h** |

_35,101.2M total tokens processed. 95.7% cache hit rate._
<!-- STATS-END -->

<!-- PROJECTS-START -->
<!-- PROJECTS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jde90)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-11-19 18:02 UTC by [aidevops](https://aidevops.sh) pulse._
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
