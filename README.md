# JesJupyter

**Senior Blockchain Security Researcher — Solana, EVM & Cross-Protocol Integrations**

Co-founder of [Taichi Audit](https://taichiaudit.com/) · Core Member of [DeFiHackLabs](https://defihacklabs.io/)

My work spans competitive audits, private engagements, open-source contributions, and source-level security research.

- **407 recorded High/Critical and Medium findings** across public competitions and private security reviews
- **9 recorded first-place finishes**, including Coinbase SpendPermission, Arcade.xyz, and OneWorld
- **10+ additional Solana engagements under NDA**
- Recurring collaborations with Cyfrin, Pashov Audit Group, Fuzzland, Plainshift, Burra Sec, Failsafe, and yAudit
- Stack: 🟦 Solidity / EVM · 🟩 Solana / Rust · 🟧 Move · 🟪 Cairo · 🟨 Daml / Canton · Go

## Contact

- 💬 Direct: [jes163940@gmail.com](mailto:jes163940@gmail.com) · [Telegram](https://t.me/jesjupyter)
- 🐦 Research and updates: [X / Twitter](https://twitter.com/jesjupyter) · [@jesjupyter](https://twitter.com/jesjupyter)

---

## Selected Findings

1. **Velvet — Share Manipulation via Liquidity Inflation in Position Tokenization** `Solo · Contest`
   Direct interaction with the underlying Uniswap V3 position can inflate recorded liquidity, distort share issuance, and capture value from later depositors.
   → [View finding](https://cantina.xyz/code/8cf9c7a0-a7a6-446a-8577-1e2c254eb5a8/findings/58)

2. **Royco — Reward-Rate Manipulation via a Short Reward-Interval Extension** `Solo · Contest`
   Extending a campaign close to expiry can unexpectedly change the reward rate and redistribute value between participants.
   → [View finding](https://cantina.xyz/code/fadb5a8f-e39c-4a6b-89f6-a03858bb8602/findings/459)

3. **Velvet — Hash Collision in Token Bit-Position Mapping** `Contest`
   Modulo-based token mapping can assign multiple assets to the same bit position, breaking token tracking and downstream accounting.
   → [View finding](https://cantina.xyz/code/8cf9c7a0-a7a6-446a-8577-1e2c254eb5a8/findings/41)

4. **Royco — Unauthorized IP Can Create Fake Orders** `Contest`
   A missing authorization check allows an ineligible IP to award points and create orders that should never exist.
   → [View finding](https://cantina.xyz/code/fadb5a8f-e39c-4a6b-89f6-a03858bb8602/findings/527)

5. **Arcade.xyz — Lender Loss on Immediate Loan Repayment** `Solo · Contest`
   Without a minimum repayment period, a borrower can repay too quickly for the lender to recover the intended economics of the loan.
   → [View finding](https://cantina.xyz/code/c2e31b04-fbb2-4355-80ef-141d58b6e0cc/findings/17)

6. **Coinbase EIP-7702 Proxy — Implementation Signatures Never Expire** `Contest`
   A signed implementation update remains executable indefinitely because the signed payload has no expiration control.
   → [View finding](https://cantina.xyz/code/b0a948cd-c861-4807-b36e-d680d82598bf/findings/96)

---

## Track Record

| Category | High / Critical | Medium | H/M Total |
|---|---:|---:|---:|
| Public competitions | 34 | 71 | 105 |
| Secure3 | 4 | 20 | 24 |
| Private engagements | 91 | 187 | 278 |
| **Total** | **129** | **278** | **407** |


## Selected Competition Results

[Aggregated public audit profile](https://audits.sherlock.xyz/watson/jesjupyer)

| Platform | Protocol | Result | Focus | Stack | Accepted findings | Evidence |
|---|---|---:|---|---|---|---|
| Cantina | Arcade.xyz | 🏆 **1st** | Lending | 🟦 Solidity / EVM | 2 Medium, including 1 solo | [Leaderboard](https://cantina.xyz/code/c2e31b04-fbb2-4355-80ef-141d58b6e0cc/overview/leaderboard) |
| Cantina | Coinbase SpendPermission | 🏆 **1st** | Smart wallet | 🟦 Solidity / EVM | Low-severity review winner | [Leaderboard](https://cantina.xyz/code/6837e02a-0a87-4577-a047-4e1ea71cff01/overview/leaderboard) |
| CodeHawks | OneWorld | 🏆 **1st** | Marketplace / DAO | 🟦 Solidity / EVM | 1 High, 1 Medium | [Leaderboard](https://codehawks.cyfrin.io/contests/cm2mxcaoo000112pvkwt2nb8u) |
| Cantina | Usual Pegasus | 🥈 **2nd** | Order book / DEX | 🟦 Solidity / EVM | 1 Medium | [Leaderboard](https://cantina.xyz/code/31a752e3-8ece-49b3-a9ee-d7294c659340/overview/leaderboard) |
| Code4rena | Badger eBTC Zap Router | 🥈 **2nd** | Lending | 🟦 Solidity / EVM | 1 Medium | [Report](https://code4rena.com/audits/2024-06-ebtc-zap-router) |
| Cantina | Coinbase EIP-7702 Proxy | 🥈 **2nd** | Smart wallet | 🟦 Solidity / EVM | 1 Medium | [Leaderboard](https://cantina.xyz/code/b0a948cd-c861-4807-b36e-d680d82598bf/overview/leaderboard) |
| Cantina | Royco | 🥉 **3rd** | Order book / DEX | 🟦 Solidity / EVM | 7 High, 6 Medium; most findings; 1 solo | [Leaderboard](https://cantina.xyz/code/fadb5a8f-e39c-4a6b-89f6-a03858bb8602/overview/leaderboard) |
| Code4rena | THORWallet | **6th** | Smart wallet | 🟦 Solidity / EVM | 1 High, 1 Medium | [Report](https://code4rena.com/audits/2025-02-thorwallet) |
| CodeHawks | TempleGold | **6th** | Staking | 🟦 Solidity / EVM | 1 High, 1 Low | [Results](https://codehawks.cyfrin.io/c/2024-07-templegold/results?page=1) |
| CODESPECT | SpecSiege | **6th** | Bonding | 🟦 Solidity / EVM | 3 Medium, 2 Low | — |
| Sherlock | Polygon Heimdall V2 | **7th** | DLT / validator infrastructure | Go | 3 Medium, 19 Low | [Profile](https://audits.sherlock.xyz/watson/jesjupyer) |
| Cantina | Morpho Vaults | **8th** | Lending / vaults | 🟦 Solidity / EVM | 1 Medium | [Leaderboard](https://cantina.xyz/code/523e1540-f8c3-45ae-9c5d-b6d35d3a326c/overview/leaderboard) |
| Code4rena | TraitForge | **10th** | NFT / GameFi | 🟦 Solidity / EVM | 2 High, 5 Medium | [Report](https://code4rena.com/audits/2024-07-traitforge) |
| Cantina | Velvet Capital | **11th** | DeFi / AMM | 🟦 Solidity / EVM | 1 High, 3 Medium | [Leaderboard](https://cantina.xyz/code/8cf9c7a0-a7a6-446a-8577-1e2c254eb5a8/overview/leaderboard) |
| Cantina | DefiApp | **11th** | Yield farming | 🟦 Solidity / EVM | 1 High, 1 Medium | [Leaderboard](https://cantina.xyz/code/1b64737c-1373-4ecf-a179-4cd0d7b0b232/overview/leaderboard) |
| Cantina | YOLO Games | **14th** | GameFi | 🟦 Solidity / EVM | 1 Medium | [Leaderboard](https://cantina.xyz/code/a2c3cc6a-e384-495f-9751-5d7e657bc219/overview/leaderboard) |
| Code4rena | UniStaker Infrastructure | **15th** | Staking | 🟦 Solidity / EVM | — | [Report](https://code4rena.com/reports/2024-02-uniswap-foundation) |
| Cantina | Goat Tech | **15th** | GameFi / staking | 🟦 Solidity / EVM | 1 High, 3 Medium | [Leaderboard](https://cantina.xyz/code/f214cf86-cc80-40c0-a70b-e9bb25d7ac80/overview/leaderboard) |
| Cantina | Bima | **16th** | Lending | 🟦 Solidity / EVM | 1 Medium | [Leaderboard](https://cantina.xyz/code/44d68da7-3cf4-4cec-a3f8-f0917062dac6/overview/leaderboard) |
| Cantina | mev-commit | **17th** | Network / commitments | 🟦 Solidity / EVM | 1 High, 3 Medium | [Leaderboard](https://cantina.xyz/code/4ee8716d-3e0e-4f59-b90d-aa56bf3b484c/overview/leaderboard) |
| Cantina | Solayer Bridge | **17th** | Bridge | 🟩 Solana / Rust | 1 High, 3 Medium | [Leaderboard](https://cantina.xyz/code/0f543452-2076-438f-86ae-bbd6b065fffb/overview/leaderboard) |
| Code4rena | Panoptic | **19th** | Options / perpetuals | 🟦 Solidity / EVM | 1 Medium | [Report](https://code4rena.com/audits/2024-04-panoptic) |
| Code4rena | Chakra | **20th** | Settlement | 🟦 Solidity / EVM | 2 High, 2 Medium | [Report](https://code4rena.com/audits/2024-08-chakra) |
| Code4rena | Vultisig | **21st** | Uniswap V3 integration | 🟦 Solidity / EVM | 2 Medium | [Report](https://code4rena.com/reports/2024-06-vultisig) |
| Code4rena | Althea Liquid Infrastructure | **28th** | ERC-20 / infrastructure | 🟦 Solidity / EVM | 2 Medium | [Report](https://code4rena.com/audits/2024-02-althea-liquid-infrastructure) |
| Code4rena | Revert Lend | **28th** | Lending | 🟦 Solidity / EVM | 2 Medium | [Report](https://code4rena.com/reports/2024-03-revert-lend) |

### Secure3

- [Secure3 leaderboard](https://app.secure3.io/zh/leaderboard?platform=s3)
- 6 first-place finishes and 10+ Top 3 finishes
- 4 High findings, including 1 solo; 20 Medium findings, including 11 solo

---

## Private Engagements

The engagements below include independent work, guest-auditor roles, and reviews delivered through established security teams. Public reports are linked where available; private and NDA work is included only at the level permitted for disclosure.

| Selected engagement | Delivered through | Focus | Stack | Evidence |
|---|---|---|---|---|
| [Deriverse](https://deriverse.io/) | Cyfrin | DEX / perpetuals | 🟩 Solana / Rust | [Public report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2025-12-15-cyfrin-deriverse-dex-v2.0.pdf) |
| [Securitize SVM On/Off Ramp](https://www.securitize.io/) | Cyfrin | RWA / on-off ramp | 🟩 Solana / Rust | [Public report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-02-19-cyfrin-securitize-svm-on-off-ramp-v2.0.pdf) |
| [Securitize Bridge](https://www.securitize.io/) | Cyfrin | RWA / bridge | 🟩 Solana / Rust | [Public report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-04-30-cyfrin-securitize-solana-bridge-v2.1.pdf) |
| [USD1](https://worldlibertyfinancial.com/usd1) | Fuzzland | Canton token | 🟨 Daml / Canton | Private report |
| [Pump.fun](https://pump.fun/) | Pashov Audit Group | Launchpad | 🟩 Solana / Rust | Private report |
| [StarkWare](https://www.starkware.co/) | Pashov Audit Group | Smart wallet | 🟪 Cairo | Private report |
| [Virtuals ACP](https://www.virtuals.io/) | Failsafe | Settlement | 🟦 Solidity / EVM | Private report |

<details>
<summary><strong>View the complete private-engagement record</strong></summary>

### Taichi Audit

| Protocol | Provider | Focus | Stack | High / Critical | Medium | Low | Evidence |
|---|---|---|---|---:|---:|---:|---|
| [LazyOtter](https://lazyotter.finance/) | Taichi Audit | Yield farming | 🟦 Solidity / EVM | 1 | 3 | — | — |
| [Lambo Win](https://lambo-win.gitbook.io/lambo.win) | Taichi Audit | Launchpad | 🟦 Solidity / EVM | 0 | 3 | — | — |
| [Isle V2](https://www.isle.finance/) | Taichi Audit | Lending | 🟦 Solidity / EVM | 3 | 7 | 8 | — |

### Cyfrin

| Protocol | Provider | Focus | Stack | High / Critical | Medium | Low | Evidence |
|---|---|---|---|---:|---:|---:|---|
| Temple DAO Mitigation | CodeHawks | Staking | 🟦 Solidity / EVM | 1 | 2 | 1 | Private report |
| [Deriverse](https://deriverse.io/) | Cyfrin | DEX / perpetuals | 🟩 Solana / Rust | 9 | 14 | 8 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2025-12-15-cyfrin-deriverse-dex-v2.0.pdf) |
| [Story IP Derivative Agent](https://www.story.foundation/) | Cyfrin | Agent | 🟦 Solidity / EVM | 0 | 0 | 1 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-01-15-cyfrin-story-ip-derivative-agent-v2.1.pdf) |
| [Securitize SVM On/Off Ramp](https://www.securitize.io/) | Cyfrin | RWA / on-off ramp | 🟩 Solana / Rust | 1 | 1 | 5 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-02-19-cyfrin-securitize-svm-on-off-ramp-v2.0.pdf) |
| Private | Cyfrin | RWA | 🟩 Solana / Rust | 0 | 1 | 2 | — |
| [Securitize SPL ACL](https://www.securitize.io/) | Cyfrin | RWA / access control | 🟩 Solana / Rust | 0 | 0 | 0 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-03-17-cyfrin-securitize-solana-spl-acl-v2.0.pdf) |
| [Securitize Whitelister](https://www.securitize.io/) | Cyfrin | RWA / whitelisting | 🟩 Solana / Rust | 0 | 0 | 1 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-03-18-cyfrin-securitize-solana-whitelister-v2.0.pdf) |
| [Securitize Bridge](https://www.securitize.io/) | Cyfrin | RWA / bridge | 🟩 Solana / Rust | 2 | 1 | 6 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-04-30-cyfrin-securitize-solana-bridge-v2.1.pdf) |
| Private | Cyfrin | RWA | 🟩 Solana / Rust | 0 | 0 | 4 | — |
| [Securitize Jump Router](https://www.securitize.io/) | Cyfrin | Router | 🟩 Solana / Rust | 0 | 0 | 1 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-06-09-cyfrin-securitize-svm-jump-router-v2.0.pdf) |
| [Securitize Bridge ACL Support](https://www.securitize.io/) | Cyfrin | Bridge / access control | 🟩 Solana / Rust | 0 | 0 | 1 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-06-26-cyfrin-securitize-svm-bridge-acl-support-v2.0.pdf) |
| Private | Cyfrin | NFT marketplace | 🟩 Solana / Rust | 2 | 8 | 10 | — |
| Private | Cyfrin | Oracle | 🟩 Solana / Rust | 0 | 0 | 2 | — |
| Private | Cyfrin | RWA | 🟩 Solana / Rust | 0 | 0 | 0 | — |


### Burra Sec

| Protocol | Provider | Focus | Stack | High / Critical | Medium | Low | Evidence |
|---|---|---|---|---:|---:|---:|---|
| [Zama](https://www.zama.org/) | Burra Sec | LayerZero integration | 🟦 Solidity / EVM + 🟩 Solana / Rust | 0 | 0 | 1 | — |
| [Zama](https://www.zama.org/) | Burra Sec | LayerZero integration | 🟦 Solidity / EVM + 🟩 Solana / Rust | 0 | 0 | 0 | — |
| [Zama](https://www.zama.org/) | Burra Sec | LayerZero integration | JavaScript | 0 | 3 | 1 | — |
| [Centrifuge Token Bridge](https://centrifuge.io/) | Burra Sec | LayerZero integration | 🟦 Solidity / EVM | 0 | 0 | 1 | — |

### Fuzzland

| Protocol | Provider | Focus | Stack | High / Critical | Medium | Low | Evidence |
|---|---|---|---|---:|---:|---:|---|
| [Vishwa Network BTCVC](https://vishwanetwork.xyz/) | Fuzzland | Cross-chain | 🟦 Solidity / EVM | 2 | 0 | 0 | — |
| [Vishwa Network SBTCVC](https://vishwanetwork.xyz/) | Fuzzland | Cross-chain | 🟧 Move | 1 | 0 | 1 | — |
| [Vishwa Network SBTCVC](https://vishwanetwork.xyz/) | Fuzzland | Cross-chain | 🟧 Move | 1 | 1 | 0 | — |
| [Tenbin](https://tenbin.io/) | Fuzzland | Yield / ERC-4626 | 🟦 Solidity / EVM | 4 | 2 | 2 | — |
| ThetaFunction RFQ | Fuzzland | RFQ | 🟦 Solidity / EVM | 2 | 1 | 2 | — |
| ThetaFunction RFQ V2 | Fuzzland | RFQ | 🟦 Solidity / EVM | 0 | 3 | 2 | — |
| [Dolomite](https://dolomite.io/) | Fuzzland | dYdX fork | 🟦 Solidity / EVM | 2 | 6 | 3 | — |
| [USD1](https://worldlibertyfinancial.com/usd1) | Fuzzland | Canton token | 🟨 Daml / Canton | 1 | 1 | 2 | — |
| [USD1 PreApproval](https://worldlibertyfinancial.com/usd1) | Fuzzland | Canton token | 🟨 Daml / Canton | 0 | 0 | 1 | — |
| ROBO Finance | Fuzzland | DeFi | 🟦 Solidity / EVM | 0 | 4 | 2 | — |
| [Vishwa Network](https://vishwanetwork.xyz/) | Fuzzland | Cross-chain | TypeScript | 0 | 3 | 3 | — |

### Pashov Audit Group

| Protocol | Provider | Focus | Stack | High / Critical | Medium | Low | Evidence |
|---|---|---|---|---:|---:|---:|---|
| Hyperhyper | Pashov Audit Group | Lending | 🟦 Solidity / EVM | 6 | 9 | 11 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Hyperhyper-security-review_2025-03-30.pdf) |
| RipIt | Pashov Audit Group | Lottery | 🟦 Solidity / EVM | 6 | 9 | 26 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/RipIt-security-review_2025-04-25.pdf) |
| [TokenLogic](https://www.tokenlogic.xyz/) | Pashov Audit Group | Yield | 🟦 Solidity / EVM | 0 | 0 | 5 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/TokenLogic-security-review_2025-05-05.pdf) |
| [KittenSwap](https://kittenswap.finance/) | Pashov Audit Group | Swap / DEX | 🟦 Solidity / EVM | 4 | 4 | 14 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/KittenSwap-security-review_2025-05-07.pdf) |
| Gacha | Pashov Audit Group | GameFi | 🟦 Solidity / EVM | 1 | 4 | 12 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Gacha-security-review_2025-01-27.pdf) |
| [HyperStable](https://hyperstable.xyz/) | Pashov Audit Group | Stablecoin | 🟦 Solidity / EVM | 0 | 1 | 3 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Hyperstable-security-review_2025-02-26.pdf) |
| [Bancor](https://bancor.network/) | Pashov Audit Group | DEX | 🟦 Solidity / EVM | 0 | 1 | 6 | Private report |
| [RAAC](https://raac.io/) | Pashov Audit Group | RWA | 🟦 Solidity / EVM | 4 | 9 | 16 | Private report |
| [Avon](https://www.avon.xyz/) | Pashov Audit Group | Lending | 🟦 Solidity / EVM | 4 | 12 | 21 | Private report |
| [Bancor](https://bancor.network/) | Pashov Audit Group | DEX | 🟦 Solidity / EVM | 0 | 1 | 0 | Private report |
| [Pump.fun](https://pump.fun/) | Pashov Audit Group | Launchpad | 🟩 Solana / Rust | 0 | 0 | 3 | Private report |
| [SXT](https://www.spaceandtime.io/) | Pashov Audit Group | Uniswap V3 integration | 🟦 Solidity / EVM | 1 | 4 | 4 | Private report |
| [Thrust](https://app.thrust.com/) | Pashov Audit Group | Launchpad | 🟩 Solana / Rust | 3 | 3 | 2 | Private report |
| [Pump.fun](https://pump.fun/) | Pashov Audit Group | Launchpad | 🟩 Solana / Rust | 0 | 1 | 1 | Private report |
| AlphaHype | Pashov Audit Group | Hyperliquid | 🟦 Solidity / EVM | 1 | 3 | 3 | Private report |
| [SQDGN](https://www.sqdgn.ai/) | Pashov Audit Group | ERC-20 | 🟦 Solidity / EVM | 0 | 0 | 2 | Private report |
| [Ouroboros](https://www.ouroboros.finance/) | Pashov Audit Group | Launchpad | 🟦 Solidity / EVM | 0 | 9 | 8 | Private report |
| [Anthias](https://anthias.xyz/) | Pashov Audit Group | Router | 🟦 Solidity / EVM | 0 | 1 | 4 | Private report |
| [Tangent](https://www.tangent.finance/) | Pashov Audit Group | Lending | 🟦 Solidity / EVM | 0 | 2 | 5 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Tangent-security-review_2025-10-30.pdf) |
| [Tangent](https://www.tangent.finance/) | Pashov Audit Group | Lending | 🟦 Solidity / EVM | 0 | 0 | 3 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Tangent-security-review_2025-12-08.pdf) |
| [Pump.fun](https://pump.fun/) | Pashov Audit Group | Launchpad | 🟩 Solana / Rust | 0 | 0 | 2 | Private report |
| Zoop | Pashov Audit Group | Cross-chain | 🟦 Solidity / EVM | 1 | 3 | 8 | Private report |
| [StarkWare](https://www.starkware.co/) | Pashov Audit Group | Smart wallet | 🟪 Cairo | 0 | 0 | 3 | Private report |
| SQD | Pashov Audit Group | Staking | 🟦 Solidity / EVM | 1 | 2 | 5 | Private report |
| [TokenLock / Opinion](https://www.opinion.trade/) | Pashov Audit Group | Airdrop | 🟦 Solidity / EVM | 0 | 0 | 5 | Private report |
| [0xOstium](https://www.ostium.com/) | Pashov Audit Group | RWA | 🟦 Solidity / EVM | 0 | 0 | 5 | Private report |
| [veRAAC](https://raac.io/) | Pashov Audit Group | RWA | 🟦 Solidity / EVM | 3 | 2 | 1 | Private report |
| [0xOstium](https://www.ostium.com/) | Pashov Audit Group | RWA | 🟦 Solidity / EVM | 0 | 0 | 3 | Private report |
| [veRAAC](https://raac.io/) | Pashov Audit Group | Locker | 🟦 Solidity / EVM | 4 | 3 | 6 | Private report |
| [0xOstium](https://www.ostium.com/) | Pashov Audit Group | RWA | 🟦 Solidity / EVM | 0 | 0 | 3 | Private report |
| [Pump.fun](https://pump.fun/) | Pashov Audit Group | Launchpad | 🟩 Solana / Rust | 1 | 2 | 13 | Private report |

### yAudit — Guest Auditor

| Protocol | Provider | Focus | Stack | High / Critical | Medium | Low | Evidence |
|---|---|---|---|---:|---:|---:|---|
| [Fira](https://www.fira.money/) | yAudit | Lending | 🟦 Solidity / EVM | 0 | 0 | 2 | Private report |

### Plainshift
| Protocol | Provider | Focus | Stack | High / Critical | Medium | Low | Evidence |
|---|---|---|---|---:|---:|---:|---|
| Private | Plainshift | ICO / staking / launchpad | 🟦 Solidity / EVM | 11 | 20 | 9 | — |
| Private | Plainshift | ICO | 🟩 Solana / Rust | 1 | 2 | 3 | — |

### Failsafe

| Protocol | Provider | Focus | Stack | High / Critical | Medium | Low | Evidence |
|---|---|---|---|---:|---:|---:|---|
| [Virtuals PR](https://www.virtuals.io/) | Failsafe | Launchpad | 🟦 Solidity / EVM | 0 | 1 | 1 | — |
| [Virtuals PR](https://www.virtuals.io/) | Failsafe | Launchpad | 🟦 Solidity / EVM | 0 | 0 | 1 | — |
| [Virtuals PR](https://www.virtuals.io/) | Failsafe | Launchpad | 🟦 Solidity / EVM | — | — | — | — |
| [AZverse](https://www.azverse.xyz/en) | Failsafe | DEX | 🟦 Solidity / EVM | 1 | 2 | 1 | — |
| [Virtuals PR](https://www.virtuals.io/) | Failsafe | Launchpad | 🟦 Solidity / EVM | 0 | 1 | 2 | Private report |
| [Virtuals PR](https://www.virtuals.io/) | Failsafe | Launchpad | 🟦 Solidity / EVM | 0 | 3 | 4 | Private report |
| [Virtuals ACP](https://www.virtuals.io/) | Failsafe | Settlement | 🟦 Solidity / EVM | 6 | 9 | 15 | Private report |

### Undisclosed Clients

10+ additional Solana engagements are covered by NDA. Their private finding counts are not included in the portfolio total.

| Client | Focus | Stack | Findings | Evidence |
|---|---|---|---|---|
| Private | CLMM | 🟩 Solana / Rust | Private | NDA |
| Private | Launchpad | 🟩 Solana / Rust | Private | NDA |
| Private | Prediction market | 🟩 Solana / Rust | Private | NDA |
| Private | Dark pool | 🟩 Solana / Rust | Private | NDA |
| Private | DEX router | 🟩 Solana / Rust | Private | NDA |
| Private | Position manager | 🟩 Solana / Rust | Private | NDA |
| Private | Cross-chain token | 🟩 Solana / Rust | Private | NDA |
| Private | Cross-chain token | 🟩 Solana / Rust | Private | NDA |
| Private | CLMM | 🟦 Solidity / EVM | Private | NDA |
| Private | RFQ | 🟦 Solidity / EVM | Private | NDA |

</details>


## Research & Talks

- **[SPL vs Token-2022: From Mint to Account](https://taichiaudit.com/blog/solana-security-series-4)**
  A source-level comparison of mint and account layouts, ATA creation, program IDs, extensions, and real initialization flows.

- **[Why Anchor Accounts Go Stale After CPI (and When to Reload)](https://taichiaudit.com/blog/solana-security-series-3)**
  An explanation of Anchor's cached account state, CPI boundaries, and when `reload()` is actually required.

- **[How `init` and `init_if_needed` Work Under the Hood](https://taichiaudit.com/blog/solana-security-series-2)**
  A deep dive into Anchor account initialization and associated-token-account griefing attacks.

- **[Pre-Funding DoS in Solana: Breaking `create_account` with Non-Zero Lamports](https://taichiaudit.com/blog/solana-security-series-1)**
  A system-level analysis of how predictable, pre-funded accounts can permanently block initialization.

- **[Understanding Liquidity: Uniswap V2 vs V3](https://taichiaudit.com/blog/understanding-liquidity-uniswap-v2-v3)**
  A technical comparison of AMM liquidity models and the security assumptions introduced by concentrated liquidity.

- **[Deep Dive into Inflation Attacks](https://www.youtube.com/watch?v=arRMN_tPu3c)**
  A Solidity and smart-contract-security talk covering inflation-attack mechanics and mitigations.

## Open-Source Contributions

### Foundry EIP-7702 Support During the Pectra Upgrade

Identified and fixed an EIP-7702-related issue in Foundry while Ethereum's Pectra upgrade was being activated:

- [Issue: foundry-rs/foundry#10181](https://github.com/foundry-rs/foundry/issues/10181)
- [Pull request: foundry-rs/foundry#10182](https://github.com/foundry-rs/foundry/pull/10182)

---