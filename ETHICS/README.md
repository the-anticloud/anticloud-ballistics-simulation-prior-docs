# Ethics — BALLISTICS_SIMULATION_PRIOR_DOCS

**Project:** BALLISTICS_SIMULATION_PRIOR_DOCS  
**Category:** ARTILLERY_MANUFACTURING  
**Upstream:** https://github.com/namighuseynov/Ballistics-Simulation  
**Pinned commit:** `ca43b88362dedf6e993c1419205848fda0e39d88`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `82097b110d915d83e112e78bc6cc02e45cb8a0b6ac36cdf588647cea7d8efbc0`  
**Date:** October 2026

## Position

BALLISTICS_SIMULATION_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
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
