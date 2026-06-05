# Dax Virani - Stock/Stack Analysis

Objective
- Provide time-series analysis and basic forecasting examples derived from `stack_analysis.py` for financial or stacked time-series data.

Steps performed
- Load time-series data and set proper indices
- Decompose series, visualize seasonality and trend
- Fit simple forecasting models (e.g., ARIMA) and evaluate residuals

Tools / Libraries
- pandas, numpy, matplotlib, statsmodels, scikit-learn

Outcome (brief)
- Notebook produces decomposition plots, benchmark forecasts, and evaluation metrics useful as a starting point for further modeling.

How to run

```bash
pip install -r requirements.txt
jupyter lab
jupyter nbconvert --to notebook --execute "Dax Virani - stack_analysis.ipynb" --inplace
```

Notes
- Forecasting cells may be compute-heavy; adjust parameters for faster iterations.
- Author: Dax Virani
