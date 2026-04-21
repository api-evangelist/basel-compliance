# Basel Compliance

Basel Compliance covers the regulatory frameworks and technical standards issued by the Basel Committee on Banking Supervision (BCBS) at the Bank for International Settlements. The Basel Accords establish minimum capital adequacy, leverage, liquidity, and risk management requirements for internationally active banks. RegTech platforms provide APIs to automate Basel compliance calculations, reporting (COREP, FINREP), and supervisory submissions.

## Overview

The Basel framework is organized around three pillars:

- **Pillar 1** — Minimum capital requirements for credit, market, and operational risk
- **Pillar 2** — Supervisory review process (ICAAP/SREP)
- **Pillar 3** — Market discipline through public disclosure

## Key Standards

| Standard | Description |
|---|---|
| CET1 Capital Ratio | Minimum 4.5% of risk-weighted assets |
| Tier 1 Capital Ratio | Minimum 6% of risk-weighted assets |
| Total Capital Ratio | Minimum 8% of risk-weighted assets |
| LCR | 30-day liquidity coverage ratio >= 100% |
| NSFR | Net Stable Funding Ratio >= 100% |
| Leverage Ratio | Minimum 3% of total exposures |
| Output Floor | IRB RWA >= 72.5% of standardized approach |

## Data Providers

- [BIS Statistics](https://stats.bis.org/) — Global banking statistical data
- [EBA Data](https://www.eba.europa.eu/risk-analysis-and-data) — EU supervisory reporting datasets
- [Federal Reserve Statistical Release](https://www.federalreserve.gov/releases/) — US bank capital data
- [S&P Global Market Intelligence](https://www.spglobal.com/marketintelligence/en/) — Commercial bank data
- [Moody's Analytics](https://www.moodysanalytics.com/) — Risk and compliance solutions

## Resources

- [Basel Committee on Banking Supervision](https://www.bis.org/bcbs/)
- [Basel III Framework](https://www.bis.org/bcbs/basel3.htm)
- [European Banking Authority](https://www.eba.europa.eu/)
- [COREP/FINREP Reporting](https://www.eba.europa.eu/regulation-and-policy/supervisory-reporting)
- [Federal Reserve - Basel Implementation](https://www.federalreserve.gov/supervisionreg/Basel.htm)

## Vocabulary

See [vocabulary/basel-compliance-vocabulary.yaml](vocabulary/basel-compliance-vocabulary.yaml) for key terms and definitions.

## JSON-LD Context

See [json-ld/basel-compliance-context.jsonld](json-ld/basel-compliance-context.jsonld) for linked data context mapping Basel compliance concepts.

## Examples

See [examples/capital-ratio-report-example.json](examples/capital-ratio-report-example.json) for a sample Basel capital ratio report structure.

## Maintainers

- Kin Lane (kin@apievangelist.com)
