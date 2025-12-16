# Server-Log-analysis
Overview: This project analyzes server log data from a university Virtual Desktop Infrastructure (VDI) environment to provide strategic recommendations to the CIO regarding hardware provisioning and software licensing.

Key Analysis:

Data Wrangling: Processed raw server logs using R (tidyverse, lubridate) to handle date inconsistencies, missing data gaps, and system error codes.

Stability Audit: Identified a critical 16% session failure rate, highlighting "hidden" system instability not previously reported in standard metrics.

Performance Optimization: Conducted CPU intensity analysis to identify "Noisy Neighbor" events, pinpointing unoptimized student coursework applications (avg >80% CPU) as the root cause of system latency.

Outcomes: Delivered a strategic report recommending the isolation of development workloads to high-performance server pools and a revised licensing budget model to account for missing temporal data.
