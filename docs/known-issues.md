# Known Issues

**Last Updated:** 2026-03-18

This page collects confirmed or recurring issues affecting the SERO ecosystem in 2026.

---

## Status Labels

Use these labels when adding issues:

- **Unverified**
- **Partial**
- **Confirmed**
- **Resolved**
- **Outdated Guide**
- **Broken Link**
- **Needs Retest**

---

## Current Issues

### 1. Pullup Windows wallet freezes during creation/import
- Status: **Confirmed**
- Impact: New users cannot reliably onboard through Pullup on tested Windows setup
- Notes: Freezes 100% during wallet/account creation and wallet import

### 2. Pullup web wallet freezes during creation/import
- Status: **Confirmed**
- Impact: Web-based Pullup route is not usable for normal onboarding
- Notes: Page opens, but creation/import path freezes consistently

### 3. Local Win11 node execution is broken
- Status: **Confirmed**
- Impact: Self-hosted local node path is blocked in tested Windows 11 environment
- Notes: go-sero / gero binaries fail to run successfully; missing DLL issue observed

### 4. Official wiki home is broken
- Status: **Confirmed**
- Impact: Users may think official docs are still intact when the historical entry point is broken
- Notes: Wiki repository still exists, but home page entry is not usable

### 5. Historical explorer URL is broken
- Status: **Confirmed**
- Impact: Historical fallback explorer link should not be presented as current infrastructure
- Notes: Returns unusable result / 404

### 6. Native desktop staking remains untested
- Status: **Partial**
- Impact: Users should not assume desktop staking flow matches Popup DApp path
- Notes: Popup staking path works, native desktop staking still not tested

### 7. Liquidity depth is not yet fully profiled
- Status: **Partial**
- Impact: Working DEX path does not guarantee healthy execution on larger trades
- Notes: DEX / swap works, but deeper liquidity analysis remains pending

---

## Positive Counterpoints

These are **not** issues, but they are important status clarifications:

- mainnet is working
- explorer is working
- Full Node Wallet is working
- Popup online wallet is working
- SEED / pool / Coral DEX / CoralSwap are working

---

## How To Report A New Issue

When adding an issue, include:

- title
- date observed
- status
- affected component
- reproduction steps
- logs or screenshots if possible
- whether the issue is still current

---

## Community Issue Reports

### 2026-03-18
- Pullup Windows wallet creation/import freeze: confirmed
- Pullup web wallet creation/import freeze: confirmed
- Win11 local node failure: confirmed
- broken historical links: confirmed
