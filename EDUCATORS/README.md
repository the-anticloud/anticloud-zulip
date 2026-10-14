# Educators — ZULIP

**Project:** ZULIP  
**Category:** CHAT_PLATFORMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `29fbc01fa8232da1176932865d31d34085b8f39e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3d89272174b88b45b2618aed13bab80988f56ea8fda62790fb02413bb64dba71`  
**Date:** October 2026

## Teaching with ZULIP

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `3d89272174b88b45b2618aed13bab80988f56ea8fda62790fb02413bb64dba71` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
