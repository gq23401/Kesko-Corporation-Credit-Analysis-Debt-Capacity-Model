# Kesko Corporation — Credit Analysis & Debt Capacity Model

A comprehensive leveraged finance credit analysis for Kesko Corporation (KESKOB.HE), covering EBITDA projections, leverage ratios, interest coverage, debt structure, covenant analysis, maximum debt capacity, and indicative pricing — built following CFI Financial Modeling Best Practices.

**Credit Assessment: INVESTMENT GRADE — STRONG (Implied BBB+ / Baa1)**

**Incremental Debt Capacity: EUR 845M (conservative) to EUR 1,981M (aggressive)**

**Prepared by: GBENGA QUADRI CFA CANDIDATE**

---

## Credit Summary

| Metric | FY2025A | FY2026E | FY2027E | FY2028E | IG Threshold |
|--------|---------|---------|---------|---------|-------------|
| EBITDA | 1,135 | 1,198 | 1,267 | 1,340 | — |
| Net Debt / EBITDA (excl. leases) | **0.8x** | 0.7x | 0.5x | 0.4x | < 2.5x |
| Total Debt / EBITDA (incl. leases) | **3.1x** | 2.9x | 2.7x | 2.5x | < 4.0x |
| EBITDA / Interest | **9.9x** | 10.9x | 12.1x | 13.4x | > 4.0x |
| Free Cash Flow | 529 | 566 | 636 | 709 | — |

Kesko operates well within investment-grade credit parameters across all metrics. The company is significantly under-levered relative to European retail peers (median 1.8x ND/EBITDA) and has EUR 888M of available liquidity (EUR 488M cash + EUR 400M undrawn RCF).

---

## Debt Structure (FY2025)

| Layer | Instrument | Amount (EUR M) | Rate | Maturity |
|-------|-----------|---------------|------|----------|
| **Senior Secured** | NIB Sustainability-Linked Loan | 150 | 3.25% | 2031 |
| | RCF (undrawn) | 0 (400 committed) | Euribor+85bps | 2028 |
| **Senior Unsecured** | Green Notes (Sep 2024) | 300 | 3.50% | Feb 2030 |
| | Term Loan A | 150 | Euribor+110bps | 2026 |
| | Term Loan B | 150 | Euribor+120bps | 2027 |
| | Term Loan C | 200 | Euribor+130bps | 2027 |
| | Bond (legacy) | 300 | 2.875% | 2026 |
| | Other Bank Debt | 95 | Various | Various |
| **IFRS 16 Leases** | Store/warehouse leases | 2,151 | ~3.0% implicit | Various |
| **Total Financial Debt** | | **1,345** | | |
| **Total incl. Leases** | | **3,496** | | |

### Maturity Wall

| Year | Amount (EUR M) | Risk Level |
|------|---------------|------------|
| **2026** | **450** | **HIGH — Refinancing needed immediately** |
| **2027** | **350** | **HIGH — EUR 350M maturity wall** |
| 2028 | 0 | Low |
| 2029 | 0 | Low |
| 2030 | 300 | Moderate (Green Notes) |
| 2031+ | 245 | Low |

**Critical finding:** EUR 800M matures in 2026-2027. At current Euribor (2.65%) plus estimated 95bps spread, refinancing at 3.60% would cost EUR 28.8M annually — only EUR 6.4M more than existing rates. Manageable, but needs to be initiated.

---

## Maximum Debt Capacity

| Scenario | Target ND/EBITDA | Max Net Debt | Current | **Incremental Capacity** |
|----------|-----------------|-------------|---------|------------------------|
| Conservative (A- rating) | 1.5x | EUR 1,703M | EUR 857M | **EUR 846M** |
| **Base Case (BBB)** | **2.0x** | **EUR 2,270M** | **EUR 857M** | **EUR 1,413M** |
| Aggressive (BBB- floor) | 2.5x | EUR 2,838M | EUR 857M | **EUR 1,981M** |

At the base case (maintain BBB), Kesko can raise approximately EUR 1.4B in incremental debt before approaching rating downgrade thresholds. This is sufficient to fund the hypothetical Tokmanni acquisition (EUR 718M new debt per M&A model) with capacity to spare.

---

## Covenant Analysis

| Covenant Test | Limit | FY2025 Actual | Headroom | Status |
|--------------|-------|--------------|----------|--------|
| Net Debt / EBITDA (excl. leases) | < 3.5x | 0.8x | **2.7x** | PASS |
| Total Debt / EBITDA (incl. leases) | < 5.0x | 3.1x | **1.9x** | PASS |
| Interest Coverage (EBITDA/Int) | > 3.0x | 9.9x | **6.9x** | PASS |
| Minimum EBITDA | > EUR 800M | EUR 1,135M | **EUR 335M** | PASS |
| Maximum CapEx | < EUR 600M | EUR 450M | **EUR 150M** | PASS |
| Dividend Payout Ratio | < 75% | 55% | **20%** | PASS |

All covenants pass with substantial headroom. The 2.7x headroom on ND/EBITDA is the key metric — Kesko would need EBITDA to fall below EUR 245M (a 78% decline) before breaching this covenant at current debt levels.

---

## Interest Coverage Deep Dive

