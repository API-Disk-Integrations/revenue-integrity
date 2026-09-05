# Revenue Integrity API TypeScript SDK

Reconcile contracts, usage, invoices, payments and ledger state; detect revenue leakage and generate repair plans.

This package is the zero-runtime-dependency TypeScript/JavaScript client from
the audited public integration repository. It supports ESM and CommonJS on
Node.js 18 or newer. Import and construction perform no network request.

## Install

```sh
npm install revenue-integrity
```

## Authenticated client

```ts
import { RevenueIntegrity } from 'revenue-integrity'

const client = new RevenueIntegrity({
  apiKey: process.env.REVENUE_INTEGRITY_API_KEY,
})
```

Never place an API key in browser code, source control, logs, or examples.
Requesting a sandbox key is an email-verification and claim flow; it does not
return a key in the initial response.

- [Product, docs, demo, pricing, privacy, and terms](https://revenueintegrity-api.com/?utm_source=npm&utm_medium=package&utm_campaign=revenue-integrity&utm_content=readme)
- [Source and changelog](https://github.com/API-Disk-Integrations/revenue-integrity)
- [Issues](https://github.com/API-Disk-Integrations/revenue-integrity/issues)

Security reports must not be filed in a public issue. Use the repository's
private security-reporting path after the owner confirms it is enabled.

MIT licensed. The API service remains governed by the product site's terms.
