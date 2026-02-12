# Project 01 — VaR / ES Engine + Backtesting (Python)

## Objective
Compute daily VaR/ES and validate using standard backtesting (Kupiec, Christoffersen).

## Models
- Historical VaR/ES
- Parametric (Normal) VaR/ES
- EWMA volatility VaR/ES

## Validation
- VaR exceptions
- Kupiec POF
- Christoffersen independence

## How to run

```bash```
pip install -r requirements.txt

## Results (sample)

### Realized return vs VaR (99%)
![Realized return vs VaR](outputs/var_vs_return.png)

### VaR exceptions (EWMA)
![VaR exceptions](outputs/exceptions_ewma.png)

Backtest summary: [`backtest_summary.csv`](outputs/backtest_summary.csv)
