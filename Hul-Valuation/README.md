## Hindustan Unilever Limited — DCF Valuation

### What This Is

A full DCF valuation of Hindustan Unilever Limited built on an integrated three-statement financial model (FY2026–FY2030). The analysis derives an implied equity value per share and compares it against the current market price to assess whether HUL is overvalued, fairly valued, or undervalued at current levels.

### Key Numbers

| Metric | Value |
| --- | --- |
| _[Fill: Implied Share Price]_ | _[Fill: INR X]_ |
| _[Fill: Current Market Price]_ | _[Fill: INR X]_ |
| _[Fill: Upside / Downside]_ | _[Fill: X%]_ |
| Revenue CAGR (FY2026–FY2030) | _[Fill: X%]_ |
| WACC | _[Fill: X%]_ |
| Terminal Growth Rate | _[Fill: X%]_ |
| Cost of Equity (CAPM) | _[Fill: X%]_ |
| Hamada-Adjusted Beta | _[Fill: X.XX]_ |

> Replace all `[Fill: ...]` values with your actual model outputs.

### Model Output

![DCF Summary](screenshots/dcf-summary.png)
![Sensitivity — WACC vs Terminal Growth Rate](screenshots/sensitivity-wacc-tgr.png)
![Three-Statement Model — Income Statement](screenshots/income-statement-forecast.png)

> Screenshot your: (1) DCF valuation output table, (2) WACC–TGR sensitivity grid, (3) Income Statement forecast. Save in `screenshots/`.

### How It Was Built

Built an integrated Income Statement, Balance Sheet, and Cash Flow Statement with 5-year forecasts (FY2026–FY2030). Revenue was projected using segment-level drivers across HPC and Foods & Refreshment divisions. Cost of Equity derived via CAPM using the Hamada equation to unlever and re-lever betas from a peer set of 5 comparable FMCG companies (Dabur, Marico, Godrej Consumer, Nestlé India, Tata Consumer). Beta data sourced from TopStockResearch using both 2-Year Weekly and 5-Year Monthly regression windows. Terminal value calculated using both Gordon Growth Model and Exit Multiple methods. Size Premium and Asset-Based Risk Premium set at 0.00% based on Kroll/Duff & Phelps CRSP Deciles and Damodaran's framework.

### Files in This Project

| File | What It Contains |
| --- | --- |
| [model/hul-three-statement-model.xlsx](model/hul-three-statement-model.xlsx) | Integrated 3-statement model with DCF, WACC, and sensitivity |
| [model/hul-comparable-beta-analysis.xlsx](model/hul-comparable-beta-analysis.xlsx) | Comparable company beta analysis (Hamada equation) |
| [report/hul-valuation-report.pdf](report/hul-valuation-report.pdf) | Written valuation report _(optional — include if you have one)_ |

### Data Sources

HUL Annual Reports (FY2020–FY2025), BSE/NSE filings, TopStockResearch (beta data), Screener.in, Kroll/Duff & Phelps (risk premia), Damodaran (country risk premium, ERP).

---

*This analysis is for educational and portfolio purposes and does not constitute investment advice.*

---

## Skills Demonstrated

- Three-statement financial modelling (Income Statement, Balance Sheet, Cash Flow Statement)
- DCF valuation (FCFF-based Enterprise Value to Equity Value bridge)
- WACC construction using CAPM
- Comparable company beta analysis using the Hamada equation
- Sensitivity and scenario analysis
- Ind AS / IFRS 16 treatment (ROU assets, lease liabilities)

---

## Contact

- **LinkedIn:** Suyash Mandhana[www.linkedin.com/in/suyashmandhana]
- **Email:** suyashymandhana@gmail.com
