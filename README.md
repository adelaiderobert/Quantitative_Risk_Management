# Quantitative_Risk_Management

These two projects were awarded the **maximum grade (6/6)** in the *Quantitative Risk Management* course at **EPFL (Fall 2025)*
The projects focus on **market risk**, **credit risk**, and **statistical learning**, with practical implementations in Python using real and simulated financial data.

---

## Repository Structure

```
├── Project1_notebook.ipynb
├── Project2_notebook.ipynb
├── QRM-Project1_Description.pdf
├── QRM-Project2_Description.pdf
└── README.md
```


---

## Project 1 — Market Risk: VaR, ES & Copulas

This project focuses on **market risk measurement** and **dependence modeling** using financial time series.

Main objectives:

- Compute and analyze **Value-at-Risk (VaR)** and **Expected Shortfall (ES)**
- Study stylized facts of financial returns (volatility clustering, fat tails)
- Fit different statistical models:
  - Historical simulation
  - Gaussian distribution
  - Student-t distribution
  - AR + GARCH models
  - Filtered Historical Simulation (FHS)
- Perform **backtesting** of risk models:
  - Kupiec test (coverage)
  - Christoffersen test (independence)
  - Acerbi–Székely test for ES
- Model dependence between assets using:
  - Gaussian copula
  - Student-t copula
- Evaluate portfolio risk with and without dependence modeling

### Data

- Assets: **AAPL, META, JPM**
- Period: Jan 2023 – June 2025
- Data source: `yfinance`

### Key Skills

- Time series analysis
- Volatility modeling (GARCH)
- Risk metrics (VaR, ES)
- Backtesting methodologies
- Copula modeling

---

## Project 2 — Credit Risk & Statistical Learning

This project focuses on **credit risk modeling** and **machine learning methods** for loan default prediction.

Main objectives:

- Simulate borrower features:
  - age
  - income
  - employment status
- Generate repayment probabilities using nonlinear models
- Train and compare predictive models:
  - Logistic Regression
  - Support Vector Machine (SVM with RBF kernel)
- Evaluate models using:
  - Cross-entropy loss
  - ROC curves
  - AUC
- Design and evaluate **lending strategies**
- Simulate profit & loss distributions
- Compute **VaR and ES on P&L**

### Key Skills

- Classification models
- Model evaluation (ROC, AUC)
- Simulation techniques
- Risk-return trade-off analysis
- Decision-making under uncertainty

---

## Technologies Used

- Python
- NumPy, Pandas
- Matplotlib / Seaborn
- SciPy / Statsmodels
- scikit-learn
- yfinance

---

## Highlights

- End-to-end implementation of risk models (from data to backtesting)
- Combination of **financial theory** and **machine learning**
- Strong focus on **model validation and interpretation**
- Practical experience with **realistic financial datasets**

---
