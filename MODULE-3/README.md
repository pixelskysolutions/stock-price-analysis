# 📊 Module 3: Probability, Statistics & Risk  

## 📌 Executive Summary  
This module introduces the foundations of **probability, statistics, and financial risk measurement**.  
We begin with simple simulations (coins, dice, and stock returns) to build intuition about randomness and distributions, then apply these principles to **quantify financial risk** using Value-at-Risk (VaR) and Conditional VaR (CVaR).  

Finally, we expand the scope to **portfolio risk and diversification**, showing how correlations between assets shape overall portfolio volatility and returns.  
By the end of this module, you’ll see how probability theory directly connects to **real-world finance** — from modeling uncertainty to managing portfolio risk.  

---

## 🔹 Core Topics Covered
- **Probability Basics** – events, conditional probability, Bayes’ rule.  
- **Distributions** – Normal, Log-normal, Binomial, Poisson.  
- **Descriptive Statistics** – mean, variance, skewness, kurtosis.  
- **Risk Measures** – standard deviation, Value-at-Risk (VaR), Conditional VaR (CVaR).  
- **Correlation & Dependence** – covariance matrices, portfolio diversification.  

---

## 📂 Project Roadmap  

### 1️⃣ Dice, Coins, and Stock Returns Simulation  
📓 Notebook: `Dice-Coins-and-Stock-Returns-Simulation.ipynb`  

- Simulated **coin flips** (Law of Large Numbers).  
- Simulated **dice rolls** (uniform distribution).  
- Generated **synthetic stock returns** from a normal distribution.  
- Plotted distributions and stock price paths.  

📈 **Charts**:  
- `[coin_toss_simulation.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/coin_toss_simulation.png)`  
- `[dice_roll_simulation.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/dice_roll_simulation.png)`  
- `[Simulated_Stock_Price.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/Simulated_Stock_Price.png)`  
- `[Distribution_of_Daily_Returns.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/Distribution_of_Daily_Returns.png)`  

---

### 2️⃣ Risk Metrics – Value-at-Risk (VaR)  
📓 Notebook: `Risk-Metrics-&-Value-at-Risk.ipynb`  

- Introduced **Value-at-Risk (VaR)** as a key risk measure.  
- Used three approaches:  
  - **Parametric (Variance-Covariance)**  
  - **Historical Simulation**  
  - **Monte Carlo Simulation**  
- Compared and visualized results at 95% confidence level.  

📈 **Charts**:  
- `[95%_Value_at_Risk_Estimates.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/95%25_Value_at_Risk_Estimates.png)`  
- `[Distribution_of_Simulated_Daily_Returns.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/Distribution_of_Simulated_Daily_Returns.png)`  

---

### 3️⃣ Risk Metrics – Value-at-Risk & Conditional VaR (CVaR)  
📓 Notebook: `Risk_Metrics_Value_at_Risk_&_Conditional_VaR.ipynb`  

- Extended VaR with **Conditional VaR (Expected Shortfall)**.  
- Showed how CVaR captures **tail risk beyond VaR cutoff**.  
- Compared **VaR vs CVaR** with historical simulations.  

📈 **Charts**:  
- `[VaR_&_CVaR_Historical_Method.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/VaR_%26_CVaR_Historical_Method.png)`  
- `[Distribution_of_Synthetic_Daily_Returns.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/Distribution_of_Synthetic_Daily_Returns.png)`  

---

### 4️⃣ Portfolio Risk & Diversification  
📓 Notebook: `Portfolio_Risk_and_Diversification.ipynb`  

- Constructed **synthetic multi-asset portfolios**.  
- Computed **expected returns, volatilities, Sharpe ratios**.  
- Visualized **correlation matrix & diversification effects**.  
- Saved supporting data files:  
  - `corr_empirical.csv`  
  - `cov_empirical.csv`  
  - `portfolio_returns_multi.csv`  
  - `[summary_portfolio_risk.json](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/summary_portfolio_risk.json)`  

📈 **Charts**:  
- `[corr_matrix.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/corr_matrix.png)`  
- `[diversification_vs_correlation.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/diversification_vs_correlation.png)`  
- `[risk_return_scatter.png](https://github.com/pixelskysolutions/stock-price-analysis/blob/main/MODULE-3/charts/risk_return_scatter.png)`  

---

## ✅ Wrap-Up
- Module 3 connected **probability theory** with **financial risk management**.  
- We saw how **randomness** drives outcomes in coins, dice, and stock returns.  
- Learned how to measure **risk** using **VaR & CVaR**.  
- Built intuition on **portfolio diversification** using correlation.  

📌 Next Step → Move to **Module 4: Financial Modeling & Time Series** 🚀  

---


