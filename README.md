# UK Property Investment & Yield Screener

> **Archived / off-brand.** This is a rules-based property tool, not a core machine-learning project, and sits outside my main behavioural-AI portfolio. It's kept public for reference. The previous README on this repo incorrectly described a retail sentiment pipeline — that has been corrected to match the actual notebook.

## What it does
A screening tool that filters UK property listings to surface high-yield buy-to-let opportunities. It calculates acquisition costs — including **UK Stamp Duty Land Tax (SDLT)** — and rental yield, then ranks listings by ROI.

- **Type:** rules-based financial calculator + ranking (not a predictive ML model).
- **Data:** uses a `generate_mock_listings()` simulator standing in for a Rightmove/Zoopla scrape, so the notebook is reproducible without API keys. This is clearly a demonstration, not real market data.

## Tech Stack
Python · pandas · NumPy · Matplotlib · Seaborn

## How to Run
```bash
git clone https://github.com/kndukuba17-hub/UK-Property-Investment-Tool.git
cd UK-Property-Investment-Tool
pip install -r requirements.txt
jupyter notebook notebooks/uk_property_yield_screener.ipynb
```

---
*If revisited, the natural upgrade is to wire in a real listings source and add a predictive price/yield model — at which point it would earn a place in the main portfolio.*
