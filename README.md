# Market Risk Quant Portfolio (Python)

This repository contains a small set of end-to-end market risk projects implemented in Python.
Each project is designed to be reproducible, validated, and easy to review.

## Projects

### 1) VaR / ES Engine + Backtesting
- Methods: Historical VaR/ES, Parametric (Normal) VaR/ES, EWMA volatility VaR/ES
- Validation: VaR exceptions, Kupiec POF, Christoffersen independence
- Outputs: VaR/ES time series, exception plot, backtest summary

Path: `projects/01_var_es_backtesting/`

### 2) Stress Testing & Scenario Analysis (planned)
Path: `projects/02_stress_scenarios_options/`

### 3) Risk Decomposition & Limit Monitoring (planned)
Path: `projects/03_risk_decomposition_limits/`

## Quickstart

```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
pip install -r requirements.txt
