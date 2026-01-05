# WIDS_5
The Repo for WiDS 2025.
This repository contains the code and notebooks used in the project on Optimal Portfolio Allocation.
Each notebook in this repository is week-wise and self-contained in itself.There is no dependency or execution order between notebooks.
```
1.Python for Quantitative Analysis
  Used NumPy for vectorized mathematical operations
  Used Matplotlib for financial visualizations
  Implemented calculations using matrix algebra instead of loops wherever possible.

2. Financial Data Handling
  Downloaded historical asset prices using yfinance
  Converted price data into:
    Simple returns
    Log returns

Worked with daily data and annualized:
  Expected returns
  Volatility
  Covariance matrices

3. Risk & Return Analysis
Computed:
  Individual asset risk (volatility)
  Portfolio expected return
  Portfolio variance and standard deviation
  Studied the role of covariance and correlation in diversification

4. Portfolio Generation (Brute Force)
  Generated feasible portfolio weight combinations under constraints
  Constructed a risk–return cloud
  Visualized how different weight allocations affect portfolio performance

5. Optimization Techniques
Formulated portfolio variance as a quadratic form
  Computed:
    Minimum variance portfolio
    Markowitz portfolios for different target returns
    Constructed the efficient frontier
    Compared optimized portfolios against brute-force feasible portfolios

6. Stress Testing
  Applied stress to the correlation / covariance matrix
  Recomputed portfolio volatility under stressed conditions
  Compared original vs stressed risk to study robustness
  Observed how increased correlation reduces diversification benefits
  ```

