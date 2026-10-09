# Educators — OPTICUT

**Project:** OPTICUT  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/JeroenGar/sparrow.git  
**Pinned commit:** `5901a79b6c5a74d8b9c356ee2916736567308108`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ed2811d6167e5e49107123dc25ae17e1b720e8eadfb90564fde4df7326033f51`  
**Date:** October 2026

## Teaching with OPTICUT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `ed2811d6167e5e49107123dc25ae17e1b720e8eadfb90564fde4df7326033f51` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
