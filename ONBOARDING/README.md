# Onboarding — OPENMC

**Project:** OPENMC  
**Category:** NUCLEAR  
**Upstream:** https://github.com/openmc-dev/openmc  
**Pinned commit:** `3cded0fbe0d6a066c17e74dd818bd19dbbcb10c3`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f0e1e5a8c8b549d6fb5be6caea3f86bf062ee7177649293346368880bc4da22e`  
**Date:** October 2026

## First hour

1. Read `README.md` — what the project is and what it measures.
2. Read `ISOLATED_LAB_RESULTS/03_Result_Register.md` — the 16 checks and their
   evidence hashes.
3. Run the suite: `python tools/run_bench.py --out BENCH.json`.
4. Verify a hash: recompute SHA3-256 of a file in `04_Evidence/` and compare.

## First day

- `10_TECHNICAL_HANDOFF` — architecture and interfaces
- `11_TUTORIAL_DEVELOPERS` — build and test
- `18_COMMAND_LINE_INTERFACE` — CLI reference
- `27_DEPENDENCIES` — the offline dependency mirror

## Getting help

lois@0-1.gg · 0-1.gg
