# Project 01 — VaR / ES Engine + Backtesting (Python)

## Objective
Build and validate a daily market risk engine that computes VaR and Expected Shortfall (ES), and evaluates model performance using standard backtesting tests.

## Models
- Historical Simulation VaR/ES
- Parametric (Normal) VaR/ES
- EWMA volatility VaR/ES (RiskMetrics-style)

## Validation
- VaR exception tracking
- Kupiec POF (unconditional coverage)
- Christoffersen independence (clustering)

## Structure
- `src/` : reusable functions (returns, VaR/ES calculators, backtests)
- `notebooks/` : end-to-end demo notebook
- `reports/` : short write-up (optional)
- `outputs/` : generated plots/tables

## How to run
From repo root:

```bash
pip install -r requirements.txt
