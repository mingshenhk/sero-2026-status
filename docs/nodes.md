# Node and RPC Status

**Status:** Checking  
**Last Updated:** 2026-03-17

---

## Purpose

This page tracks whether SERO full nodes, RPC endpoints, and public network access points are still usable in 2026.

---

## Official / Historical Node Links

- Core Repository: https://github.com/sero-cash/go-sero
- Core Releases: https://github.com/sero-cash/go-sero/releases
- Official Wiki: https://wiki.sero.cash/en/index.html?file=home-Home
- Source Install Guide (historical): https://wiki.sero.cash/en/index.html?file=Start/from-the-sourcecode-base-on-centos7
- Binary Install Guide (historical): https://wiki.sero.cash/en/index.html?file=Start/from-the-binary-package
- Pullup Docs Repository: https://github.com/sero-cash/pullup-docs

---

## Key Questions

- Is the mainnet still producing blocks?
- Can a fresh full node still sync?
- Are there public nodes that are reachable?
- Does RPC still respond correctly?
- Are historical node setup instructions still valid?

---

## Verification Checklist

| Item | Result | Notes |
|------|--------|-------|
| Full node binary available | Unknown | |
| Full node starts | Unknown | |
| Node sync begins | Unknown | |
| Node reaches current height | Unknown | |
| Peer discovery works | Unknown | |
| RPC endpoint responds | Unknown | |
| Historical config still valid | Unknown | |

---

## Historical Public Node References

These are historical references only and **must be re-tested** before being treated as usable.

| Endpoint | Type | Status | Last Checked | Notes |
|----------|------|--------|--------------|-------|
| http://129.204.197.105:8545 | RPC | Unknown | 2026-03-17 | Historical default node mentioned in Pullup docs |
| [Add your own tested node here] | RPC / Full Node | Unknown | [Date] | |

---

## Suggested Test Commands

Document commands here after confirming current software behavior.

### Example Template

```bash
# start node
[add verified startup command here]

# query block height
[add verified RPC or CLI command here]

# query peers
[add verified peer query command here]
```

Do not leave example commands in production status pages unless they have been tested.

---

## Reporting Template

When reporting a node test, include:

- Date
- OS
- Node version
- Config file used
- Sync result
- Current height reached
- Peer count
- RPC status
- Errors encountered

---

## Known Problems

Use this section for recurring failures such as:

- no peers found
- RPC port unreachable
- startup crash
- database incompatibility
- outdated configuration syntax

_No known problems documented yet._
