# Educators — OPENMC

**Project:** OPENMC  
**Category:** NUCLEAR  
**Upstream:** https://github.com/openmc-dev/openmc  
**Pinned commit:** `3cded0fbe0d6a066c17e74dd818bd19dbbcb10c3`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f0e1e5a8c8b549d6fb5be6caea3f86bf062ee7177649293346368880bc4da22e`  
**Date:** October 2026

## Teaching with OPENMC

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f0e1e5a8c8b549d6fb5be6caea3f86bf062ee7177649293346368880bc4da22e` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
