# Security

## Program scope

The [Klarity FHIR exhibit catalog](https://github.com/klaritylabs-us/klarity-fhir-exhibits) indexes **35** small public reference repos. Each exhibit uses **synthetic fixtures only**—no PHI.

## Synthetic data only

All JSON, NDJSON, and X12 sketch fixtures in exhibit repositories are **synthetic**. They must not be replaced with production extracts in public commits.

## Reporting

For security questions about any exhibit or Klarity Labs services:

- **Email:** sk@klaritylabs.ai
- **Website:** [klaritylabs.ai](https://klaritylabs.ai/)

Individual exhibit repos are **read-only reference code** (no supported issue queue). Use email for coordinated disclosure.

Do not commit credentials, tokens, private keys, or customer artifacts. If something sensitive was committed, contact us immediately so we can coordinate removal and rotation.

## Scope

Exhibit checkers are **structural** pre-flight helpers—not penetration tests, not ONC certification, and not a substitute for your own security review of production systems.

## What we do not ship on GitHub

Proprietary verification engine code, licensed rule packs, and customer artifacts remain **private**. Exhibits are MIT reference checkers only.
