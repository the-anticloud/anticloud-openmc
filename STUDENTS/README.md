# Students — OPENMC

**Project:** OPENMC  
**Category:** NUCLEAR  
**Upstream:** https://github.com/openmc-dev/openmc  
**Pinned commit:** `3cded0fbe0d6a066c17e74dd818bd19dbbcb10c3`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f0e1e5a8c8b549d6fb5be6caea3f86bf062ee7177649293346368880bc4da22e`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `3cded0fbe0d6a066c17e74dd818bd19dbbcb10c3`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f0e1e5a8c8b549d6fb5be6caea3f86bf062ee7177649293346368880bc4da22e`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
