# 📊 Module 3: Probability, Statistics & Risk  

This module builds intuition about probability, randomness, and statistical risk measures in finance.  
We move from **coins & dice** → **stock return simulations** → **risk metrics** → **portfolio diversification**.  

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
- `coin_toss_simulation.png`  
- `dice_roll_simulation.png`  
- `Simulated_Stock_Price.png`  
- `Distribution_of_Daily_Returns.png`  

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
- `95%_Value_at_Risk_Estimates.png`  
- `Distribution_of_Simulated_Daily_Returns.png`  

---

### 3️⃣ Risk Metrics – Value-at-Risk & Conditional VaR (CVaR)  
📓 Notebook: `Risk_Metrics_Value_at_Risk_&_Conditional_VaR.ipynb`  

- Extended VaR with **Conditional VaR (Expected Shortfall)**.  
- Showed how CVaR captures **tail risk beyond VaR cutoff**.  
- Compared **VaR vs CVaR** with historical simulations.  

📈 **Charts**:  
- `VaR_&_CVaR_Historical_Method.png`  
- `Distribution_of_Synthetic_Daily_Returns.png`  

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
  - `summary_portfolio_risk.json`  

📈 **Charts**:  
- `corr_matrix.png`  
- `diversification_vs_correlation.png`  
- `risk_return_scatter.png`  

---

## ✅ Wrap-Up
- Module 3 connected **probability theory** with **financial risk management**.  
- We saw how **randomness** drives outcomes in coins, dice, and stock returns.  
- Learned how to measure **risk** using **VaR & CVaR**.  
- Built intuition on **portfolio diversification** using correlation.  

📌 Next Step → Move to **Module 4: Financial Modeling & Time Series** 🚀  

---

