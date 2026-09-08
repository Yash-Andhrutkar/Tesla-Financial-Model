# Tesla Financial Model & Equity Valuation

An independent integrated financial modeling and equity valuation project on **Tesla, Inc. (NASDAQ: TSLA)**, covering FY2021A–FY2025A historical performance and FY2026E–FY2030E forecasts.

## Project Overview

This project builds a driver-based three-statement financial model for Tesla and evaluates the company's equity value through multiple valuation frameworks.

The model includes:

- Integrated Income Statement, Balance Sheet and Cash Flow Statement
- Automotive, Energy and Services segment forecasts
- Driver-based revenue and cost assumptions
- FCFF Discounted Cash Flow valuation
- CAPM and WACC analysis
- Bear / Base / Bull scenario analysis
- Trading comparable-company valuation
- WACC × terminal-growth sensitivity analysis
- Reverse DCF / market-implied expectations analysis
- Automated model integrity checks

## Key Base-Case Outputs

| Metric | Base Case |
|---|---:|
| FY2030E Revenue | $161.4bn |
| FY2030E EBITDA | $29.0bn |
| FY2030E EBIT Margin | 12.7% |
| FY2030E FCFF | $10.8bn |
| WACC | 12.38% |
| Terminal Growth Rate | 3.8% |
| Enterprise Value | $93.7bn |
| Equity Value | $128.6bn |
| DCF Implied Value / Share | **$32.57** |
| Market Price (3 Sep 2026) | **$376.37** |

## Scenario Analysis

| Scenario | FY2030E Revenue | EBIT Margin | FCFF | DCF / Share |
|---|---:|---:|---:|---:|
| Bear | $113.1bn | 6.0% | $2.4bn | $13.12 |
| **Base** | **$161.4bn** | **12.7%** | **$10.8bn** | **$32.57** |
| Bull | $206.5bn | 17.0% | $20.1bn | $53.45 |

## Valuation Framework

The Base Case DCF produces an implied equity value of **$32.57 per share**, compared with Tesla's market price of **$376.37** on the valuation date.

Rather than forcing the fundamental DCF toward the observed market price, the project uses a **Reverse DCF** to examine the operating expectations embedded in Tesla's market valuation.

The analysis indicates a market-implied enterprise value approximately **15.5×** the fundamental DCF enterprise value. On the modeled economics, justifying the observed market price would require approximately **$170.0bn of FY2030E FCFF**, or roughly **15.7× the Base Case**.

The model does not separately forecast potential cash-flow streams from autonomy, AI software or robotics.

## Valuation Methods

**Discounted Cash Flow**
- FCFF methodology
- CAPM-derived cost of equity
- WACC: 12.38%
- Terminal growth: 3.8%
- WACC × terminal-growth sensitivity analysis

**Trading Comparables**
- EV / Revenue
- EV / EBITDA
- P / E
- Peer-derived valuation range

**Scenario Analysis**
- Bear, Base and Bull operating cases
- 11 operating drivers vary by scenario

**Reverse DCF**
- Evaluates operating expectations implied by the market valuation

## Files

### `Tesla_Financial_Model.xlsx`

Full integrated Excel model containing historical financials, operating assumptions, three-statement forecasts, supporting schedules, ratio analysis, trading comparables, scenario analysis, DCF valuation, reverse DCF and model checks.

### `Tesla_Equity_Valuation_Summary.pdf`

One-page executive valuation summary presenting the major operating forecasts, valuation outputs, scenario analysis and market-implied expectations.

## Data Sources

Historical and market data are sourced from Tesla company filings and Investor Relations, U.S. Treasury data, NYU Stern / Aswath Damodaran, Yahoo Finance and additional sources documented within the workbook.

## Disclaimer

This project was created independently for educational and portfolio purposes. It is **not investment research, an investment recommendation or investment advice**.
