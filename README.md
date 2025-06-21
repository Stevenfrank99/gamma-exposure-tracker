# 🧠 SPY Gamma Exposure Tracker

This is a Python-based project to visualize and analyze SPY option market structure using gamma exposure, delta exposure, and implied volatility.

![Gamma Plot Example](https://github.com/Stevenfrank99/gamma-exposure-tracker/assets/your-image-placeholder.png)

## 📊 Features

- 📈 **Net Gamma Exposure (GEX)** by strike
- 🟢 **Long Gamma / 🔴 Short Gamma** zones (volatility damping/amplifying)
- 🚩 **Gamma Flip points**
- 🔶 **Dealer Delta Exposure** visualization
- 🌈 **Implied Volatility Surface**
- ⚠️ **IV Crush Zones** detection

---

## 🛠️ Tools Used

- `yfinance` – Live options and price data
- `scipy` – Black-Scholes Greeks
- `matplotlib`, `seaborn` – Plotting
- `pandas` – Data manipulation

---

## 📌 Current Metrics Output

```bash
📌 Spot Price: 543.21  
🧱 Max GEX at Strike: 545.00 with GEX: 100,000+  
⚠️ Nearest Gamma Flip: 540.00  
📉 Current Gamma Regime: Long Gamma  
