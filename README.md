<div align="center">

# 📈 Behavioral Alpha
### Market Sentiment & Trader Performance Research

*Quantifying how psychology drives profitability in crypto markets*

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![SciPy](https://img.shields.io/badge/SciPy-Statistical_Testing-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)](https://scipy.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

## 🏛️ Executive Summary

> This research project explores the quantitative relationship between Bitcoin Market Sentiment (Fear & Greed Index) and the behavioral performance of traders on the Hyperliquid decentralized exchange. By moving beyond qualitative assumptions, this study utilizes rigorous statistical methods to identify how psychological regimes dictate profitability, risk-taking, and market intensity.

---

## 🔍 Core Research Findings

| Regime | Market Impact | Trader Behavior | Risk Profile |
|---|---|---|---|
| **Greed** | 🚀 Profitability Expansion | Increased Trade Frequency | Positive Momentum Bias |
| **Fear** | ⚠️ Downside Dispersion | Reduced Activity | High Volatility & Loss Variance |

### 💡 Key Analytical Insights

- 📊 **Momentum Amplification** — Greed regimes correlate with a significant expansion in average daily PnL across most segments.
- 📉 **Volatility Asymmetry** — Fear regimes do not just lower profits; they exponentially increase the variance of losses.
- ⚡ **Segment Sensitivity** — High-frequency traders exhibit the highest "Sentiment Beta," making them vulnerable to rapid regime shifts.
- 🛡️ **Regime Resilience** — A subset of "Consistent Traders" was identified who maintain stable equity curves regardless of sentiment.

---

## 🛠️ Technical Architecture

**Data Pipeline & Workflow**
📥 Data Acquisition  →  🔗 Timestamp Alignment  →  🧮 Feature Engineering  →  📐 Statistical Validation  →  🎯 Segmentation

1. **Data Acquisition** — Hyperliquid Trade Data & Fear & Greed Index API.
2. **Data Alignment** — Synchronization of trade timestamps with daily sentiment scores.
3. **Feature Engineering** — Calculation of PnL, Win Rate, and Behavioral Intensity.
4. **Statistical Validation** — Welch's t-test to confirm regime-based performance variance.
5. **Segmentation** — Categorizing traders by activity and resilience.

### 🧰 Tech Stack

| Component | Tool Used |
|:---|:---|
| ⚙️ **Engine** | Python 3.10+ |
| 📊 **Analysis** | Pandas, NumPy, SciPy (Welch's t-test validation) |
| 📈 **Visualization** | Seaborn, Matplotlib, Plotly |
| 📓 **Environment** | Jupyter Research Environment |

---

## 🚀 How to Run

1. **Clone the repository**
```bash
   git clone https://github.com/shubham333k/SentimentEngine.git
   cd SentimentEngine
```

2. **Install dependencies**
```bash
   pip install pandas numpy scipy seaborn matplotlib plotly jupyter
```

3. **Launch Jupyter Notebook**
```bash
   jupyter notebook
```

4. Open **`analysis.ipynb`** to explore the full research lifecycle — from data cleaning to statistical testing.

---

## 💡 Strategic Recommendations

**1. Sentiment-Adaptive Risk Management**
Institutional and retail traders should implement Regime-Based Exposure Scaling. Reducing leverage and position sizing during "Extreme Fear" can mitigate the statistically proven downside dispersion.

**2. Dynamic Capital Allocation**
Platforms can utilize these findings to build Sentiment-Aware Margin Engines that adjust collateral requirements based on the prevailing market psychology and individual trader "Regime Resilience" scores.

---

## 📂 Repository Structure

```
SentimentEngine/
├── analysis.ipynb    # Full research lifecycle (Cleaning → EDA → Statistical Testing)
└── README.md          # Executive documentation
```

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

## 🤝 Connect & Collaborate

**Shubham Kumar**
*Computer Science (AIML) Undergraduate*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubhamkumar-aiml/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shubham333k)

*This project was developed as part of a Data Science Research Assignment.*

</div>
