# Costco Wholesale Corp (COST) - Equity Research & 3-Stage FCFF Valuation

## Executive Summary
This project provides a comprehensive financial valuation of **Costco Wholesale Corp (COST)**. Using a detailed 3-stage Discounted Free Cash Flow to Firm (FCFF) model, the analysis identifies an **intrinsic undervaluation of 28.1%** compared to the market price (as of late 2025).



## Key Financial Metrics
* **Intrinsic Value:** Calculated using a 3-stage transition growth model.
* **Adjusted WACC:** **6.07%** (accounting for operating leases capitalization).
* **Bottom-up Beta:** Derived from industry peer samples to reflect pure-play risk.
* **Terminal Growth Rate ($g$):** **5.07%** (aligned with stable industry expectations).

## Methodology
### 1. Financial Modeling
* **3-Stage FCFF:** Modeled high-growth, transition, and stable phases to capture Costco's membership-driven business model.
* **Operating Leases:** Adjusted EBIT and Debt by capitalizing operating leases to reflect the true leverage of the firm.
* **Sensitivity Analysis:** Performed a stress test on WACC vs. Terminal Growth to evaluate valuation robustness.

### 2. Quantitative Analysis (Trend & Forecasting)
* **Geometric Brownian Motion (GBM):** Implemented a statistical price forecast.
    * **Annual Drift ($\mu$):** 18.5%
    * **Annual Volatility ($\sigma$):** 22.9%
* This approach compares the fundamental DCF value with a statistical probability distribution of future prices.

## Repository Structure
* `/models`: Excel DCF Model with detailed WACC and Tax adjustments.
* `/reports`: Final Equity Research Report (PDF).
* `/data`: Raw data exports from Bloomberg/Yahoo Finance.

---
*Project conducted as part of FINA 410 at John Molson School of Business (JMSB).*
