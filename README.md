# Jesjupyter

Blockchain Security Researcher & Smart Contract Auditor  
Specialties: 🟦 Solidity (EVM) · 🟩 Solana (Rust) · 🟪 Cairo · 🟧 Move (Learning)
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

## 🏢 Private Audits

- **Pashov Audit Group** — 20+ audits  
  **Languages:** 15+ Solidity (EVM), 4 Solana, 1 Cairo  
  **Domains:** Launchpad, RWA, Lending, Cross-chain

- **Plainshift** — multiple audits  
  **Languages:** Solidity (EVM), Solana  
  **Domains:** Launchpad, Staking

- **Cyfrin** — 1 audit  
  **Languages:** Solana  
  **Domains:** DEX, PERP

- **Yaudit (as guest auditor)** — 1 audit  
  **Languages:** Solidity (EVM)  
  **Domains:** Lending

- **Confidential / Undisclosed Clients** — multiple audits  
  **Languages:** Solana  
  **Domains:** Launchpad, DEX
---

## 🏆 Contest Performance
- [**Mainstream Audit Contest Platforms**](https://audits.sherlock.xyz/watson/jesjupyer): 33 High, 61 Medium  

| Platform | Protocol | Rank | Findings | Link |
|----------|---------|------|---------|------|
| Cantina | arcadexyz/arcade-protocol |  🏆 **1st** | 2 Medium (1 SOLO) | [Leaderboard](https://cantina.xyz/code/c2e31b04-fbb2-4355-80ef-141d58b6e0cc/overview/leaderboard) |
| Cantina | Coinbase Spend-permission | 🏆 **1st** | — | [Leaderboard](https://cantina.xyz/code/6837e02a-0a87-4577-a047-4e1ea71cff01/overview/leaderboard) |
| Codehawks | OneWorld | 🏆 **1st** | 1 High, 1 Medium | [Leaderboard](https://codehawks.cyfrin.io/contests/cm2mxcaoo000112pvkwt2nb8u) |
| Cantina | pegasus(usual) | 🥈 **2nd** | 1 Medium | [Leaderboard](https://cantina.xyz/code/31a752e3-8ece-49b3-a9ee-d7294c659340/overview/leaderboard) |
| Code4rena | Badger | 🥈 **2nd** | 1 Medium | [Leaderboard](https://code4rena.com/audits/2024-06-ebtc-zap-router) |
| Cantina | Coinbase EIP7702Proxy | 🥈 **2nd** | 1 Medium | [Leaderboard](https://cantina.xyz/code/b0a948cd-c861-4807-b36e-d680d82598bf/overview/leaderboard) |
| Cantina | Royco | 🥉 **3rd** | 7 High, 6 Medium (Most findings, 1 SOLO) | [Leaderboard](https://cantina.xyz/code/fadb5a8f-e39c-4a6b-89f6-a03858bb8602/overview/leaderboard) |

- [**Secure3**](https://app.secure3.io/zh/leaderboard?platform=s3)  
  - 6 × 🏆 Top 1, 10+ Top 3  
  - Total Findings: 4 High (1 SOLO), 20 Medium (11 SOLO)  
  
---

## 🧠 Research & Write‑ups

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