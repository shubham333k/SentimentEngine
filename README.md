📌 Project Overview

This project explores the intersection of behavioral finance and cryptocurrency trading. By analyzing Bitcoin market sentiment (Fear vs. Greed ) alongside granular trader data from Hyperliquid, I conducted a statistical investigation into how market "moods" influence actual trading outcomes.

The core objective was to move beyond anecdotal evidence and provide a data-backed understanding of how sentiment regimes dictate profitability, trading intensity, and risk profiles.




🔍 Key Insights & Findings

Through rigorous statistical analysis (including Welch’s t-tests), the following patterns were identified:

•
🚀 Greed Regimes & Profitability: Trading activity and average daily PnL significantly expand during "Greed" periods, suggesting a positive momentum bias.

•
⚠️ Fear Regimes & Volatility: "Fear" environments lead to higher downside dispersion, with loss volatility widening significantly compared to Greed regimes.

•
📊 Sentiment Sensitivity: High-activity traders are the most sensitive to sentiment shifts, showing amplified upside and downside exposure.

•
🛡️ Regime Resilience: Traders with high historical win rates demonstrate remarkable stability, maintaining consistent performance even during extreme sentiment shifts.




🛠️ Tech Stack & Methodology

Tech Stack

•
Language: Python

•
Libraries: Pandas (Data Wrangling), NumPy (Numerical Analysis), Matplotlib/Seaborn (Visualization), Scipy (Statistical Testing)

•
Environment: Jupyter Notebook

Methodology

1.
Data Alignment: Synchronized high-frequency Hyperliquid trade data with daily Bitcoin Fear & Greed Index values.

2.
Feature Engineering: Developed custom metrics including Daily PnL, Win Rate, Behavioral Intensity (trades/day), and Long/Short Ratios.

3.
Statistical Validation: Applied Welch’s t-test to validate performance differences across sentiment regimes.

4.
Trader Segmentation: Categorized the user base into activity-based and performance-based segments to analyze divergent behavioral patterns.




💡 Strategic Recommendations

1. Sentiment-Aware Risk Scaling

Traders should consider reducing exposure and trade frequency during "Fear" regimes to mitigate the higher downside dispersion, while expanding controlled participation during "Greed" regimes.

2. Segment-Based Capital Allocation

Institutional platforms can use these insights to adjust leverage limits or margin requirements dynamically based on the prevailing market sentiment and a trader's historical "regime resilience."




📂 Project Structure

•
analysis.ipynb: The core research notebook containing data cleaning, EDA, statistical tests, and visualizations.

•
README.md: Project documentation and executive summary.




🤝 Contact

Shubham Kumar - LinkedIn - shubhamjhanjhot333k@gmail.com

Project Link: https://github.com/shubham333k/Trader-Performance-vs-Market-Sentiment-Analysis

