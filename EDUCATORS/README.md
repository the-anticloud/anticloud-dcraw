# Educators — DCRAW

**Project:** DCRAW  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `3273c35bfb7ec05ebed60f37aac87bf602b40401`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `374c1857d14b17f1b5e77a91f9eea509625fd783306fce33ce852abb1e95b96b`  
**Date:** October 2026

## Teaching with DCRAW

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `374c1857d14b17f1b5e77a91f9eea509625fd783306fce33ce852abb1e95b96b` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
