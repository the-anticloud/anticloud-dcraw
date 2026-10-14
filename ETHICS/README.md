# Ethics — DCRAW

**Project:** DCRAW  
**Category:** CAMERAS  
**Upstream:** see BENCH.json  
**Pinned commit:** `3273c35bfb7ec05ebed60f37aac87bf602b40401`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `374c1857d14b17f1b5e77a91f9eea509625fd783306fce33ce852abb1e95b96b`  
**Date:** October 2026

## Position

DCRAW is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
