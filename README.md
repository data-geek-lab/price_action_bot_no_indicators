# price_action_bot_no_indicators
Build a Python trading bot using price action breakout logic and Alpha Vantage API. No indicators.

# Price Action Trading Bot in Python (No Indicators)

This project is part of the **Beginner Algorithmic Trading Series** by *Data Geek is My Name* on YouTube.

In Episode 5, we build a pure price action trading bot — using **no indicators** like RSI or SMA.  
Instead, we use **breakout logic**:  
✅ Buy when the price breaks above the previous 5-day high  
✅ Sell when it drops below the previous 5-day low

---

## What You’ll Learn

- How to access free stock data using the Alpha Vantage API
- How to calculate breakout levels using price only (no indicators)
- How to generate buy/sell signals with pandas
- How to visualize those signals on a clean chart using matplotlib

---

## Tools Used

- Python
- `requests`
- `pandas`
- `matplotlib`
- [Alpha Vantage API](https://www.alphavantage.co/)

---

## Files Included

- `Price_Action_Bot_AlphaVantage.ipynb` – The full working notebook
- `README.md`

---

## 🔑 API Key

To run this notebook, you’ll need a free API key from [Alpha Vantage](https://www.alphavantage.co/support/#api-key).  
Store it safely in your code like this:
```python
api_key = 'YOUR_KEY_HERE'

**Watch the full tutorial on YouTube:**  
🎥 YouTube videos: https://www.youtube.com/watch?v=4jcVT56qSLo&list=PLUDxdzmiKmX68B9R5LzI6_JBr63bx_Jun

☕ **Support the channel** :
Buy Me a Coffee: https://buymeacoffee.com/datageekismyname

Follow me on YouTube:
https://www.youtube.com/@datageekismyname


