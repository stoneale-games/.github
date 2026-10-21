# 🧠 Stoneale

**A play-to-learn mental wellness gaming platform, built on [Stellar](https://stellar.org).**

Stoneale makes emotional well-being fun. Players unwind with short, science-backed games, build healthy habits, and earn **STONE**, a Stellar asset, plus soulbound **wellness badges** as they go.

🌐 **Live demo (testnet):** https://stoneale-bay.vercel.app · 🏠 **Website:** https://stoneale.com

## Why Stellar

* **Freighter wallet:** one-click connect, and players always sign in their own wallet.
* **STONE rewards:** a real Stellar asset minted by a Soroban contract when players complete wellness achievements.
* **Soulbound badges:** non-transferable milestones that players own and can delete at any time.
* **Micro-rewards that make sense:** fees of a fraction of a cent and about 5-second finality.
* **Privacy by design:** only achievement IDs go on-chain, never mood or journal data.

## Repositories

| Repo | What it is |
|---|---|
| [**Frontend**](https://github.com/stoneale-games/Frontend) | React, Vite and TypeScript web app with Freighter wallet connect, the Stellar wallet page and the games |
| [**stoneale-contracts**](https://github.com/stoneale-games/stoneale-contracts) | Soroban smart contracts: `stone-rewards` and `wellness-badges`, live on testnet |
| [**stoneale-sdk**](https://github.com/stoneale-games/stoneale-sdk) | TypeScript SDK: typed contract clients, read helpers and server-side `awardStone` |
| [**Contract-Deployment**](https://github.com/stoneale-games/Contract-Deployment) | One-command testnet deploys, smoke tests, key rotation and badge metadata |

## Roadmap

- [x] **Phase 1, Stellar foundations:** Freighter connect, STONE rewards and badge contracts on testnet, CI
- [ ] **Phase 2, Stellar-native accounts:** ~~sign in with Stellar~~ and ~~game server signs reward calls~~ (built, awaiting backend deploy), retire the EVM stack
- [ ] **Phase 3, wellness games:** breathing, mood check-in and journaling games that pay STONE, plus a badge gallery
- [ ] **Phase 4, player-owned data:** opt-in, encrypted progress proofs players can share with therapists
- [ ] **Phase 5, impact ledger and mainnet:** anonymised on-chain impact metrics, a security audit and mainnet launch

## Contribute

We'd love your help! Browse issues labelled [`good first issue`](https://github.com/search?q=org%3Astoneale-games+label%3A%22good+first+issue%22+state%3Aopen&type=issues) or filter by `complexity: trivial`, `complexity: medium` or `complexity: high`. Comment on an issue to have it assigned to you, then read the repo's `CONTRIBUTING.md`.

> *"The fun side of feeling better."* 💜
