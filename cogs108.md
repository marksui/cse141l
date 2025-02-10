# Project Proposal: Data-Driven Market State Assessment  
**Identifying Market Trends and Risk Levels Using Quantitative Analysis**

## 1. NAMES  
- **Group Member 1:** Bohang Kang  
- **Group Member 2:** Mukund Dittakavi  
- **Group Member 3:** Mark Sui  
- **Group Member 4:** Tianyu Li  
- **Group Member 5:** Pranshu Gupta  

---

## 2. RESEARCH QUESTION  
**How can we quantitatively classify the overall state of financial markets using historical price and volatility data?**  

Specifically:  
1. What are the key indicators that best define market trends (bullish, bearish, or neutral)?  
2. Can we develop a simple scoring system to assess the risk level of the market?  
3. How do historical trends in volatility relate to different market phases?  

This research aims to provide a **data-driven approach** to evaluating market conditions, assisting investors and policymakers in making informed decisions.

---

## 3. BACKGROUND  
Financial markets are constantly evolving, and identifying the overall market state is essential for investors and institutions. Traditionally, market conditions have been assessed subjectively through news sentiment, economic reports, and price charts. However, with the increasing availability of data, **quantitative approaches** have gained prominence.

### Key concepts in prior research:  
#### 1. Market Volatility as a Risk Indicator  
- The **VIX Index (CBOE Volatility Index)** is widely used as a measure of market fear and uncertainty. Higher VIX values are historically associated with bear markets and economic downturns (**Whaley, 2000**).  
- Research shows that **market volatility often spikes before major market corrections** (**Giot, 2005**).

#### 2. Market Regimes and State Classification  
- Financial markets tend to alternate between distinct phases: **bullish (growth), bearish (decline), and neutral (sideways trading)**.  
- Some studies use **Hidden Markov Models (HMMs) and clustering methods** to identify these regimes (**Ang & Timmermann, 2012**).

#### 3. Simple Market Trend Indicators  
- **Moving averages (50-day and 200-day)** have historically been used to indicate trends (**Fama & French, 1988**).  
- **Momentum-based indicators** like MACD and RSI have been used in previous works to study market movement (**Jegadeesh & Titman, 1993**).

While prior studies provide valuable insights, many rely on **complex statistical models** that are difficult to interpret for everyday investors.  
Our project seeks to build a **simpler and interpretable model** to assess market conditions using volatility, price movements, and technical indicators.

### References  
1. Whaley, R. E. (2000). The Investor Fear Gauge. *Journal of Portfolio Management, 26(3), 12-17.*  
2. Giot, P. (2005). Implied volatility indexes and daily stock market returns. *Journal of Derivatives, 12(4), 54-64.*  
3. Ang, A., & Timmermann, A. (2012). Regime Changes and Financial Markets. *Annual Review of Financial Economics, 4, 313-337.*  
4. Fama, E. F., & French, K. R. (1988). Permanent and Temporary Components of Stock Prices. *Journal of Political Economy, 96(2), 246-273.*  
5. Jegadeesh, N., & Titman, S. (1993). Returns to Buying Winners and Selling Losers: Implications for Stock Market Efficiency. *Journal of Finance, 48(1), 65-91.*  

---

## 4. HYPOTHESIS  
- **Financial markets exhibit distinguishable states** (bullish, bearish, or neutral) that can be quantified using volatility and trend indicators.  
- **Periods of extreme volatility often precede significant market corrections** (e.g., crashes or recessions).  
- A **market risk scoring system** based on volatility and momentum indicators can provide an **early warning for high-risk market conditions**.

---

## 5. DATA  

| **Type**               | **Source**                    | **Variables**                                      |
|------------------------|------------------------------|----------------------------------------------------|
| **Stock & Futures Prices** | Yahoo Finance, AkShare      | Open, High, Low, Close (OHLC), Volume              |
| **Market Volatility**  | VIX (CBOE Volatility Index)  | VIX levels, historical volatility                  |
| **Macroeconomic Data** | FRED, IMF                    | Interest rates, GDP growth, inflation              |
| **Market Indicators**  | Technical Indicators         | Moving Averages, RSI, MACD                         |

---

## 6. ETHICS & PRIVACY CONSIDERATIONS  

### 1. Bias & Fairness  
- **Data is sourced from publicly available financial datasets**, eliminating privacy concerns.  
- However, our dataset **may be biased toward developed markets** (e.g., S&P 500, Nasdaq) and exclude emerging market trends.

### 2. Terms of Use & Transparency  
- Ensure **compliance** with API usage limits and data provider policies.  
- Clearly **document data sources and methodology** in our final report.

### 3. Potential Limitations & Mitigation Strategies  
- **Historical data may not fully represent future market behavior.**  
  - We will acknowledge this limitation and avoid overfitting models.  
- **Outlier events (e.g., COVID-19 crash) could distort results.**  
  - We will conduct robustness checks to mitigate this issue.

---

## 7. DATA ANALYSIS APPROACH  
- **Collaboration & Communication:** Weekly check-ins to track progress.  
- **Workload Distribution:** Each member contributes to both analysis and documentation.  
- **Conflict Resolution:** Any disagreements will be resolved through discussion and consensus.  
- **Responsibility:** Members are expected to complete assigned tasks on time.  

---

## 8. PROJECT TIMELINE PROPOSAL  

| **Date**  | **Task**                                 | **Responsible Member(s)**  |
|----------|--------------------------------------|---------------------------|
| Week 1  | Data collection and cleaning        | Tianyu, Pranshu, Mark     |
| Week 2-3  | Exploratory Data Analysis (EDA)   | Mukund, Tianyu, Pranshu   |
| Week 4  | Market state classification (bull/bear/neutral) | Velane, Mark, Pranshu  |
| Week 5  | Market risk scoring system          | Mukund, Mark, Velane     |
| Week 6  | Model validation & visualization    | Velane, Mukund, Tianyu, Mark |
| Week 7  | Final report writing & submission   | All Members              |

---

## 9. EXPECTED DELIVERABLES  
- **Dataset** with structured market data.  
- **Market classification model** (simple rule-based + clustering).  
- **Market risk scoring system** to quantify risk levels.  
- **Final report & presentation** summarizing key insights.  
