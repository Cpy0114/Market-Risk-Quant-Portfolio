# Market Risk Quant Portfolio (Python)

A small set of end-to-end market risk projects implemented in Python.  
Focus: **VaR / Expected Shortfall (ES)**, **model validation/backtesting**, and **reproducible risk reporting**.

## Projects

### ✅ Project 01 — VaR / ES Engine + Backtesting (complete)
- **Methods:** Historical VaR/ES, Parametric (Normal) VaR/ES, EWMA volatility VaR/ES  
- **Validation:** VaR exceptions, Kupiec POF, Christoffersen independence  
- **Outputs:** VaR/ES time series, exception diagnostics, backtest summary (CSV)

→ **Open:** [projects/01_var_es_backtesting/](projects/01_var_es_backtesting/)

### Project 02 — Stress Testing & Scenario Analysis (planned)
Path: `projects/02_stress_scenarios_options/`

### Project 03 — Risk Decomposition & Limit Monitoring (planned)
Path: `projects/03_risk_decomposition_limits/`

## Quickstart

```bash
python -m venv .venv
source .venv/bin/activate  # macOS/Linux
# .venv\Scripts\activate   # Windows
pip install -r requirements.txt
```
Then open:
- `projects/01_var_es_backtesting/notebooks/01_var_es_backtesting.ipynb`

## Portfolio highlights
- Built a Python VaR/ES engine (Historical, Normal, EWMA) with standard backtesting (Kupiec POF, Christoffersen independence).
- Produced exception diagnostics, time-series plots, and reproducible outputs (CSV + figures) for review.
- Documented model limitations and practical takeaways (volatility regimes, exception clustering, tail risk).
