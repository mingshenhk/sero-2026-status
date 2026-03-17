# Wallet Setup and Wallet Status

**Status:** Mixed  
**Last Updated:** 2026-03-18

---

## Summary

As of current Windows 11 testing:

- Full Node Wallet: working
- Popup online wallet: working
- Pullup Windows wallet: broken
- Pullup web wallet: broken

---

## Official / Historical Wallet Links

### Full Node Wallet
- Repository: https://github.com/sero-cash/wallet
- Releases: https://github.com/sero-cash/wallet/releases

### Pullup Light Wallet
- Repository: https://github.com/sero-cash/pullup
- Releases: https://github.com/sero-cash/pullup/releases
- Docs Repository: https://github.com/sero-cash/pullup-docs

### Popup
- Repository: https://github.com/sero-cash/popup
- Online Wallet: https://popup-flame.vercel.app/#/

### General SERO
- Official Website: https://sero.cash/
- Wiki Home: https://wiki.sero.cash/en/index.html?file=home-Home
- Wiki Repository: https://github.com/sero-cash/wiki

---

## Confirmed Working

### Full Node Wallet
Tested successfully for:

- new wallet creation
- wallet import
- receiving funds
- sending funds
- transaction history
- reopen after disconnect
- contract / DApp entry

### Popup Online Wallet
Confirmed usable for:

- normal wallet access
- DApp browser access
- SEED DApp access
- pool access
- Coral DEX access
- CoralSwap access

---

## Confirmed Broken

### Pullup Windows Wallet
Confirmed behavior:

- opens
- freezes during wallet/account creation
- freezes during wallet import
- issue reproduced consistently

### Pullup Web Wallet
URL:
- https://pullup-ruby.vercel.app/

Confirmed behavior:

- page opens
- freezes during wallet creation/import
- not usable for normal onboarding
- issue reproduced consistently

---

## Verification Table

| Item | Result | Notes |
|------|--------|-------|
| Full node wallet download works | Working | |
| Full node wallet install works | Working | |
| Full node wallet starts normally | Working | |
| New wallet creation | Working | |
| Existing wallet import | Working | |
| Receive funds | Working | |
| Send funds | Working | |
| Transaction history | Working | |
| Reopen after disconnect | Working | |
| Contract / DApp entry | Working | |
| Popup online wallet usable | Working | |
| Pullup Windows wallet creation/import | Broken | Freezes 100% |
| Pullup web wallet creation/import | Broken | Freezes 100% |

---

## Notes

At the current stage, **Pullup should be treated as unusable** for normal onboarding.

The most practical wallet routes right now are:

1. Full Node Wallet
2. Popup online wallet

---

## Remaining Untested Wallet Items

- native desktop staking page inside Full Node Wallet
- deeper compatibility across more Windows versions
- Popup behavior under larger transaction volume

---

## Community Test Reports

### 2026-03-18
- Full Node Wallet: working
- Popup online wallet: working
- Pullup Windows wallet: broken
- Pullup web wallet: broken# Wallet Setup and Wallet Status

**Status:** Checking  
**Last Updated:** 2026-03-17

---

## Purpose

This page tracks whether SERO wallets are still usable in 2026 and provides a clean checklist for testing installation, sync, and transfers.

---

## Official / Historical Wallet Links

### Full Node Wallet
- Repository: https://github.com/sero-cash/wallet
- Releases: https://github.com/sero-cash/wallet/releases

### Light Wallet (Pullup)
- Repository: https://github.com/sero-cash/pullup
- Releases: https://github.com/sero-cash/pullup/releases
- Docs Repository: https://github.com/sero-cash/pullup-docs

### Mobile Wallet
- Repository: https://github.com/sero-cash/popup

### General SERO Docs
- Official Website: https://sero.cash/
- Official Wiki: https://wiki.sero.cash/en/index.html?file=home-Home
- Wallet Manual (historical): https://wiki.sero.cash/en/index.html?file=Tutorial/manual-of-wallet

---

## What Needs To Be Verified

- Can the wallet still be downloaded from a reliable source?
- Does the wallet still install normally on a modern operating system?
- Can it connect to the network and sync?
- Can it create a new wallet?
- Can it import an existing wallet or key?
- Can it send and receive a transaction successfully?
- Does the wallet expose staking / equity pool features?

---

## Verification Checklist

| Item | Result | Notes |
|------|--------|-------|
| Official wallet source reachable | Unknown | |
| Full node wallet download works | Unknown | |
| Pullup wallet download works | Unknown | |
| Desktop wallet installs | Unknown | |
| Wallet starts normally | Unknown | |
| New wallet creation works | Unknown | |
| Existing wallet import works | Unknown | |
| Network sync works | Unknown | |
| Receive address generation works | Unknown | |
| Outbound transfer works | Unknown | |
| Transaction history loads | Unknown | |
| Staking page accessible | Unknown | |

---

## Recommended Verification Method

When testing a wallet, record:

- Operating system
- Wallet version
- Download source
- Install result
- Sync result
- Transfer test result
- Screenshot or console log if available

### Example Test Template

- Date:
- OS:
- Wallet version:
- Download source:
- Installation:
- Sync:
- Send / receive:
- Notes:

---

## Known Risks

- Old wallet binaries may be outdated
- Historical download links may be broken
- Some wallet instructions from old guides may no longer match current systems
- Network sync may fail if public nodes are unavailable
- Full node wallet and Pullup wallet may not be interchangeable in account-file format

---

## Community Test Reports

_No reports yet._

---

## Notes

This page does not recommend storing significant funds in any wallet until usability and safety are independently verified.
