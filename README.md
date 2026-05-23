# service-properties-trust

Profile for **Service Properties Trust (NASDAQ: SVC)** in the API Evangelist
network. Fortune 1000 (rank 914). Externally managed by The RMR Group.

## Snapshot

- **Sector:** Real estate investment trust (REIT) — hospitality + net lease retail
- **Portfolio (as of March 31, 2026):** 761 service-focused retail net lease
  properties (>13.6M sq ft) and 93 hotels (>21,000 guest rooms)
- **Invested capital:** ~$9.9 billion
- **Manager:** The RMR Group (NASDAQ: RMR)
- **Homepage:** <https://www.svcreit.com>

## API surface

**None.** SVC is a publicly traded REIT and does not operate a developer
program. There are no public APIs, OpenAPI specs, SDKs, CLIs, webhooks, or
RSS feeds of operational data. Investor-facing endpoints are limited to:

- SEC filings (quarterly + annual reports)
- Press releases (archive back to 2002)
- Email alerts (filings / press / events / end-of-day stock quotes)
- Events & presentations with webcasts

See [`apis.yml`](./apis.yml) for the structured common-properties index.

## Artifacts

This repo intentionally contains **no** `openapi/`, `capabilities/`,
`json-schema/`, `plans/`, `rate-limits/`, or `finops/` directories. The
API Evangelist pipeline does not create empty/placeholder specs.

## Re-run trigger

Re-run the pipeline if SVC or RMR Group later publishes:
- A developer portal or OpenAPI spec
- A property / hotel data feed for partners
- A booking, tenant, or rent-roll API

## Contact

- Investor Relations: `IR@svcreit.com` — 617-796-8232
- Media Relations: `media@svcreit.com`
