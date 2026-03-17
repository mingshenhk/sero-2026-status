# Explorer Status

**Status:** Working  
**Last Updated:** 2026-03-18

---

## Summary

The current SERO explorer is usable and matches current chain state in manual testing.

The historical explorer URL is not usable.

---

## Explorer Links

### Current Explorer
- https://explorer.sero.cash/

### Historical Explorer
- https://explorer.web.sero.cash/blocks.html

---

## Confirmed Findings

### Current Explorer
Confirmed by manual testing:

- explorer loads
- explorer is usable
- explorer height matches current chain state
- current chain state is consistent with active mining observation

### Historical Explorer
- historical URL returns unusable result / 404
- should not be treated as a live fallback

---

## Verification Table

| Item | Result | Notes |
|------|--------|-------|
| Current explorer reachable | Working | |
| Current explorer usable | Working | |
| Current explorer height freshness | Working | matched manually |
| Current explorer suitable for basic verification | Working | |
| Historical explorer URL | Broken | 404 / unusable |

---

## Current Interpretation

Explorer is one of the stronger surviving parts of the SERO ecosystem in 2026.

However, historical explorer links should be considered outdated and should not be presented as live infrastructure.

---

## Remaining Optional Checks

- search behavior under more cases
- address lookup under newly generated wallets
- transaction visibility immediately after fresh transfer

---

## Community Test Reports

### 2026-03-18
- current explorer: working
- historical explorer: broken# Explorer Status

**Status:** Mixed / Needs Retest  
**Last Updated:** 2026-03-17

---

## Purpose

This page tracks whether public SERO block explorers are still reachable, indexing correctly, and showing recent chain data.

---

## Explorer Candidates

| Explorer | Status | Last Checked | Notes |
|----------|--------|--------------|-------|
| https://explorer.sero.cash/ | Mixed / Needs Retest | 2026-03-17 | Public pages resolve, but freshness and consistency still need local comparison |
| https://explorer.web.sero.cash/blocks.html | Historical | 2026-03-17 | Historical official explorer URL from older official docs |

---

## Current Working Assumption

At least one public explorer domain still resolves.  
However, explorer usability should not be treated as confirmed until you manually compare it against a live node / RPC result.

Use this rule:

- **reachable** does not mean **current**
- **current** does not mean **correct**
- **correct** does not mean **complete**

---

## Questions To Answer

- Is there still a working public explorer?
- Does it load recent blocks?
- Does it show transactions correctly?
- Can addresses and balances be queried?
- Is it current or stale?

---

## Verification Checklist

| Item | Result | Notes |
|------|--------|-------|
| Explorer website reachable | Partial | |
| Recent block list visible | Unknown | |
| Transaction page loads | Partial | |
| Address page loads | Partial | |
| Search works | Unknown | |
| Explorer appears current | Unknown | |

---

## Staleness Check Procedure

A working explorer must be tested against live network observations.

Suggested checks:

1. Load homepage
2. Record latest visible block
3. Compare with node / RPC result
4. Open at least one transaction page
5. Open at least one address page
6. Test search with a known hash

If the explorer loads but the latest block is old, mark it as **stale**, not **working**.

---

## Recommended Manual Test Targets

- Homepage block counter
- Blocks list page
- Transaction list page
- Account detail page
- Transaction detail page
- Search bar behavior
- Block height freshness vs local node

---

## Community Test Reports

_No reports yet._
