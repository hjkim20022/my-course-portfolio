# Financial Intelligence | Power BI Financial Analysis

**Portfolio project by HeeJung Kim** · Power BI · DAX · Financial Reporting · KPI Analysis

> **Project status:** The eight-page Power BI report exists. The public GitHub presentation is a **design concept and project case study**, not a completed redesign of the `.pbix` file. The original public Power BI link is unavailable, so this GitHub project is accessible without a Power BI account.

**[Explore the eight-page design prototype](./index.html)** · [Power BI design checklist](./IMPLEMENTATION_CHECKLIST.md)  
**[Review the redesign and validation checklist](./REDESIGN_AND_VALIDATION.md)**

## Project at a glance

The Financial Report explores revenue, cost of goods sold, profitability, financial statements, working capital, and financial ratios. It demonstrates KPI design, DAX measures, financial analysis, and report structure.

### Verified visual snapshot

The **original Power BI Service dashboard screenshot** displayed these rounded headline amounts:

| KPI | Shown on original dashboard |
|---|---:|
| Revenue | 18.90K |
| COGS | 7.84K |
| Gross profit | 11.06K |
| Net profit | 2.55K |

*The screenshot did not independently establish currency or reporting-period context. These values describe the original visual; they should not be interpreted as audited figures.*

## Eight-page report inventory

| Original report page | Intended business question | Redesign approach |
|---|---|---|
| dashboard | What is overall financial performance? | Executive KPI hierarchy and readable trend/comparison charts |
| IS | How do revenue and expenses contribute to profit? | Clean income statement, subtotals, clear formatting |
| BS | What is the balance sheet position? | Assets, liabilities and equity hierarchy |
| CF | Where does cash come from and go? | Operating, investing and financing sections |
| WC | What is the liquidity position? | Working capital and current liability view |
| Ratios | What do the detailed ratios show? | Clearly labeled measures with appropriate units |
| Ratios 1 | What is overall financial health? | Liquidity, profitability and solvency groups |
| financials | What drives revenue and profit? | Trends, slicers, and performance drivers |

## Redesign priorities

1. **Dashboard:** Retain four main KPI concepts, remove visually competing elements, improve whitespace and date-axis readability.
2. **Ratios 1:** Replace the three multi-row cards with a structured liquidity/profitability/solvency view.
3. **Financial calculations:** Validate Operating Margin Ratio (originally displayed in scientific notation) and format decimal margins as percentages *after verifying DAX*.
4. **Remaining pages:** Apply consistent title, navigation, spacing, and percentage/currency/ratio formats.
5. **Evidence:** Replace design concepts with actual polished Power BI Desktop screenshots when each page is verified.

## What employers can review now

- A public **static design prototype** with eight navigable views in [`index.html`](./index.html)
- Existing project structure, analytical objectives and original dashboard KPI snapshot
- A detailed [Power BI implementation and validation plan](./REDESIGN_AND_VALIDATION.md)

**Transparency:** The prototype is not a live Power BI dashboard; its page layouts are proposed designs. Ratios and trend data that have not been verified are intentionally left blank. The underlying `.pbix` and data model were not uploaded publicly.

## Portfolio links

- [More projects](https://github.com/hjkim20022)
- [Enterprise Retail Analytics Platform](https://github.com/hjkim20022/enterprise-retail-analytics-platform)
- [AR Collection Portfolio](https://github.com/hjkim20022/HeeJung_Kim_AR_Collection_Portfolio)

## GitHub Pages

The repository owner can enable **Settings → Pages → Deploy from a branch → main → /(root)**. When deployment succeeds, the public design prototype is expected at:

`https://hjkim20022.github.io/my-course-portfolio/power-bi-financial-analysis/`

Until Pages is enabled and the site is tested, use this GitHub project README URL for job applications:

`https://github.com/hjkim20022/my-course-portfolio/tree/main/power-bi-financial-analysis`

**Privacy:** Please publish only report screenshots and datasets that you have permission to share. Do not publish confidential financial records or employer data.
