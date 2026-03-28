# trader-behavior-insights
Analysis of trader performance vs Bitcoin market sentiment
## 📌Objective
Explore the relationship between trader performance on Hyperliquid 
and Bitcoin market sentiment (Fear & Greed Index).

## 📂 Datasets Used
- **Historical Trader Data** from Hyperliquid (211,224 trades)
- **Bitcoin Fear & Greed Index** (2,644 daily sentiment records)

## 🔧 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

## 📊 Key Analyses Performed
1. Exploratory Data Analysis (EDA) on both datasets
2. Data cleaning & preprocessing
3. Merging datasets on date
4. PnL analysis by market sentiment
5. Win rate by sentiment (Fear vs Greed)
6. Trading volume by sentiment
7. Top 10 performing accounts
8. Buy vs Sell behavior during Fear/Greed
9. Correlation heatmap
10. Monthly PnL trend over time
11. Best & worst performing coins

## 🔑 Key Findings
- Traders perform **better during Greed** phases vs Fear
- **@107, HYPE, SOL** are top performing coins
- **TRUMP, FARTCOIN** showed highest losses (meme coins)
- Platform saw **massive growth from Oct 2024**
- Sentiment score has **near-zero linear correlation** (0.0092) 
  with PnL — but categorical sentiment matters significantly
- **Size USD & Fee** have strong correlation (0.76)
