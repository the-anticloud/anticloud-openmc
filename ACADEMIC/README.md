# Academic Use — OPENMC

**Project:** OPENMC  
**Category:** NUCLEAR  
**Upstream:** https://github.com/openmc-dev/openmc  
**Pinned commit:** `3cded0fbe0d6a066c17e74dd818bd19dbbcb10c3`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f0e1e5a8c8b549d6fb5be6caea3f86bf062ee7177649293346368880bc4da22e`  
**Date:** October 2026

## Scope

OPENMC is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `3cded0fbe0d6a066c17e74dd818bd19dbbcb10c3`
- The 16-check assurance register with per-check evidence and hashes
- The AIOSS ledger attesting the project artifacts
- Benchmark output in `BENCH.json`

## Reproducing the result

```
python tools/run_bench.py --out BENCH.json
```

Then recompute any row's SHA3-256 from `ISOLATED_LAB_RESULTS/04_Evidence/`.

## Contact

lois@0-1.gg · 0-1.gg
