# Security Policy

Stoneale handles on-chain rewards and wellness-related user data, so we take security seriously.

## Supported versions

| Component | Network | Supported |
|---|---|---|
| `stoneale-contracts` (latest `main`) | Stellar testnet | ✅ |
| `Frontend` (latest `main`) | stoneale-bay.vercel.app | ✅ |

The contracts have **not been audited yet** and are deployed on **testnet only**. Do not use them with real value.

## Reporting a vulnerability

**Please do not open a public issue for security problems.**

Report vulnerabilities privately by email to **[security@stoneale.com](mailto:security@stoneale.com)**. Include:

- the affected repository, contract or page
- the steps to reproduce, or a proof of concept
- the impact you expect (for example unauthorized minting, a bypassed daily cap, or leaked user data)

We aim to acknowledge reports within **72 hours** and to agree a disclosure timeline with you. We're happy to credit reporters in the fix release.

## Scope

In scope:
- the Soroban contracts (`stone-rewards`, `wellness-badges`): authorization, minting limits, storage and TTL handling, and upgrades
- Frontend wallet flows: transaction building and signing, and any path that could expose keys or user data

Out of scope:
- third-party services (Freighter, Horizon, Soroban RPC, Vercel)
- denial of service through testnet congestion
