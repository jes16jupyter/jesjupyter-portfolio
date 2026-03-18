# JesJupyter

- Blockchain security researcher & smart contract auditor, specializing in:  
  🟦 Solidity (EVM) · 🟩 Solana (Rust) · 🟪 Cairo · 🟧 Move (Rust)
- Co-founder, [Taichi Audit](https://taichiaudit.com/), Core Member of [DeFiHackLabs](https://defihacklabs.io/)
- Uncovered 330+ High/Medium Severity Findings
- Audit collaborations: Cyfrin, Plainshift, Pashov Audit Group, Burra Sec, FailSafe, YAudit
- Audited notable protocols: Coinbase (EIP-7702), PUMP (Launchpad), Badger (Lending), Usual (DEX), HashKey (Staking), Fira (Lending), StarkWare

---

## 📫 Contact

- 📧 Email: [jes163940@gmail.com](mailto:jes163940@gmail.com)  
- 🐦 Twitter: [@jesjupyter](https://twitter.com/jesjupyter)  
- 💬 Telegram: [@jesjupyter](https://t.me/jesjupyter)

---

## 🔥 Top Findings (Selected)

1. **[SOLO][Contest] Share Manipulation via Liquidity Inflation Attack in Position Tokenization**  
   ↳ [View Finding](https://cantina.xyz/code/8cf9c7a0-a7a6-446a-8577-1e2c254eb5a8/findings/58)  
   Description: Position tokenization can be exploited by inflating underlying liquidity via directly interacting with the underlying protocol(Uniswap V3), stealing new users’ contributions.

2. **[SOLO][Contest] Reward Rate Manipulation via Short Extension of Rewards Interval**  
   ↳ [View Finding](https://cantina.xyz/code/fadb5a8f-e39c-4a6b-89f6-a03858bb8602/findings/459)  
   Description: A campaign's reward rate can be manipulated near the end by extending the reward interval, causing financial harm.

3. **[Contest] Hash Collision Vulnerability in Token Bit Position Mapping**  
   ↳ [View Finding](https://cantina.xyz/code/8cf9c7a0-a7a6-446a-8577-1e2c254eb5a8/findings/41)  
   Description: Modulo-based token mapping can cause hash collisions, leading to incorrect token tracking and system malfunction.

4. **[Contest] Lack of Check If IP Can Award Point — Fake Order Creation**  
   ↳ [View Finding](https://cantina.xyz/code/fadb5a8f-e39c-4a6b-89f6-a03858bb8602/findings/527)  
   Description: Missing IP authorization check allows fake order creation, disrupting protocol operation.

5. **[SOLO][Contest] Lender Loss on Quick Loan Repayment**  
   ↳ [View Finding](https://cantina.xyz/code/c2e31b04-fbb2-4355-80ef-141d58b6e0cc/findings/17)  
   Description: No minimum repayment time can cause lenders to incur losses if the borrower repays too quickly, potentially harming lender funds.

6. **[Contest] Missing Signature Expiration Control in Implementation Setting**  
   ↳ [View Finding](https://cantina.xyz/code/b0a948cd-c861-4807-b36e-d680d82598bf/findings/96)  
   Description: Implementation signatures lack expiration, allowing old signatures to remain executable indefinitely.

---


## 🔢 Finding Summary

| Platform | High/Critical | Medium | Summary |
|----------|---------------|--------|---------|
| Public Contest | 34 | 63 | 97 |
| Secure3 | 4 | 20 | 24 |
| Private Audits | 70 | 141 | 211 |
| Total | 108 | 224 | 332 |

## 🏆 Contest Performance
- [**Mainstream Audit Contest Platforms**](https://audits.sherlock.xyz/watson/jesjupyer): 34 High, 63 Medium  

| Platform | Protocol | Ranking | Description | Language | Findings | Link |
|----------|---------|------|---------|------|------|------|
| Cantina | arcadexyz/arcade-protocol |  🏆 **1st** / 19 Participants | Lending | 🟦 Solidity (EVM) | 2 Medium (1 SOLO) | [Leaderboard](https://cantina.xyz/code/c2e31b04-fbb2-4355-80ef-141d58b6e0cc/overview/leaderboard) |
| Cantina | Coinbase Spend-permission | 🏆 **1st** / 353 Participants | Smart Wallet | 🟦 Solidity (EVM) | — | [Leaderboard](https://cantina.xyz/code/6837e02a-0a87-4577-a047-4e1ea71cff01/overview/leaderboard) |
| Codehawks | OneWorld | 🏆 **1st** / 65 Participants | MarketPlace, DAO | 🟦 Solidity (EVM) | 1 High, 1 Medium | [Leaderboard](https://codehawks.cyfrin.io/contests/cm2mxcaoo000112pvkwt2nb8u) |
| Cantina | pegasus(usual) | 🥈 **2nd** / 346 Participants | Orderbook, Dex | 🟦 Solidity (EVM) |1 Medium | [Leaderboard](https://cantina.xyz/code/31a752e3-8ece-49b3-a9ee-d7294c659340/overview/leaderboard) |
| Code4rena | Badger | 🥈 **2nd** / 16 Participants | Lending | 🟦 Solidity (EVM) |1 Medium | [Leaderboard](https://code4rena.com/audits/2024-06-ebtc-zap-router) |
| Cantina | Coinbase EIP7702Proxy | 🥈 **2nd** / 309 Participants | Smart Wallet | 🟦 Solidity (EVM) | 1 Medium | [Leaderboard](https://cantina.xyz/code/b0a948cd-c861-4807-b36e-d680d82598bf/overview/leaderboard) |
| Cantina | Royco | 🥉 **3rd** / 281 Participants | Orderbook, Dex | 🟦 Solidity (EVM) | 7 High, 6 Medium (Most findings, 1 SOLO) | [Leaderboard](https://cantina.xyz/code/fadb5a8f-e39c-4a6b-89f6-a03858bb8602/overview/leaderboard) |
| Code4rena | ThorWallet  | 6 / 132 Participants | Smart Wallet | 🟦 Solidity (EVM) | 1 High, 1 Medium | [Leaderboard](https://code4rena.com/audits/2025-02-thorwallet) |
| Codehawks | Temple DAO | 6 / 100 Participants | Staking | 🟦 Solidity (EVM) |1 High, 1 Low | [Leaderboard](https://codehawks.cyfrin.io/c/2024-07-templegold/results?page=1) |
| Cantina | Morpho Vault | 8 / 561 Participants | Lending | 🟦 Solidity (EVM) |1 Medium | [Leaderboard](https://cantina.xyz/code/523e1540-f8c3-45ae-9c5d-b6d35d3a326c/overview/leaderboard) |
| Code4rena | TraitForge | 10 / 247 Participants | NFT, GameFi | 🟦 Solidity (EVM) |2 High, 5 Medium | [Leaderboard](https://code4rena.com/audits/2024-07-traitforge) |
| Cantina | Velvet | 11 / 624 Participants | DeFi, AMM | 🟦 Solidity (EVM) | 1 High, 3 Medium | [Leaderboard](https://cantina.xyz/code/8cf9c7a0-a7a6-446a-8577-1e2c254eb5a8/overview/leaderboard) |
| Cantina | Defi App | 11 / 361 Participants | yield farming | 🟦 Solidity (EVM) | 1 High, 1 Medium | [Leaderboard](https://cantina.xyz/code/1b64737c-1373-4ecf-a179-4cd0d7b0b232/overview/leaderboard) |
| Cantina | Yolo Games  | 14 / 250 Participants | GameFi | 🟦 Solidity (EVM) | 1 Medium | [Leaderboard](https://cantina.xyz/code/a2c3cc6a-e384-495f-9751-5d7e657bc219/overview/leaderboard) |
| Code4rena | Unistaker  | 15 / 54 Participants | Staking | 🟦 Solidity (EVM) | - | [Leaderboard](https://code4rena.com/reports/2024-02-uniswap-foundation) |
| Cantina | Goat Tech  | 15 / 244 Participants | GameFi, Staking | 🟦 Solidity (EVM) |1 High, 3 Medium | [Leaderboard](https://cantina.xyz/code/f214cf86-cc80-40c0-a70b-e9bb25d7ac80/overview/leaderboard) |
| Cantina | Bima  | 16 / 338 Participants | Lending | 🟦 Solidity (EVM) | 1 Medium | [Leaderboard](https://cantina.xyz/code/44d68da7-3cf4-4cec-a3f8-f0917062dac6/overview/leaderboard) |
| Cantina | Mev Commit  | 17 / 248 Participants | Network | 🟦 Solidity (EVM) | 1 High, 3 Medium | [Leaderboard](https://cantina.xyz/code/4ee8716d-3e0e-4f59-b90d-aa56bf3b484c/overview/leaderboard) |
| Cantina | Solayer Bridge  | 17 / 306 Participants | Bridge | 🟩 Solana (Rust) | 1 High, 3 Medium | [Leaderboard](https://cantina.xyz/code/0f543452-2076-438f-86ae-bbd6b065fffb/overview/leaderboard) |
| Code4rena | Panoptic  | 19 / 63 Participants | Perpetual | 🟦 Solidity (EVM) | 1 Medium | [Leaderboard](https://code4rena.com/audits/2024-04-panoptic) |
| Code4rena | Chakra  | 20 / 109 Participants | Settlement | 🟦 Solidity (EVM) | 2 High, 2 Medium | [Leaderboard](https://code4rena.com/audits/2024-08-chakra) |
| Code4rena | Vultisig  | 21 / 70 Participants | UniswapV3 Integration | 🟦 Solidity (EVM) | 2 Medium | [Leaderboard](https://code4rena.com/reports/2024-06-vultisig) |
| Code4rena | Althea Liquid Infrastructure  | 28 / 93 Participants | ERC20 | 🟦 Solidity (EVM) | 2 Medium | [Leaderboard](https://code4rena.com/audits/2024-02-althea-liquid-infrastructure) |


- [**Secure3**](https://app.secure3.io/zh/leaderboard?platform=s3)  
  - 6 × 🏆 Top 1, 10+ Top 3  
  - Total Findings: 4 High (1 SOLO), 20 Medium (11 SOLO)  
  
---

## 🏢 Private Engagement

### Taichi Audit

| Protocol | Provider | Description | Language | Critical/High | Medium | Low | Report Link|
|----------|---------|---------|---------|------|---------|------|---------|
| [LazyOtter](https://lazyotter.finance/) | Taichi Audit | yield farming | 🟦 Solidity (EVM) | 1 | 3 | - | - |
| [Lambo Win](https://lambo-win.gitbook.io/lambo.win) | Taichi Audit | Launchpad | 🟦 Solidity (EVM) | 0 | 3 | - | - |
| Private | Taichi Audit | Lending | � Solidity (EVM) | 3 | 7 | 8 | - |

### Cyfrin

| Protocol | Provider | Description | Language | Critical/High | Medium | Low | Report Link|
|----------|---------|---------|---------|------|---------|------|---------|
| Temple DAO Mitigation | CodeHawks | Staking | 🟦 Solidity (EVM) | 1 | 2 | 1 | Private Report |
| [Deriverse](https://deriverse.io/) | Cyfrin | DEX, Perpetual | 🟩 Solana (Rust) | 9 | 14 | 8 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2025-12-15-cyfrin-deriverse-dex-v2.0.pdf) |
| [Story IP Derivative Agent](https://www.story.foundation/) | Cyfrin | Agent | 🟦 Solidity (EVM) | 0 | 0 | 1 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-01-15-cyfrin-story-ip-derivative-agent-v2.1.pdf) |
| [Securitize SVM On/Off Ramp](https://www.securitize.io/) | Cyfrin | RWA | 🟩 Solana (Rust) | 1 | 1 | 5 | [Report](https://github.com/Cyfrin/cyfrin-audit-reports/blob/main/reports/2026-02-19-cyfrin-securitize-svm-on-off-ramp-v2.0.pdf) |
| Private | Cyfrin | RWA | 🟩 Solana (Rust) | 0 | 1 | 2 | - |
| Private | Cyfrin | RWA | 🟩 Solana (Rust) | 0 | 0 | 0 | - |
| Private | Cyfrin | RWA | 🟩 Solana (Rust) | 0 | 0 | 1 | - |

### Plainshift
| Protocol | Provider | Description | Language | Critical/High | Medium | Low | Report Link|
|----------|---------|---------|---------|------|---------|------|------|
| Private | Plainshift | ICO, Staking, Launchpad | 🟦 Solidity (EVM) | 11 | 20 | 9 | - |
| Private | Plainshift | ICO | 🟩 Solana (Rust) | 1 | 2 | 3 | - |

### Pashov Audit Group
| Protocol | Provider | Description | Language | Critical/High | Medium | Low | Report Link|
|----------|---------|---------|---------|------|---------|------|---------|
| HyperHypyer | Pashov Audit Group | Lending | 🟦 Solidity (EVM) | 6 | 9 | 11 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Hyperhyper-security-review_2025-03-30.pdf) |
| RipIt | Pashov Audit Group | Lottery | 🟦 Solidity (EVM) | 6 | 9 | 26 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/RipIt-security-review_2025-04-25.pdf) |
| [TokenLogic](https://www.tokenlogic.xyz/) | Pashov Audit Group | Yield | 🟦 Solidity (EVM) | 0 | 0 | 5 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/TokenLogic-security-review_2025-05-05.pdf)|
| [KittenSwap](https://kittenswap.finance/) | Pashov Audit Group | Swap, DEX | 🟦 Solidity (EVM) | 4 | 4 | 14 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/KittenSwap-security-review_2025-05-07.pdf)|
| Gacha | Pashov Audit Group | GameFi | 🟦 Solidity (EVM) | 1 | 4 | 12 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Gacha-security-review_2025-01-27.pdf)|
| [HyperStable](https://hyperstable.xyz/) | Pashov Audit Group | Stable Coin | 🟦 Solidity (EVM) | 0 | 1 | 3 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Hyperstable-security-review_2025-02-26.pdf)|
| [Bancor](https://bancor.network/) | Pashov Audit Group | DEX | 🟦 Solidity (EVM) | 0 | 1 | 6 | Private Report|
| [RegnuMaurum](https://raac.io/) | Pashov Audit Group | RWA | 🟦 Solidity (EVM) | 4 | 9 | 16 | Private Report|
| [Avon](https://www.avon.xyz/) | Pashov Audit Group | Lending | 🟦 Solidity (EVM) | 4 | 12 | 21 | Private Report|
| [Bancor](https://bancor.network/) | Pashov Audit Group | DEX | 🟦 Solidity (EVM) | 0 | 1 | 0 | Private Report|
| [Pump.fun](https://pump.fun/) | Pashov Audit Group | Launchpad | 🟩 Solana (Rust) | 0 | 0 | 3 | Private Report|
| [SXT](https://www.spaceandtime.io/) | Pashov Audit Group | UniswapV3 Integration | 🟦 Solidity (EVM) | 1 | 4 | 4 | Private Report|
| [Thrust](https://app.thrust.com/) | Pashov Audit Group | Launchpad | 🟩 Solana (Rust) | 3 | 3 | 2 | Private Report|
| [Pump.fun](https://pump.fun/) | Pashov Audit Group | Launchpad | 🟩 Solana (Rust) | 0 | 1 | 1 | Private Report|
| AlphaHype | Pashov Audit Group | HyperLiquid | 🟦 Solidity (EVM) | 1 | 3 | 3 | Private Report|
| [SQDGN](https://www.sqdgn.ai/) | Pashov Audit Group | ERC20 | 🟦 Solidity (EVM) | 0 | 0 | 2 | Private Report|
| [Ouroboros](https://www.ouroboros.finance/) | Pashov Audit Group | Launchpad | 🟦 Solidity (EVM) | 0 | 9 | 8 | Private Report|
| [Anthias](https://anthias.xyz/) | Pashov Audit Group | Router | 🟦 Solidity (EVM) | 0 | 1 | 4 | Private Report|
| [Tangent](https://www.tangent.finance/) | Pashov Audit Group | Lending | 🟦 Solidity (EVM) | 0 | 2 | 5 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Tangent-security-review_2025-10-30.pdf) |
| [Tangent](https://www.tangent.finance/) | Pashov Audit Group | Lending | 🟦 Solidity (EVM) | 0 | 0 | 3 | [Report](https://github.com/pashov/audits/blob/master/team/pdf/Tangent-security-review_2025-12-08.pdf) |
| [Pump.fun](https://pump.fun/) | Pashov Audit Group | Launchpad | 🟩 Solana (Rust) | 0 | 0 | 2 | Private Report|
| Zoop | Pashov Audit Group | Cross-chain | 🟦 Solidity (EVM) | 1 | 3 | 8 | Private Report|
| [Starkware](https://www.starkware.co/) | Pashov Audit Group | Smart Wallet | 🟪 Cairo | 0 | 0 | 3 | Private Report|
| SQD | Pashov Audit Group | staking | 🟦 Solidity (EVM) | 1 | 2 | 5 | Private Report|
| Private | Pashov Audit Group | Airdrop | 🟦 Solidity (EVM) | 0 | 0 | 5 | Private Report|
| Private | Pashov Audit Group | RWA | 🟦 Solidity (EVM) | 0 | 2 | 9 | Private Report|

### Yaudit(as guest auditor)
| Protocol | Provider | Description | Language | Critical/High | Medium | Low | Report Link|
|----------|---------|---------|---------|------|---------|------|---------|
| [Fira](https://www.fira.money/) | Yaudit | Lending | 🟦 Solidity (EVM) | 0 | 0 | 2 | Private Report |

### Burra Sec
| Protocol | Provider | Description | Language | Critical/High | Medium | Low | Report Link|
|----------|---------|---------|---------|------|---------|------|---------|
| [Zama](https://www.zama.org/) | Burra Sec | LayerZero | 🟦 Solidity (EVM) + 🟩 Solana (Rust) | 0 | 0 | 1 | - |
| [Zama](https://www.zama.org/) | Burra Sec | LayerZero | 🟦 Solidity (EVM) + 🟩 Solana (Rust) | 0 | 0 | 0 | - |

### Failsafe
| Protocol | Provider | Description | Language | Critical/High | Medium | Low | Report Link|
|----------|---------|---------|---------|------|---------|------|---------|
| [Virtuals-PR](https://www.virtuals.io/) | Failsafe | Launchpad | 🟦 Solidity (EVM) | 0 | 1 |1 | - |
| [Virtuals-PR](https://www.virtuals.io/) | Failsafe | Launchpad | 🟦 Solidity (EVM) | 0 | 0 |1 | - |
| [Virtuals-PR](https://www.virtuals.io/) | Failsafe | Launchpad | 🟦 Solidity (EVM) | - | - |- | - |
| [AZverse](https://www.azverse.xyz/en) | Failsafe | DEX | 🟦 Solidity (EVM) | 1 | 2 |1 | - |
| [Virtuals-PR](https://www.virtuals.io/) | Failsafe | Launchpad | 🟦 Solidity (EVM) | 0 | 1 | 2 | Private Report|


### Fuzzland
| Protocol | Provider | Description | Language | Critical/High | Medium | Low | Report Link|
|----------|---------|---------|---------|------|---------|------|---------|
| [vishwanetwork-btcvc](https://vishwanetwork.xyz/) | Fuzzland | cross-chain | 🟦 Solidity (EVM) | 2 | 0 | 0 | - |
| [vishwanetwork-sbtcvc](https://vishwanetwork.xyz/) | Fuzzland | cross-chain | 🟧 Move (Rust) | 1 | 0 | 1 | - |
| [vishwanetwork-sbtcvc](https://vishwanetwork.xyz/) | Fuzzland | cross-chain | 🟧 Move (Rust) | 1 | 1 | 0 | - |
| [Tenbin](https://tenbin.io/) | Fuzzland | Yield, ERC4626 | 🟦 Solidity (EVM) | 4 | 2 | 2 | - |
| ThetaFunction RFQ | Fuzzland | RFQ | 🟦 Solidity (EVM) | 2 | 1 | 2 | - |

### Undisclosed Clients

Note: 5 additional Solana audits under NDA

| Protocol | Provider | Description | Language | Critical/High | Medium | Low | Report Link|
|----------|---------|---------|---------|------|---------|------|---------|
| Private | Undisclosed Clients | CLMM | 🟩 Solana (Rust) | private | private |private | - |
| Private | Undisclosed Clients | Launchpad | 🟩 Solana (Rust) | private | private |private | - |
| Private | Undisclosed Clients | Prediction Market | 🟩 Solana (Rust) | private | private |private | - |
| Private | Undisclosed Clients | DarkPool | 🟩 Solana (Rust) | private | private |private | - |
| Private | Undisclosed Clients | Dex Router | 🟩 Solana (Rust) | private | private |private | - |

## 🧠 Research & Write‑ups

- **SPL vs Token2022: From Mint to Account**

  A technical comparison of SPL Token and Token2022—from mint/account layouts to ATA creation—highlighting program IDs, extensions, and real initialization flows.
  ↳ https://taichiaudit.com/blog/solana-security-series-4

- **Why Anchor Accounts Go Stale After CPI (and When to Reload)**

  Detailed analysis of why Anchor accounts go stale after CPI and when to reload.
  
  ↳ https://taichiaudit.com/blog/solana-security-series-3

- **How `init` and `init_if_needed` work under the hood & associated token account griefing attack (Solana / Anchor)**

  Deep dive into how Anchor’s account initialization mechanisms behave at runtime and subtle griefing/DoS patterns resulting from pre‑created associated token accounts.  
  ↳ https://taichiaudit.com/blog/solana-security-series-2

- **Pre‑Funding DoS in Solana: Breaking `create_account` with Non‑Zero Lamports**

  Analysis of how Solana’s account creation semantics can be exploited in DoS patterns via pre‑funded accounts.  
  ↳ https://taichiaudit.com/blog/solana-security-series-1

- **Understanding Liquidity: Uniswap v2 vs v3**

  Comparative technical exploration of concentrated liquidity mechanics and implications for DeFi LPs on Uniswap.  
  ↳ https://taichiaudit.com/blog/understanding-liquidity-uniswap-v2-v3

- **YouTube: Solidity / Blockchain Security Talk**

  Video covering [Deep Dive into Inflation Attacks]  
  ↳ https://www.youtube.com/watch?v=arRMN_tPu3c

---