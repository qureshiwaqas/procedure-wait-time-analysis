# Priority Procedures Wait Time Analysis

This analysis aims to analyse wait times for prioritized medical procedures across Canada's major provinces from 2008 to 2024. Its objective is to benchmark provincial performance, identifies trends over the years, extracts procedure-specific patterns, and spotlights regions with notable variations.

Dashboards ([1](https://public.tableau.com/app/profile/waqas5688/viz/processed_wait_times/Benchmark), 
[2](https://public.tableau.com/app/profile/waqas5688/viz/processed_wait_times/Dashboard2))

![Dashboard-1-img](https://github.com/qureshiwaqas/procedure-wait-time-analysis/blob/main/resources/d1.png)
![Dashboard-2-img](https://github.com/qureshiwaqas/procedure-wait-time-analysis/blob/main/resources/d2.png)

## Data
[Source](https://www.cihi.ca/sites/default/files/document/wait-times-priority-procedures-in-canada-2025-data-tables-en.xlsx) - Canadian Institute for Health Information. Wait Times for Priority Procedures in Canada, 2008–2024 — Data Tables. Ottawa, ON: CIHI; 2025.

[Transformed Data](https://github.com/qureshiwaqas/procedure-wait-time-analysis/blob/main/resources/processed_wait_times.csv)

## Transformations Applied
- Removed metadata rows
- Fixed year formatting
- Dropped empty/irrelevant columns
- Reshaped data
- Renamed columns
- Added flags

## Insights Derived
- ⚠️ Critical Issues
  - 1 in 5 patients wait longer than doctors consider safe
  - Typical wait time is over 1 month nationwide
  - Bone/joint surgery waits are a crisis everywhere in Canada
- 📊 Regional Comparisons
  - Ontario performs best (thanks to eCTAS system)
  - Quebec has longest waits despite smaller population
  - British Columbia has middle-ranking results (can improve)
- ℹ️ System Trends
  - Hospitals handle cases faster, but patient numbers keep rising
  - Even in Ontario, 10% wait up to 4 months

Ontario demonstrates that well-designed systems can maintain quality under heavy demand - a model warranting nationwide study. 

## Recommendations
- Prioritize Orthopedic Reforms
- Scale cost-effective procedures
- Adopt Ontario's System nationwide
- Targeted backlog analysis
