# Students — OPTICUT

**Project:** OPTICUT  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/JeroenGar/sparrow.git  
**Pinned commit:** `5901a79b6c5a74d8b9c356ee2916736567308108`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ed2811d6167e5e49107123dc25ae17e1b720e8eadfb90564fde4df7326033f51`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `5901a79b6c5a74d8b9c356ee2916736567308108`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `ed2811d6167e5e49107123dc25ae17e1b720e8eadfb90564fde4df7326033f51`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
