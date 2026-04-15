---
description: Walk through your first cross-chain swap on 7.Exchange.
---

# Your First Swap

This guide walks through a complete swap from start to finish.

## 1. Connect your wallet

If you haven't already, connect your wallet by clicking **Connect Wallet** in the navigation bar. See [Connect Your Wallet](connect-your-wallet.md) for details.

## 2. Select your source token

On the swap interface, the **From** field is where you select what you're swapping away.

- Click the token selector to open the token and chain picker.
- Select the **chain** your funds are on.
- Select the **token** you want to swap.
- Enter the **amount** you want to swap, or click **Max** to use your full balance.

## 3. Select your destination token

In the **To** field, select the token and chain you want to receive.

This can be on the same chain (a simple swap) or a different chain (a cross-chain swap). The routing engine handles both the same way.

## 4. Review routes

Once both tokens and an amount are set, 7.Exchange fetches quotes from all available providers and displays the results.

Each route shows:

- **Output** — The estimated amount you'll receive
- **Fee** — Total cost including gas, bridge fees, and routing fee
- **ETA** — Estimated time to completion
- **Provider** — Which bridge or DEX is used for each step

The recommended route is highlighted by default. You can sort routes by **Highest Output**, **Fastest**, or **Lowest Fee** depending on your priority.

Routes include tags like **Recommended**, **Fastest**, and **Lowest Fee** to help you compare at a glance.

{% hint style="info" %}
Quotes refresh automatically. The countdown timer shows when the next refresh occurs. You can also manually refresh at any time.
{% endhint %}

## 5. Adjust settings (optional)

Click the settings icon to customize:

- **Slippage tolerance** — The maximum price deviation you'll accept. Default is usually sufficient, but you can adjust for volatile tokens.
- **Excluded providers** — Remove specific exchanges or bridges from consideration if you prefer not to route through them.

## 6. Confirm and execute

Once you've selected a route:

1. Click **Swap** to lock the quote.
2. Review the **Quote Preview** — verify the tokens, amounts, and route details.
3. Click **Execute Quote**.
4. Your wallet will prompt you to sign the transaction. Review and approve it.

After signing, the execution tracker appears showing real-time progress of your swap.

## 7. Track your transaction

The execution tracker shows the current status of your swap:

| Status | Meaning |
|---|---|
| **Pending** | Transaction submitted, waiting for confirmation |
| **In progress** | Swap is executing across chains |
| **Completed** | Funds delivered to your destination wallet |
| **Failed** | Transaction did not complete (see [FAQ](../resources/faq.md) for troubleshooting) |

For cross-chain swaps, execution may take anywhere from a few seconds to several minutes depending on the chains involved and network conditions.

## Tips

- **Start with a small amount** if this is your first time using the platform or swapping on an unfamiliar chain.
- **Check your destination wallet** — if you're swapping to a different chain ecosystem (e.g., EVM to Solana), make sure the correct destination wallet is connected.
- **Quotes are time-sensitive** — if a quote expires before you execute, the system will fetch a fresh one automatically.
