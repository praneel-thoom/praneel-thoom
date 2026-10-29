I'm a Computer Engineering student at Georgia Tech (class of 2028, concentrating in Distributed Systems and Software Design). I build data and ML systems end to end, from the ingestion layer to the dashboard someone actually uses, and I care about checking whether a result is real before I report it.

### What I'm working on

- **GT BME research:** Utilizing high-performance computing clusters to build, train, and benchmark diffusion models for inverse problem solving in microscopy; targeting high-fidelity image reconstruction from sparsely-sampled scans.
- **ISyE Directed Research Project (DRP):** day-ahead hourly load forecasting for the PJM Dominion market, comparing a Transformer, XGBoost, and a seasonal baseline on six years of hourly data.
- **Before this:** co-founded Noesis, a pre-submission peer review tool for academic researchers, and designed its [Stripe billing backend](https://github.com/praneel-thoom/noesis-billing-architecture) with signature-verified webhooks and exactly-once event processing.

### Live demos

| | |
| - | - |
| [thoom-polymarket-weather.streamlit.app](https://thoom-polymarket-weather.streamlit.app) | **Polymarket Weather Pipeline.** Do prediction markets move on hurricane odds before forecasts update? Serves a May 23 to Aug 17 2026 snapshot, and live AWS streaming is paused. [Source](https://github.com/praneel-thoom/polymarket-weather-pipeline) |
| [Tableau Public](https://public.tableau.com/views/ChessOpeningIntelligencePlatform/ChessOpeningIntelligencePlatform) | **Chess Opening Intelligence Platform.** Which openings win most at each rating level, built on over a million Lichess games. [Source](https://github.com/praneel-thoom/chess-opening-intel) |

### Selected work

| | |
| - | - |
| [polymarket-weather-pipeline](https://github.com/praneel-thoom/polymarket-weather-pipeline) | Python producers into Kafka, Spark Structured Streaming with watermarked joins into a Delta Lake medallion on S3, dbt on DuckDB, and a Streamlit dashboard. Backfill scripts feed the same Bronze tables, so live and historical data are treated identically. |
| [chess-opening-intel](https://github.com/praneel-thoom/chess-opening-intel) | A dbt star schema over 1M+ Lichess games from 4,563 players, with 8 automated data tests and a dashboard that flags openings whose win rates only look good at tiny sample sizes. |
| [noesis-billing-architecture](https://github.com/praneel-thoom/noesis-billing-architecture) | How Noesis billing is designed: a signature-verified Stripe webhook pipeline with exactly-once event processing over a dedup table, subscription lifecycle handling across three pricing tiers, and dunning for failed payments. Designed and tested, never run against live transactions. |
| [FirstWave](https://github.com/vaibhavw30/FirstWave) | Predictive EMS staging: forecast where 911 calls will cluster in the next hour and pre-position idle ambulances. I led the data pipeline and demand model. On 25,200 calls from a held-out year, calls reached within 8 minutes rose from 56.7% to 66.8%. GT Hacklytics 2026, SafetyKit Best AI for Human Safety. |

[GitHub](https://github.com/praneel-thoom) · [pthoom6@gatech.edu](mailto:pthoom6@gatech.edu)
