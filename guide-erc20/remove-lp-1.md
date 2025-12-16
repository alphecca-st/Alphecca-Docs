---
icon: shield-virus
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Anti-Whale Settings

Limit max buy, sell, and holdings to prevent price manipulation from large trades.

{% hint style="success" %}
#### [https://alphecca.io/anti-whale/binance](https://alphecca.io/anti-whale/binance)
{% endhint %}

## How to Use Anti Whale Settings

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Token Address

Select the token contract address you want to configure Anti Whale settings for.

{% hint style="warning" %}
This feature is only available for tokens created through Alphecca. Only the token owner can modify settings.
{% endhint %}

### Step 3: Configure Anti Whale Settings

<table><thead><tr><th width="192">Field</th><th>Description</th></tr></thead><tbody><tr><td>Max Buy Amount</td><td>Maximum tokens per buy transaction (0 = no limit)</td></tr><tr><td>Max Sell Amount</td><td>Maximum tokens per sell transaction (0 = no limit)</td></tr><tr><td>Wallet Limit</td><td>Maximum tokens a wallet can hold (0 = no limit)</td></tr><tr><td>Buy Cooldown</td><td>Minimum time between buys (minutes) (0 = no limit)</td></tr><tr><td>Sell Cooldown</td><td>Minimum time between sells (minutes) (0 = no limit)</td></tr><tr><td>Active Duration</td><td>How long this feature stays active (days)  (0 = permanent)</td></tr></tbody></table>

{% hint style="info" %}
Buy/Sell limits and cooldowns are based on liquidity pool transactions. When using Alphecca's Create Liquidity Pool page, the pool address is automatically registered to the token contract and Buy/Sell limits and cooldowns are applied.
{% endhint %}

{% hint style="info" %}
Anti Whale protects your community by preventing large-scale market manipulation and maintaining price stability.
{% endhint %}

{% hint style="info" %}
Buy/Sell limits and cooldowns work correctly regardless of whether swap aggregators (wallet apps, 1inch, etc.) are used.
{% endhint %}

### Step 4: Save Settings

Click the 'Set Anti-Whale' button and approve the transaction in your wallet.

{% hint style="info" %}
A one-time fee is charged only during initial setup. After that, all changes are completely free.
{% endhint %}

***

### Frequently Asked Questions

#### How much does it cost to change Anti-Whale settings?

A one-time fee is charged only during initial setup. After that, all changes are completely free.

#### Can I disable Anti-Whale after enabling it?

Yes. Set all limits to 0 to remove restrictions.

#### When do Anti-Whale settings take effect?

Settings take effect immediately after the transaction is confirmed.

#### What happens when Active Duration expires?

Anti-Whale restrictions are automatically lifted. You can set a new duration anytime to reactivate.

#### Why aren't Buy/Sell limits working?

Buy/Sell limits only apply to trades through liquidity pools. Make sure you have created a liquidity pool through Alphecca's Create Liquidity Pool page for the limits to take effect.
