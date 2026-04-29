---
description: Swap tokens across chains through a single interface.
---

# Cross-Chain Swaps

Cross-chain swaps are the core feature of 7.Exchange. Swap any supported token on any supported chain to any other supported token on any other chain all from one interface.

## How it works

A cross-chain swap on 7.Exchange combines bridging and swapping into a single flow. Instead of manually bridging an asset to the destination chain and then swapping it on a local DEX, the routing engine handles the entire path.

Depending on the pair, a cross-chain swap may involve:

- A direct bridge transfer (if the same token is supported on both chains)
- A swap on the source chain, bridge, then delivery on the destination chain
- A bridge transfer followed by a swap on the destination chain
- A combination of all three (swap, bridge, swap)

You don't need to think about these steps. The routing engine evaluates all possible paths and presents the best options ranked by net output.

## Same-chain swaps

7.Exchange also supports same-chain swaps. If your source and destination tokens are on the same chain, the engine routes through integrated DEXs and liquidity sources on that chain.

Same-chain and cross-chain swaps use the same interface and the same routing logic.

## Execution time

Same-chain swaps typically confirm within seconds. Cross-chain swaps take longer because they depend on:

- Block finality requirements on the source chain
- Bridge protocol processing time
- Block confirmation on the destination chain

Most cross-chain swaps complete within a few minutes. Some combinations (particularly those involving chains with long finality times) may take longer. The estimated time is always shown in the route details before you confirm.

## Recipient address

By default, swapped tokens are delivered to your connected wallet on the destination chain. If you need to receive tokens at a different address, you can enter a custom recipient address in the swap interface.

{% hint style="warning" %}
Double-check the recipient address and chain before confirming. Cross-chain transactions are irreversible. Tokens sent to an incorrect address cannot be recovered.
{% endhint %}

## Limits

7.Exchange does not impose minimum or maximum swap amounts. However, practical limits exist:

- **Small swaps** may not be cost-effective if gas and bridge fees consume a large portion of the swap amount.
- **Large swaps** may experience higher slippage if the available liquidity on the best route is insufficient for the full amount.

The route preview always shows the net output so you can judge whether the trade is worth executing.
