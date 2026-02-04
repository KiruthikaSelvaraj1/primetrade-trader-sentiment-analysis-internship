# primetrade-trader-sentiment-analysis-internship
Analysis of trader performance and behavior on Hyperliquid under Bitcoin Fear &amp; Greed market sentiment, with actionable trading insights.
# Trader Performance vs Market Sentiment Analysis

This repository contains the Round-0 assignment submission for the Data Science Intern role at Primetrade.ai.

The project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on the Hyperliquid trading platform and derives actionable insights from observed patterns.

---

## Repository Structure

```
primetrade-trader-sentiment-analysis/
│
├── trader_sentiment_analysis.ipynb
├── README.md
├── requirements.txt
└── outputs/
    ├── average_trade_frequency_bysentiment.png
    ├── average_tradesize_by_marketsentiment.png
    ├── avg_trade_size_bysentiment.png
    ├── Behaviour_change_on_sentiment_summary.png
    ├── fear_vs_greed.png
    ├── fear-vs-greed_chart.png
    ├── frequency_segment_vs_classification.png
    ├── leveragesegment_vs_classification.png
    └── winnersegment_vs_classification.png
```

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/primetrade-trader-sentiment-analysis.git
cd primetrade-trader-sentiment-analysis
```

### 2. Install Dependencies

Ensure Python 3.8 or higher is installed.

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Open `trader_sentiment_analysis.ipynb` in Jupyter Notebook or Visual Studio Code.
2. Run all cells sequentially from top to bottom.
3. The notebook performs:
   - Data loading and cleaning
   - Timestamp conversion and daily alignment
   - Feature engineering for trader performance and behavior
   - Sentiment-based analysis and trader segmentation
   - Visualization and summary generation
4. All output charts are automatically saved in the `outputs/` directory.

---

## Outputs Description

The `outputs/` folder contains all visual evidence supporting the analysis:

- **fear_vs_greed.png / fear-vs-greed_chart.png**  
  Comparison of trader performance across Fear and Greed market conditions.

- **average_trade_frequency_bysentiment.png**  
  Average number of trades per day under different sentiment regimes.

- **avg_trade_size_bysentiment.png** and **average_tradesize_by_marketsentiment.png**  
  Trade size behavior across Fear and Greed periods.

- **Behaviour_change_on_sentiment_summary.png**  
  Summary visualization highlighting key behavioral shifts driven by sentiment.

- **frequency_segment_vs_classification.png**  
  Performance comparison of frequent vs infrequent traders across sentiment regimes.

- **leveragesegment_vs_classification.png**  
  Impact of leverage-based trader segmentation under Fear and Greed conditions.

- **winnersegment_vs_classification.png**  
  Performance consistency of winning vs inconsistent traders across sentiment regimes.

---

## Author

Kiruthika S

