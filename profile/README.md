# Earnings Feed

**Real-time SEC filings API for developers and financial professionals.**

Every 10-K, 10-Q, 8-K, and Form 4 the moment it hits EDGAR. Professional-grade data, free to start.

## What We Offer

- **SEC Filings Feed** — Annual reports, quarterly reports, 8-Ks, and more as they're accepted
- **Insider Transactions** — Form 3, 4, and 5 data with parsed transaction details
- **Institutional Holdings** — 13F filings from hedge funds and asset managers
- **Company Profiles** — CIK lookup, ticker mapping, and company metadata

## Quick Start

```bash
curl -H "Authorization: Bearer YOUR_API_KEY" \
  "https://earningsfeed.com/api/v1/filings?limit=10"
```

## Tutorials

Step-by-step guides with Python and JavaScript examples:

- [Track Insider Trading with the Earnings Feed API](https://gist.github.com/nrempel/a563290f6ed75670043776f6f8d9bbb5) — Build alerts for Form 4 insider purchases
- [Monitor Hedge Fund Holdings with 13F Data](https://gist.github.com/nrempel/200d7e21ebee7fdd64b50002c10d1006) — Track institutional investor portfolios

## Resources

| Resource | Link |
|----------|------|
| Website | [earningsfeed.com](https://earningsfeed.com) |
| API Documentation | [earningsfeed.com/api/docs](https://earningsfeed.com/api/docs) |
| OpenAPI Spec | [earningsfeed.com/api/v1/openapi.json](https://earningsfeed.com/api/v1/openapi.json) |

## Free Tier

Get started with 15 requests/minute — no credit card required.

---

Questions? Reach us at [contact@earningsfeed.com](mailto:contact@earningsfeed.com)
