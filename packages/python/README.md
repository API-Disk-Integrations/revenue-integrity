# Revenue Integrity API Python SDK

Reconcile contracts, usage, invoices, payments and ledger state; detect revenue leakage and generate repair plans.

This package is the standard-library-only Python client from the audited public
integration repository. It supports Python 3.10 or newer. Import and
construction perform no network request.

## Install

```sh
python -m pip install revenue-integrity
```

## Authenticated client

```python
import os
from revenue_integrity import RevenueIntegrity

client = RevenueIntegrity(os.environ["REVENUE_INTEGRITY_API_KEY"])
```

Never place an API key in source control, logs, or examples. Requesting a
sandbox key is an email-verification and claim flow; it does not return a key
in the initial response.

- [Product, docs, demo, pricing, privacy, and terms](https://revenueintegrity-api.com/?utm_source=pypi&utm_medium=project&utm_campaign=revenue-integrity&utm_content=readme)
- [Source and changelog](https://github.com/API-Disk-Integrations/revenue-integrity)
- [Issues](https://github.com/API-Disk-Integrations/revenue-integrity/issues)

Security reports must not be filed in a public issue. Use the repository's
private security-reporting path after the owner confirms it is enabled.

MIT licensed. The API service remains governed by the product site's terms.
