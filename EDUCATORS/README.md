# Educators — BALLISTICS_SIMULATION_PRIOR_DOCS

**Project:** BALLISTICS_SIMULATION_PRIOR_DOCS  
**Category:** ARTILLERY_MANUFACTURING  
**Upstream:** https://github.com/namighuseynov/Ballistics-Simulation  
**Pinned commit:** `ca43b88362dedf6e993c1419205848fda0e39d88`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `82097b110d915d83e112e78bc6cc02e45cb8a0b6ac36cdf588647cea7d8efbc0`  
**Date:** October 2026

## Teaching with BALLISTICS_SIMULATION_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `82097b110d915d83e112e78bc6cc02e45cb8a0b6ac36cdf588647cea7d8efbc0` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
