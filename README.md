# ERG Operating Cash Review

Interactive operating cash flow review of ERG S.A. for 2023–2025.

The project explains how a manufacturing company turns sales, inventory and supplier financing into operating cash flow.

Live project:  
https://mbimarban.github.io/erg-operating-cash-review/

## Purpose

This is not a traditional financial dashboard.

The goal is to translate financial statements into a simple business story:

- where cash was trapped,
- how cash was released,
- why EBITDA and operating cash flow can move differently,
- whether the improvement in cash flow is sustainable.

The analysis is designed for business owners, managers and non-financial decision makers.

## Key idea

In 2025 ERG improved operating cash flow, but the improvement was driven mainly by working capital release — especially inventory reduction and supplier financing — not by a structural improvement in profitability.

## What the project includes

- interactive slide-based HTML report,
- CFO-first business narrative,
- EBITDA vs operating cash flow comparison,
- working capital analysis,
- Cash Flow Sales logic,
- CCC / DSO / DIO / DPO explanation,
- simple what-if simulator,
- margin and operational risk review.

## Repository structure

```text
/
├── index.html
├── data/
│   ├── erg_sa_data.json
│   ├── erg_sa_storytelling.json
│   └── erg_sa_visualization_config.json
└── financial-model/
    └── ERG_SA_CFO_Analysis_2023_2025.xlsx
