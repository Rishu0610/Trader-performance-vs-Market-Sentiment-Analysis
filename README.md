# Trader-performance-vs-Market-Sentiment-Analysi

## 📌 Project Objective
Explore how market sentiment (Fear & Greed Index) influences trader performance, uncover hidden patterns, and build models to improve trading strategies.

## 📊 Data Sources
- **Trader Activity Data:** Includes execution price, volume, PnL, timestamp.
- **CNN Fear & Greed Index:** Daily sentiment score & classification.

## 🔧 Tools Used
- Python, Pandas, Matplotlib, Seaborn
- Scikit-learn (for machine learning)
- Jupyter Notebook

## 📈 Key Analyses
- 📅 Aggregated daily trading metrics (PnL, volume, trader count)
- 📉 Correlation analysis with sentiment index
- 📦 Boxplots of PnL across sentiment categories
- 🔍 Predictive model using Random Forest to estimate daily PnL

## 💡 Insights
- No strong linear correlation between sentiment index and profit
- Greed periods showed high volume but inconsistent profit
- Sentiment can help frame risk but should be paired with technical metrics

## 📁 Output Files
- `trader_sentiment_analysis.csv` - Final merged dataset
- `trader_sentiment_analysis_visuals.png` - Summary visualization

## 📷 Visualization Preview
![visuals](trader_sentiment_analysis_visuals.png)

## 📍 Conclusion
Market sentiment affects behavior, but not always profitability. Smart strategies can use sentiment as context to guide trade timing, volume, and caution.

---
