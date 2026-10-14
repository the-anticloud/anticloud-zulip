# Students — ZULIP

**Project:** ZULIP  
**Category:** CHAT_PLATFORMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `29fbc01fa8232da1176932865d31d34085b8f39e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3d89272174b88b45b2618aed13bab80988f56ea8fda62790fb02413bb64dba71`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `29fbc01fa8232da1176932865d31d34085b8f39e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `3d89272174b88b45b2618aed13bab80988f56ea8fda62790fb02413bb64dba71`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
