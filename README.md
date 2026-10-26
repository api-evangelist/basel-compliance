# Basel Compliance

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
