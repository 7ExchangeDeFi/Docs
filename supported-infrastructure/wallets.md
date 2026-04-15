---
description: Supported wallets on 7.Exchange.
---

# Wallets

7.Exchange supports wallets across multiple blockchain ecosystems. You can connect one or more wallets simultaneously to trade across different chain types.

## Supported wallets by ecosystem

| Ecosystem | Supported Wallets |
|---|---|
| **EVM** | MetaMask, Trust Wallet, Rabby, Coinbase Wallet, Rainbow, and any WalletConnect-compatible wallet |
| **Solana** | Phantom, Solflare |
| **Bitcoin** | Xverse, Leather |
| **Sui** | Sui Wallet |
| **Tron** | TronLink |

This list reflects commonly used wallets. Additional wallets may work if they support standard connection protocols (WalletConnect for EVM, Wallet Standard for Solana).

## Multi-wallet support

You can connect wallets from different ecosystems at the same time. This is required when swapping between ecosystem types — for example, swapping an EVM token to a Solana token requires both an EVM wallet and a Solana wallet to be connected.

The swap interface automatically detects which connected wallet to use based on the source and destination chains you've selected.

## Choosing a recipient wallet

By default, swapped tokens are delivered to your connected wallet on the destination chain. You can enter a custom recipient address if you want tokens delivered to a different wallet.

## Hardware wallets

Hardware wallets (Ledger, Trezor) work with 7.Exchange when connected through a compatible software wallet. For example, connecting MetaMask with a Ledger hardware wallet lets you sign transactions with your Ledger while interacting with the 7.Exchange interface.

## Wallet security

{% hint style="warning" %}
7.Exchange will never ask for your private keys or seed phrase. Connecting your wallet only grants the interface permission to read your address and request transaction signatures. It does not give 7.Exchange access to move your funds.
{% endhint %}

For more on connecting and managing wallets, see [Connect Your Wallet](../getting-started/connect-your-wallet.md).
