# Music Streaming Revenue Analysis

A data science case study analyzing revenue trends across major DSPs (Spotify, YouTube, Apple Music, Amazon, TikTok) using a Revenue Per Stream (RPS) methodology.

## Motivation

Streaming royalty structures vary significantly across platforms — a stream on Spotify is not worth the same as one on YouTube or TikTok. This project models per-platform RPS using trailing windows to produce defensible revenue accrual forecasts, accounting for platform-specific reporting lags and structural anomalies (e.g. the TikTok volume/RPS paradox).

## Tech Stack

- **Python** — pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook** — analysis and visualization
- **Excel** — output reporting

## Repo Structure

```
music-streaming-revenue-analysis/
├── Music_Streaming_Revenue_Analysis.ipynb   # Full analysis
├── Music_Streaming_Revenue_Analysis.pptx    # Executive presentation
└── output/
    ├── monthly_revenue_trend.png
    ├── revenue_by_dsp.png
    ├── revenue_by_territory.png
    ├── rps_trends.png
    ├── tiktok_paradox.png
    └── revenue_analysis_output.xlsx
```

## How to Run

```bash
git clone https://github.com/Swapnil-Dubey/music-streaming-revenue-analysis.git
cd music-streaming-revenue-analysis
python -m venv venv
source venv/bin/activate
pip install pandas numpy matplotlib seaborn openpyxl jupyter
jupyter notebook
```

> **Note:** The raw dataset is not included in this repo as it is proprietary. The notebook and all outputs are fully reproducible given a dataset matching the expected schema.