| Ratio | FY2023A | FY2024A | FY2025A | FY2026E | FY2027E | FY2028E | Min |
|-------|---------|---------|---------|---------|---------|---------|-----|
| EBITDA / Total Interest | 10.0x | 10.0x | 9.9x | 10.9x | 12.1x | 13.4x | > 4.0x |
| EBITDA / Financial Interest | 21.0x | 20.8x | 20.6x | 25.0x | 30.2x | 37.2x | > 6.0x |
| EBIT / Total Interest | 5.9x | 5.9x | 5.7x | 6.4x | 7.3x | 8.3x | > 2.5x |
| FCF / Total Debt Service | 5.1x | 4.9x | 2.0x | 2.2x | 1.4x | 3.5x | > 1.0x |

**Watch item:** FCF / Total Debt Service dips to 1.4x in 2027E due to the EUR 350M maturity wall. This is still above the 1.0x minimum but signals that Kesko should refinance early rather than rely on cash flow to repay at maturity.

---

## Indicative Pricing Grid (bps over Euribor / Mid-Swap)

| ND/EBITDA | Senior Secured 5yr | Senior Unsecured 5yr | Senior Unsecured 7yr | Senior Unsecured 10yr | Implied Rating |
|-----------|-------------------|---------------------|---------------------|----------------------|---------------|
| 0.5x | 55 | 80 | 95 | 115 | A / A2 |
| **1.0x** | **65** | **95** | **110** | **130** | **A- / A3** |
| 1.5x | 80 | 115 | 135 | 155 | BBB+ / Baa1 |
| 2.0x | 100 | 140 | 165 | 190 | BBB / Baa2 |
| 2.5x | 130 | 175 | 205 | 240 | BBB- / Baa3 |
| 3.0x | 175 | 235 | 275 | 320 | BB+ / Ba1 |
| 3.5x | 240 | 320 | 380 | 440 | BB / Ba2 |
| 4.0x | 325 | 430 | 500 | 575 | BB- / Ba3 |

*Highlighted row = Kesko's current approximate leverage. Spreads indicative for EUR-denominated Nordic retail issuers as of March 2026.*

---

## Model Structure (8 Sheets)

| Sheet | Tab Color | Purpose |
|-------|-----------|---------|
| Cover | Navy | Credit assessment summary, key metrics, model architecture |
| EBITDA_Analysis | Blue | 3yr historical + 3yr projected segment revenue, EBITDA build, FCF |
| Leverage_Ratios | Orange | ND/EBITDA, Total Debt/EBITDA with industry benchmarks |
| Interest_Coverage | Green | EBITDA/Interest, EBIT/Interest, FCF/Debt Service |
| Debt_Structure | Purple | Instrument-level breakdown, maturity wall, available liquidity |
| Covenants | Red | 6 maintenance tests with headroom analysis, pass/fail status |
| Maximum_Debt | Green | Incremental capacity at 3 scenarios, EBITDA sensitivity matrix |
| Pricing_Grid | Gold | 8-tier spread grid by leverage, refinancing cost estimate |

---

## CFI Methodology Compliance

| Guideline | Implementation |
|-----------|----------------|
| Blue font for inputs | All financial data, assumptions, pricing inputs |
| Black font for formulas | All calculated ratios, coverage metrics, debt capacity |
| Green font for cross-sheet links | All inter-sheet references (EBITDA, leverage, coverage) |
| Yellow fill for key assumptions | Target leverage, covenant limits, refinancing spread |
| No currency symbols | Global marker: "All figures in EUR M unless stated" |
| Brackets for negatives, dashes for zeroes | Custom number format throughout |
| Consistent columns | Same periods (2023A-2028E) across all sheets |
| Freeze panes | Frozen at C5 on all data sheets |
| Zero formula errors | 193 formulas, 0 errors verified via LibreOffice |

---

## Data Sources

| Source | Usage |
|--------|-------|
| Kesko FY2025 Financial Statements (5 Feb 2026) | EBITDA, debt balances, cash, interest expense |
| Kesko Investor Relations — Financial Position page | Debt maturity profile, bond terms, NIB loan |
| Kesko Q3 2025 Interim Report | YTD financials, updated guidance |
| Kesko Green Notes listing prospectus (Sep 2024) | EUR 300M bond terms, coupon, maturity |
| Yahoo Finance (KESKOB.HE) | Share price, market cap |
| European Central Bank | Euribor rates |
| Peer company annual reports | Industry leverage benchmarks |
| CFI Financial Modeling Best Practices (2018) | Model structure and formatting |

---

## Related Projects

- [Kesko Financial Modeling Portfolio](https://github.com/gq23401/kesko-financial-modeling) — Consolidated 6-model suite
- [Kesko Three-Statement Model](https://github.com/gq23401/kesko-financial-model) — Integrated IS / BS / CFS
- [Kesko DCF Valuation](https://github.com/gq23401/Kesko-DCF-Valuation-Model) — Discounted Cash Flow
- [Kesko-Tokmanni M&A](https://github.com/gq23401/kesko-tokmanni-ma-model) — Accretion/Dilution analysis

---

## About

This credit analysis was built as part of my leveraged finance and financial modeling portfolio, demonstrating debt capacity assessment methodology applied to a Nordic investment-grade retail issuer with real debt instruments and maturity profiles.

*Model structure developed with AI assistance; all assumptions, data sourcing, covenant structuring, pricing estimates, and analytical conclusions are my own work.*

**GBENGA QUADRI CFA CANDIDATE**

**GitHub:** [@gq23401](https://github.com/gq23401) | **Location:** Helsinki, Finland

---

## License

This project is available for educational and portfolio demonstration purposes. Financial data sourced from publicly available company reports and financial data platforms. This is not investment advice or a credit recommendation.
