# Educators — EEGLAB

**Project:** EEGLAB  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/sccn/eeglab.git  
**Pinned commit:** `8ac485f654d6bbb1a6acb8dc9ef3f2eaf3d409ba`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a47bd68910930c42a210793a8514568cba5681c2c747bb40b766d6472cbcbef0`  
**Date:** October 2026

## Teaching with EEGLAB

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `a47bd68910930c42a210793a8514568cba5681c2c747bb40b766d6472cbcbef0` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
