
# India HDI Forecasting & Regional Inequality Analysis

A data science project analysing 32 years of subnational Human Development Index (HDI) data across 36 Indian states and Union Territories (1990–2022) to forecast future development trends and measure regional inequality.

---

## What this project does

- **Forecasts** India's national HDI through 2030 using ARIMA, SARIMA, and Holt-Winters models — selected via AIC and evaluated on MAE, RMSE, and MAPE
- **Measures inequality** across states using Gini coefficient, Lorenz curve, and beta/sigma-convergence analysis
- **Quantifies COVID-19 impact** via a counterfactual model estimating cumulative HDI loss (2020–2022) per state
- **Classifies states** into 2030 policy tiers (high / medium / at-risk) to identify regions needing targeted intervention

---

## Dataset

**GDL Subnational HDI Data** — Global Data Lab  
36 Indian states/UTs · Annual HDI values · 1990–2022  
Source: https://globaldatalab.org/shdi/

---

## Tech stack

| Area | Tools |
|------|-------|
| Data wrangling | pandas, NumPy |
| Time-series modelling | statsmodels (ARIMA, SARIMA, Holt-Winters) |
| Model evaluation | scikit-learn (MAE, RMSE, MAPE) |
| Statistical tests | ADF test, AIC grid search, ACF/PACF |
| Visualisation | matplotlib, seaborn |

---

## Key findings

- India's national HDI grew steadily from ~0.43 (1990) to ~0.64 (2022)
- Inter-state inequality (Gini) declined over the period — evidence of sigma-convergence
- COVID-19 caused a measurable HDI setback in 2020–2021, with recovery visible by 2022
- Several states in central and eastern India remain persistently below the national average

---

## How to run

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
jupyter notebook India_HDI_Forecasting_Inequality.ipynb
```

---

## Author

[FIDA FATHIMA K]  [fathimakfida@gmail.com]
