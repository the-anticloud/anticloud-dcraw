# Students — DCRAW

**Project:** DCRAW  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `3273c35bfb7ec05ebed60f37aac87bf602b40401`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `374c1857d14b17f1b5e77a91f9eea509625fd783306fce33ce852abb1e95b96b`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `3273c35bfb7ec05ebed60f37aac87bf602b40401`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `374c1857d14b17f1b5e77a91f9eea509625fd783306fce33ce852abb1e95b96b`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
