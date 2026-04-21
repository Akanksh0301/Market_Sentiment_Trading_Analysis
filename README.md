# Market Sentiment vs Trading Performance Analysis

## Overview
This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical trading data.

The analysis combines sentiment indicators (Fear & Greed Index) with real trading activity to uncover patterns in profitability, behavior, and market conditions.

---

## Objective
To understand how different market sentiment conditions impact:

- Profitability (Closed PnL)
- Win Rate
- Trading Volume

---

## Dataset

The datasets used in this project are available here:

👉 https://drive.google.com/drive/folders/1LH-eBu2HFqO-jz7RtZlttpq22vJ5O4Gx?usp=sharing

### Dataset Description

1. **Fear & Greed Index Dataset**
   - Contains daily sentiment classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)
   - Represents overall Bitcoin market mood  
   - The index ranges from 0 (Extreme Fear) to 100 (Extreme Greed) :contentReference[oaicite:0]{index=0}  

2. **Historical Trading Dataset**
   - Includes trade-level data such as:
     - Execution price
     - Trade size
     - Side (Buy/Sell)
     - Closed PnL
     - Fees
     - Timestamp  

---

## Tools Used

- Python
- Pandas
- Matplotlib

---

## Methodology

1. Data Cleaning
   - Standardized column names
   - Converted timestamps into datetime format  

2. Data Processing
   - Extracted date from timestamps
   - Merged trading data with sentiment data  

3. Analysis
   - Calculated:
     - Average Profit (PnL)
     - Win Rate
     - Trade Volume  

4. Visualization
   - Bar charts for:
     - Profitability by sentiment
     - Win rate by sentiment
     - Trade distribution  

---

## Key Insights

- Extreme Greed conditions produce the highest average profit per trade  
- Fear conditions also show strong profitability due to high volatility  
- Neutral markets show weaker performance due to lack of clear direction  
- Trade activity is highest during Fear periods  

---

## Conclusion

Market sentiment plays a significant role in trading performance.  
Traders tend to perform better in strong directional markets (Greed / Extreme Greed), while uncertain conditions reduce profitability.

These insights can help in designing sentiment-based trading strategies.

---

## File

- `Market_Sentiment_Trading_Analysis.ipynb`
