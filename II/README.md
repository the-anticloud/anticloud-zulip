# Independent Insurance — ZULIP

**Project:** ZULIP  
**Category:** CHAT_PLATFORMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `29fbc01fa8232da1176932865d31d34085b8f39e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3d89272174b88b45b2618aed13bab80988f56ea8fda62790fb02413bb64dba71`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | ZULIP with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `3d89272174b88b45b2618aed13bab80988f56ea8fda62790fb02413bb64dba71`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
