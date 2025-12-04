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

**Withdraw liquidity and remove your token’s LP.**

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

| Field             | Description                                        |
| ----------------- | -------------------------------------------------- |
| Max Buy Amount    | Maximum tokens per buy transaction (0 = no limit)  |
| Max Sell Amount   | Maximum tokens per sell transaction (0 = no limit) |
| Max Wallet Amount | Maximum tokens a wallet can hold (0 = no limit)    |
| Buy Cooldown      | Minimum time between buys (seconds)                |
| Sell Cooldown     | Minimum time between sells (seconds)               |
| Active Duration   | How long this feature stays active (hours)         |

{% hint style="info" %}
Anti Whale protects your community by preventing large-scale market manipulation and maintaining price stability.
{% endhint %}

### Step 4: Save Settings

Click the 'Update Anti Whale' button and approve the transaction in your wallet.

***

### Frequently Asked Questions

#### How much does it cost to change Anti Whale settings?

A one-time fee is charged only during initial setup. After that, all changes are completely free.

#### Can I disable Anti Whale after enabling it?

Yes. Set all limits to 0 to remove restrictions.

#### When do Anti Whale settings take effect?

Settings take effect immediately after the transaction is confirmed.

#### What happens when Active Duration expires?

Anti Whale restrictions are automatically lifted. You can set a new duration anytime to reactivate.

#### Why aren't Buy/Sell limits working?

Buy/Sell limits only apply to trades through liquidity pools. Make sure you have created a liquidity pool through Alphecca's Create Liquidity Pool page for the limits to take effect.
