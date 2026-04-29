---
description: How fees work on 7.Exchange.
---

# Fees

7.Exchange is transparent about costs. Every fee is displayed in the route preview before you confirm a swap. There are no hidden charges.

## Fee types

A swap on 7.Exchange may include the following costs:

### Routing fee

A small service fee charged by 7.Exchange on each transaction. This fee supports platform development and infrastructure. The exact percentage varies by route and is always shown in the fee breakdown.

### Network gas fees

Every on-chain transaction requires gas. Gas fees go to the blockchain network validators, not to 7.Exchange. Gas costs depend on:

- Which chain you're transacting on
- Current network congestion
- Transaction complexity (multi-step routes use more gas)

### Bridge fees

Cross-chain swaps use bridge protocols to transfer assets between chains. Each bridge charges its own fee for this service. Bridge fees vary by provider, chain pair, and transfer amount.

### DEX and liquidity provider fees

When your route involves a swap on a decentralized exchange, the DEX and its liquidity providers charge a fee (typically a small percentage of the trade). This is standard across all DEXs and is built into the quoted output.

## How to see fees

Every route in the swap interface shows total fees. Click **Fee Breakdown** on any route to see a detailed split of where each cost comes from.

The **Output** number shown for each route is always net all fees have already been deducted. The amount displayed is what you should expect to receive.

## Fee comparison across routes

Different routes for the same swap can have different fee structures. A route through Bridge A might charge a higher bridge fee but offer lower slippage, resulting in a better net output than a route through Bridge B with a lower bridge fee but worse execution.

This is why 7.Exchange ranks routes by net output rather than by lowest fee the cheapest route isn't always the best route.

{% hint style="info" %}
You can sort routes by **Lowest Fee** if minimizing cost is your priority, but the **Highest Output** sort (default) typically delivers the best overall result.
{% endhint %}

## Referral fee sharing

If you were referred to 7.Exchange through an affiliate link, a portion of the routing fee may be shared with the referrer. This does not increase your cost the referral share comes from the platform's fee, not from your output.

For more on how this works, see [Referral Program](../features/referral-program.md).
