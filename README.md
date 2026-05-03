# Boeing (BA) — Three Statement Financial Model
### FY2021–FY2030E | Work in Progress

> **Disclaimer:** This model is built for learning purposes only. Figures, assumptions, and projections are not intended for investment analysis or decision-making.
DCF outputs are negative across all scenarios due to Boeing's projected negative EBITDA through FY2030, reflecting the model's conservative working capital assumptions. This is a known limitation and is discussed within the model.
---

## Overview

A dynamic, driver-based three statement financial model built on Boeing's publicly reported financials (FY2021–FY2025), with forward projections extended to FY2030. The goal of this project is to develop experience building an integrated model from scratch — understanding how assumptions and historical data flow through the income statement, balance sheet, and cash flow statement.

---

## What's Inside

| Sheet | Description |
|---|---|
| **Cover** | Title page with model metadata |
| **Assumptions** | All forecast drivers in one place — growth rates, margins, working capital days, capex, tax rates |
| **3 Statement Model** | Fully linked IS, BS, and CFS with historical actuals and projections |
| **DCF** | WACC-based valuation with terminal value, equity bridge, sensitivity tables, and three scenario toggle |

---

## Key Concepts Practised

- **Three statement integration** — income statement, balance sheet, and cash flow statement linked dynamically
- **Driver-based forecasting** — assumptions (e.g. revenue growth %, margin %, DSO/DIO/DPO) feed directly into projections
- **Working capital modelling** — days sales outstanding, days inventory outstanding, days payable outstanding
- **Capex & depreciation scheduling** — capex as % of revenue and PP&E
- **Financial ratios** — EBIT margin, gross margin, net income margin, EPS (basic & diluted), interest coverage, net debt/EBITDA
- **Per share metrics** — basic and diluted EPS across the forecast period
- **DCF valuation** — UFCF build, WACC, terminal value (exit multiple and perpetuity growth methods)
- **Scenario analysis** — Grey Sky / Base Case / Blue Sky toggle driving DIO and revenue growth assumptions simultaneously

---

## Model Scope

| | Detail |
|---|---|
| **Company** | The Boeing Company (NYSE: BA) |
| **Historical period** | FY2021 – FY2025 |
| **Forecast period** | FY2026 – FY2030E |
| **Currency** | USD millions (unless stated) |
| **Data source** | Boeing public filings (10-K) |

---

## Work in Progress

This is an ongoing project. Areas currently being developed:

- [x] DCF valuation (WACC, terminal value, implied share price)
- [x] Sensitivity analysis on key assumptions
- [x] Scenario toggles (base / bull / bear)
- [ ] Refinement of forecast logic for post-2025 projections

---

## Skills Demonstrated

`Financial Modelling` `3-Statement Model` `Driver-Based Forecasting` `DCF Valuation` `Excel` `Financial Ratios` `Working Capital Analysis` `EPS Modelling`

---

## Notes

- Assumptions are directional averages and averages of historical actuals — they do not reflect analyst consensus or real-world forecasts
- The model is intentionally kept simple to focus on structural integrity and formula logic
- Balance sheet check (Assets = Liabilities + Equity) is included and passes for all historical periods ✓
