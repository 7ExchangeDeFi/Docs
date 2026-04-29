---
description: Embeddable cross-chain swap interface for websites and dApps coming soon.
---

# Widget

{% hint style="info" %}
The 7.Exchange Widget is under development and planned for Q3 2026. This page will be updated with installation instructions, customization options, and code examples at launch.
{% endhint %}

## What the widget will provide

A drop-in swap interface that partners and dApps can embed directly into their products. Users swap cross-chain without leaving the host site, powered by the same routing engine and execution pipeline as the main 7.Exchange app.

## Planned capabilities

- **Embeddable React component** with a single script tag or npm install
- **Customizable theming** match your product's colors, fonts, and layout
- **Token and chain restrictions** limit available tokens or chains to fit your use case
- **Affiliate attribution** automatic referral fee tracking tied to your partner integration key
- **Full routing access** same multi-provider quote evaluation and net-output ranking as the main app
- **Non-custodial** user funds never pass through the widget host or 7.Exchange

## Use cases

- **Wallet apps** let users swap cross-chain without leaving the wallet
- **DeFi dashboards** add swap functionality alongside portfolio and analytics tools
- **NFT marketplaces** enable buyers to pay with any token on any chain
- **Token project sites** let users buy your token directly from your homepage

## How it will work

```html
<!-- Example embed (final API may differ) -->
<div id="7exchange-widget"></div>
<script src="https://widget.7.exchange/embed.js"></script>
<script>
  SevenExchange.init({
    containerId: '7exchange-widget',
    partnerId: 'your-partner-id',
    theme: 'dark',
    defaultSourceChain: 'ethereum',
    defaultDestinationChain: 'arbitrum'
  });
</script>
```

The widget will also be available as an npm package for React-based integrations:

```bash
npm install @7exchange/widget
```

```jsx
import { SwapWidget } from '@7exchange/widget';

function App() {
  return (
    <SwapWidget
      partnerId="your-partner-id"
      theme="dark"
    />
  );
}
```

{% hint style="warning" %}
The code examples above are illustrative and subject to change. Final implementation details will be published at launch.
{% endhint %}

## Early access

If you're building a product and want to integrate the widget before the public launch, reach out at [contact@7.exchange](mailto:contact@7.exchange).