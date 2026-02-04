# 🛩️ Supply Chain Diffusion Alpha

**Quantitative Research Proposal for Teza Technologies (Summer 2026)**
*Author: Kenzo Garnier*

## Overview
This project implements a market-neutral statistical arbitrage strategy that exploits the information diffusion latency between "Prime Contractors" (e.g., Lockheed Martin) and their suppliers.

## Key Findings (2022-2026 Backtest)
* **Sharpe Ratio:** 0.92 (LMT/MOG.A Pair)
* **Win Rate:** 58%
* **Methodology:** Rolling OLS Regression + Granger Causality Tests
* **Constraint:** Strategy remains profitable after 45bps transaction costs.

## Repository Contents
* `Research_Proposal_Teza.pdf`: Full mathematical framework and thesis.
* `backtest_simulation.py`: Python code used to generate the equity curves and signals.
* `plots/`: Visualizations of the Lead-Lag effect.

## Tech Stack
* **Python:** Pandas, NumPy, Matplotlib, Statsmodels
* **Statistical Tools:** Granger Causality, Z-Score Normalization

---
*Note: This repository serves as a supplementary material for my application to the Quantitative Research Internship at Teza.*
