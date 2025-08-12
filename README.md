# Trader Behavior vs Market Sentiment 

This project explores the relationship between trader behavior (PnL, leverage, volume) and the Bitcoin Fear & Greed Index.

---

## Directory Structure

```
ds_<your_name>/
├── notebook_1.ipynb
├── csv_files/
│   └── sentiment_aggregated_stats.csv
├── outputs/
│   ├── sentiment_distribution.png
│   ├── pnl_vs_sentiment.png
│   ├── leverage_vs_sentiment.png
│   └── volume_vs_sentiment.png
├── ds_report.pdf
└── README.md
```

---

## Datasets

- `historical_data.csv` - Trade-level data (timestamp, size, execution price, PnL, etc.)
- `fear_greed_index.csv` - Daily sentiment classification as Fear or Greed

---

## How to Run

1. Open `notebook_1.ipynb` in Google Colab or Jupyter
2. Upload the two CSVs
3. Run all cells
4. View generated plots in `outputs/` and summaries in `csv_files/`

---

## Insights

- Greed periods show higher volume and leverage
- Fear periods show higher volatility in PnL
- Sentiment correlates with risk-taking behavior

---

