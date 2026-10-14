# Students — BALLISTICS_SIMULATION_PRIOR_DOCS

**Project:** BALLISTICS_SIMULATION_PRIOR_DOCS  
**Category:** ARTILLERY_MANUFACTURING  
**Upstream:** https://github.com/namighuseynov/Ballistics-Simulation  
**Pinned commit:** `ca43b88362dedf6e993c1419205848fda0e39d88`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `82097b110d915d83e112e78bc6cc02e45cb8a0b6ac36cdf588647cea7d8efbc0`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ca43b88362dedf6e993c1419205848fda0e39d88`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `82097b110d915d83e112e78bc6cc02e45cb8a0b6ac36cdf588647cea7d8efbc0`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
