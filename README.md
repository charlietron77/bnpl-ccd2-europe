# bnpl-ccd2-europe
CCD II's competitive impact on BNPL markets in Germany and France
# BNPL in Europe: Empirical Analysis

Replication code and datasets for the BBA Final Project:
**"From Regulatory Arbitrage to Regulated Credit: How CCD II Will Reshape BNPL's Competitive Dynamics in Europe, with Evidence from Germany and France"**

IE University — Topics in Fintech | Supervisor: Pablo Soler Bach | April 2026

---

## How to run

1. Open `notebooks/BNPL_Europe_Empirical_Analysis.ipynb` in Google Colab
2. Uncomment the pip install line in Cell 1 and run it
3. Runtime → Run all
4. All 6 figures save automatically to the session

---

## Datasets

| File | Content | Source |
|------|---------|--------|
| dataset1_ecb_card_share.csv | Card payments as % of non-cash transactions, 9 euro area countries, 2019–2025H1 | ECB Statistical Annexes pis2019–pis2025H1 |
| dataset2_bnpl_adoption.csv | BNPL as % of e-commerce value, 14 European markets, 2024 | Worldpay GPR 2025, p.86 |
| dataset3_worldbank_macro.csv | GDP per capita, internet penetration, domestic credit/GDP, unemployment, 5 countries, 2023 | World Bank WDI |
| dataset3_worldbank_macro_sources.csv | Variable definitions and WDI indicator codes | — |
| dataset4_klarna_revenue.csv | Net operating income by market, H1 2024 vs H1 2025 | Klarna Holding AB (2025b), p.18 |
| dataset5_scale_comparison.csv | Klarna global GMV vs. euro area card payments, FY2024 | Klarna AR (2025a); ECB (2025a; 2025b) |

---

## Data sources

- **ECB Statistical Annexes** pis2019–pis2025H1 — [ecb.europa.eu](https://www.ecb.europa.eu/stats/payment_statistics/en.html)
- **Worldpay Global Payments Report 2025** p.86 — [worldpay.com](https://www.worldpay.com/global-payments-report)
- **Klarna Annual Report FY2024** — Klarna Holding AB (2025a), org. nr. 556676-2356
- **Klarna Interim Report H1 2025** — Klarna Holding AB (2025b), org. nr. 556676-2356
- **World Bank WDI** — [data.worldbank.org](https://data.worldbank.org)

---

## Notes

All correlations (n=5–7) are descriptive only — sample size is insufficient for formal econometric inference. See Section 6.2 of the paper for full methodological discussion.
