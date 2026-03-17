# Node and RPC Status

**Status:** Mixed  
**Last Updated:** 2026-03-18

---

## Summary

- Chain appears live and current
- Explorer height matches observed chain state
- Local Windows 11 go-sero / gero binary execution failed in testing
- Native local node operation on the tested Win11 environment is currently not usable

---

## Official / Historical Node Links

- Core Repository: https://github.com/sero-cash/go-sero
- Core Releases: https://github.com/sero-cash/go-sero/releases
- Official Website: https://sero.cash/
- Wiki Home: https://wiki.sero.cash/en/index.html?file=home-Home
- Wiki Repository: https://github.com/sero-cash/wiki

---

## Confirmed Findings

- chain height appears current
- local sync target block count looked correct during test
- maintainer is actively mining on current chain
- go-sero release download can be obtained
- go-sero / gero Windows binaries could not run successfully on tested Windows 11 setup
- gero.exe error involved missing DLL dependency
- older versions were also tested and still failed on the same environment

---

## Current Status Table

| Item | Result | Notes |
|------|--------|-------|
| Chain live status | Working | verified indirectly through mining and explorer comparison |
| Current chain height | Working | observed as current during mining and local sync target display |
| Local Win11 binary execution | Broken | go-sero / gero not usable in tested environment |
| DLL dependency issue | Broken | missing DLL error on Windows 11 |
| Older Windows binaries | Broken | same failure class in maintainer testing |
| RPC self-host testing | Untested | blocked by local node failure |
| Peer discovery | Untested | blocked by local node failure |
| Alternative OS testing | Untested | |

---

## Known Windows 11 Failure

Observed issue:

- `gero.exe` fails on Windows 11
- missing DLL dependency error appears
- maintainer tested older versions and still could not get local node path working

This should currently be treated as a confirmed Windows 11 blocker in the tested environment.

---

## What This Means

SERO chain activity is not the problem.

The problem is specifically:

**local Windows 11 node usability in the tested environment.**

That distinction matters.

---

## Remaining High-Priority Node Tests

- alternative Windows packaging path
- alternative OS test
- self-hosted RPC after a successful node launch
- wallet connection to custom local node

---

## Community Test Reports

### 2026-03-18
- chain live status: working
- explorer height vs chain: matched in manual testing
- local Win11 binary execution: broken
