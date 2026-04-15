---
description: What we've shipped and what's coming next.
---

# Roadmap

This roadmap reflects the current development plan for 7.Exchange. Timelines are targets, not guarantees — priorities may shift based on market conditions, security considerations, and community feedback.

## Phase 1 — Platform Launch (Q2 2026)

Cross-chain swap aggregation engine live, routing across EVM and non-EVM chains. Multi-provider quote evaluation with net-output ranking — every route scored by final received amount after gas, bridge fees, slippage, and MEV exposure. Multiple bridge and cross-chain transport integrations. Aggregated liquidity from hundreds of DEXs, LPs, and on-chain services. Wallet integrations via standardized connectors across EVM, Solana, Bitcoin, Sui, and Tron ecosystems.

Quote authentication with single-use execution payloads — each quote is unique, time-bound, and cryptographically tied to the requesting session. Custom slippage tolerance and route preference controls. Referral and affiliate tracking system with dashboard analytics.

Non-custodial architecture — 7.Exchange never takes custody of user funds at any point in the execution pipeline.

**Status: Live**

## Phase 2 — Token & Developer Platform (Q3 2026)

7.Exchange native token launch with protocol-level utility: fee discounts, staking mechanisms, and governance participation.

Public REST API with authenticated endpoints for quote retrieval, route computation, and transaction construction. TypeScript SDK for programmatic integration — designed for wallets, trading terminals, portfolio dApps, and institutional desks. Affiliate API enabling partners to embed 7.Exchange routing with revenue-share tracking.

Developer documentation, integration guides, and sandbox environment.

**Status: In development**

## Phase 3 — Advanced Execution Modes (Q4 2026)

On-chain limit order engine — price-targeted orders held off-chain with authenticated execution triggered when market conditions are met. No continuous user signing required.

Direct Swap — wallet-less swap execution for supported pairs. Users provide a receiving address and send funds from any source (hardware wallet, CEX withdrawal, any on-chain wallet) without connecting to the platform.

Aggregated perpetual DEX routing — unified interface for opening, managing, and closing perpetual positions across multiple on-chain venues. Cross-chain margin routing without manual network switching.

Unified transaction history across swaps, limit orders, sends, and perpetual positions.

**Status: Planned**

## Phase 4 — Protocol Contracts & On-Chain Infrastructure (H1 2027)

Deployment of the 7.Exchange Diamond Router — modular, upgradeable smart contract architecture for on-chain route execution and settlement. Completion of pre-deployment bug bounty program followed by independent third-party security audits.

On-chain fee accrual and distribution mechanism integrated with the native token. Hybrid execution model: smart contract routing on deployed chains with provider-API fallback for maximum coverage.

Published audit reports and verified contract addresses.

**Status: Planned**

## Phase 5 — Protocol Expansion (H2 2027 and beyond)

Extended Direct Swap coverage across all supported chains. Governance framework activation for protocol-level decision making. Advanced order types: DCA (dollar-cost averaging), TWAP (time-weighted average price), and conditional execution.

Embeddable swap widget for third-party dApps and websites. Cross-chain portfolio aggregation and analytics. Continued expansion of bridge and liquidity provider integrations based on performance metrics and community governance.

**Status: Planned**

---

{% hint style="info" %}
This roadmap is updated as milestones are reached. For real-time updates, follow [7.Exchange on X](https://x.com/7exchangeDeFi) or join the [Discord](https://discord.gg/your-server).
{% endhint %}
