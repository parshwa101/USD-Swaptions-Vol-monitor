# USD Swaption Volatility Surface & Term Structure Dashboard

A modular quantitative pipeline and multi-panel visualization tool built in Python. Designed to ingest multi-tenor USD swaption volatility matrices, process rate-of-change velocity, and render institutional-grade analytics dashboards.

key Features:

Institutional Data Pipeline:** Structured architecture separating raw data ingestion, statistical analytics processing, and layout rendering.
- **Multi-Tenor Surface Matrix:** Processes implied volatility grids across 1m to 10y expiries and 1y to 30y swap tenors.

Velocity & Bleed Analytics: Computes 1-day change ($bps/day$), 1-month compression metrics, and automated risk threshold alerts.

Visualizations: Generates a multi-panel grid featuring divergence heatmaps (`RdYlGn`, `Reds_r`, `Greens`) and comparative term structure curves.

Tech Stack

- **Python 3.10+**
- **Pandas & NumPy** (Matrix operations, time-series transformations, and statistical summaries)
- **Matplotlib & Seaborn** (Institutional layout rendering, custom color maps, and multi-axes figure grids)

Project Structure

```text
usd-swaption-monitor/
│
├── usd_swaption_monitor.py    # Main pipeline and visualization script
├── requirements.txt           # Package dependencies
└── README.md                  # Project documentation
