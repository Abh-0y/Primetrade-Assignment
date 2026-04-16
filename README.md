# **OVERVIEW**

This project analyzes the relationship between market sentiment (Fear vs Greed) and trader behavior & performance using real trading data from Hyperliquid and Bitcoin sentiment data.

---

# **OBJECTIVES**
- Analyze how market sentiment impacts trader performance (PnL, win rate)
- Understand changes in trading behavior (trade size, frequency, direction)
- Identify different trader segments
- Propose actionable strategies based on insights

---

# **DATASET USED**
1. Bitcoin Market Sentiment Dataset
- `date`
- `classification` (Fear / Greed)
- `value` (Fear & Greed Index)

2. Historical Trader Data (Hyperliquid)
- `Account`, `Coin`, `Execution Price`
- `Size USD`, `Side`, `Timestamp`
- `Start Position`, `Closed PnL`
- `Fee`, `Direction`, `Crossed`

---

# **METRICS CREATED**

- Daily PnL per trader
- Win rate
- Average trade size per account
- Average Trade size per day
- Long/Short ratio
- Closed PnL vs Sentiment
- win_rate vs sentiment
- Behavior Change
- Frequent vs Infrequent traders
- Consistent winners vs Inconsistent traders

---

# **INSIGHTS**

1. Sentiment Impacts Performance
- Traders perform worse during Fear periods
- Greed periods show relatively better and more stable profitability

2. Risk Behavior is Sentiment-Driven
- Traders take larger positions and trade more frequently during Greed
- During Fear, traders reduce exposure and act conservatively

3. Aggressive Trading Increases Risk
- Larger trade sizes and higher exposure lead to:
- - Higher PnL volatility
- - Less consistent performance
-Risk is amplified during Fear periods

---

# **TOOLS USED**
- Python
- Pandas
- Google Colab
