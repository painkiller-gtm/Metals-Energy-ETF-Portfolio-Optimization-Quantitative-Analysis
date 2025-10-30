# Metals & Energy ETF Portfolio Optimization — A Quantitative Analysis (2018–2024)

## 1. Project Overview

As a **Metallurgy and Materials Science Engineering student**, my academic work has primarily focused on the properties, production, and technological relevance of materials. However, the **financial dimension** of metals and energy markets is equally crucial in understanding their real-world dynamics and value chains.  

This project was developed to bridge **materials science** and **financial analytics** by quantitatively analyzing the performance and optimization of **metals, mining, and energy ETFs** using modern portfolio theory.  

The goal is to explore how **engineering commodities translate into financial assets**, assess their **systematic risk**, and design a **diversified investment strategy** that reflects both **industrial cyclicality** and **technological transition** trends (such as electrification, clean energy, and resource supply chains).

---

## 2. Objectives

1. Analyze and quantify **systematic risk (β, α, R²)** for metals, mining, and energy ETFs relative to the S&P 500 benchmark.  
2. Construct and optimize a **materials–energy portfolio** using the **Markowitz mean–variance framework**.  
3. Integrate **downstream sectors** (EVs, semiconductors, clean energy) and assess diversification effects.  
4. Connect financial performance modeling with **materials economics**, showcasing how commodity trends impact investment efficiency.

---

## 3. Methodology

This notebook applies **quantitative finance models** and **data analytics techniques** on market data spanning **2018–2024**.

| Analysis Stage | Description |
|----------------|-------------|
| **Data Acquisition** | Historical ETF data using `yfinance` API |
| **Return Calculations** | Daily, cumulative, and annualized returns |
| **CAPM Analysis** | Regression vs. S&P 500 to compute Beta (β), Alpha (α), and R² |
| **Risk Metrics** | Computation of Value-at-Risk (VaR) and Conditional VaR (CVaR) |
| **Portfolio Optimization** | Markowitz mean–variance optimization to maximize Sharpe ratio |
| **Diversification Strategy** | Correlation and performance study across downstream sectors |

---

## 4. Tools and Libraries

- **Languages & Environment:** Python, Jupyter Notebook  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy.optimize`, `statsmodels`, `yfinance`  
- **Analytical Frameworks:**  
  - Capital Asset Pricing Model (CAPM)  
  - Markowitz Efficient Frontier  
  - Value-at-Risk and Conditional VaR  
  - Correlation and diversification metrics  

---

## 5. Key Results

| Portfolio | Annual Return | Volatility | Sharpe Ratio |
|------------|----------------|-------------|---------------|
| Metals–Energy Portfolio | 10.09% | 27.45% | 0.37 |
| Optimized Portfolio | 11.86% | 29.53% | 0.40 |
| Diversified Portfolio | 13.23% | 25.70% | 0.51 |
| S&P 500 (Benchmark) | 15.16% | 19.44% | 0.78 |

**Findings:**
- Metals and energy ETFs exhibit **high market sensitivity (β ≈ 1.0–1.2)**, confirming strong cyclical exposure.  
- Portfolio optimization improved **risk-adjusted performance**, while **cross-sector diversification** achieved a **38% Sharpe ratio improvement** and reduced volatility.  
- The diversified model represents the **economic linkage between production-side commodities and consumption-side industries**, reflecting real-world material and energy cycles.

---

## 6. Insights and Implications

- **For Materials Science:** Demonstrates how financial modeling quantifies cyclicality and market exposure of metallurgical and energy resources.  
- **For Finance:** Highlights the efficiency gains from cross-sector diversification across commodities and industry users.  
- **For Industry:** Provides a framework to evaluate **supply-chain resilience** and **resource investment strategies** under changing macroeconomic conditions.

---

## 7. Applications

- **Finance & Quantitative Research:** Portfolio optimization, ETF performance analytics, and systematic risk modeling.  
- **Materials & Metallurgy:** Linking commodity performance to market demand and industrial cycles.  
- **Semiconductors & Clean Energy:** Understanding dependencies between material inputs and technology sectors.

---

## 8. Technical Summary

- Developed a **data-driven analytics pipeline** for ETF performance and portfolio construction.  
- Implemented **CAPM regression**, **Markowitz optimization**, and **risk metric evaluation**.  
- Visualized growth, correlation, and diversification through clean, reproducible statistical plots.  
- Established an interdisciplinary link between **financial markets** and **materials economics**.

---


