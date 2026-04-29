---
description: Swap without connecting a wallet coming soon.
---

# Direct Swap

{% hint style="info" %}
Direct Swap is under development. This page describes the planned feature. Follow our updates on [X](https://x.com/7exchangeDeFi) and [Discord](https://discord.gg/your-server) for launch announcements.
{% endhint %}

Direct Swap will allow you to execute swaps without connecting a wallet to 7.Exchange.

## How it will work

1. Select your source and destination token, chain, and amount.
2. Enter your **receiving address** the wallet where you want the output delivered.
3. 7.Exchange generates a **deposit address** with an amount and expiration window.
4. Send the exact amount to the deposit address from any source your own wallet, a hardware wallet, a CEX withdrawal, or any application that can send crypto.
5. The swap executes automatically.
6. Output is delivered to your receiving address.

No wallet connection, no transaction signing through the app, no approvals.

## Why it matters

Direct Swap is designed for users who:

- Use hardware wallets that don't support dApp connections
- Want to swap directly from a CEX withdrawal
- Prefer not to connect their wallet to any third-party interface
- Are on chains or wallet types that don't support standard dApp interaction

## Supported pairs

Direct Swap will initially be available for a subset of supported pairs where the underlying bridge providers support deposit-based execution. Coverage will expand over time.

## What to expect

- A refund address option in case the swap cannot be completed
- Minimum amounts to cover execution costs
- Expiration windows on deposit addresses deposits sent after expiration may be delayed or require manual recovery
