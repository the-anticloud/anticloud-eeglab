# Students — EEGLAB

**Project:** EEGLAB  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/sccn/eeglab.git  
**Pinned commit:** `8ac485f654d6bbb1a6acb8dc9ef3f2eaf3d409ba`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a47bd68910930c42a210793a8514568cba5681c2c747bb40b766d6472cbcbef0`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `8ac485f654d6bbb1a6acb8dc9ef3f2eaf3d409ba`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `a47bd68910930c42a210793a8514568cba5681c2c747bb40b766d6472cbcbef0`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
