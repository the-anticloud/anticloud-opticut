# Ethics — OPTICUT

**Project:** OPTICUT  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/JeroenGar/sparrow.git  
**Pinned commit:** `5901a79b6c5a74d8b9c356ee2916736567308108`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ed2811d6167e5e49107123dc25ae17e1b720e8eadfb90564fde4df7326033f51`  
**Date:** October 2026

## Position

OPTICUT is packaged for offline deployment with a verifiable audit trail. The
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
