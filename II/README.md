# Independent Insurance — OPENMC

**Project:** OPENMC  
**Category:** NUCLEAR  
**Upstream:** https://github.com/openmc-dev/openmc  
**Pinned commit:** `3cded0fbe0d6a066c17e74dd818bd19dbbcb10c3`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f0e1e5a8c8b549d6fb5be6caea3f86bf062ee7177649293346368880bc4da22e`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | OPENMC with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `f0e1e5a8c8b549d6fb5be6caea3f86bf062ee7177649293346368880bc4da22e`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
