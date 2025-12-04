---
icon: shield-dog
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

# Anti-Bot Settings

**Withdraw liquidity and remove your token’s LP.**

{% hint style="success" %}
#### [https://alphecca.io/anti-bot/binance](https://alphecca.io/anti-bot/binance)
{% endhint %}

## How to Use Anti Bot Settings

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Token Address

Select the token contract address you want to configure Anti Bot settings for.

{% hint style="warning" %}
This feature is only available for tokens created through Alphecca. Only the token owner can modify settings.
{% endhint %}

### Step 3: Configure Anti Bot Settings

| Field            | Description                                              |
| ---------------- | -------------------------------------------------------- |
| Max Tx Per Block | Maximum transactions per wallet per block (0 = no limit) |
| Active Duration  | How long this feature stays active (hours)               |

{% hint style="info" %}
Anti Bot limits transaction frequency per block, effectively defending against sandwich attacks and preventing bots from exploiting trades.
{% endhint %}

### Step 4: Save Settings

Click the 'Update Anti Bot' button and approve the transaction in your wallet.

***

### Frequently Asked Questions

#### How much does it cost to change Anti Bot settings?

A one-time fee is charged only during initial setup. After that, all changes are completely free.

#### Can I disable Anti Bot after enabling it?

Yes. Set Max Tx Per Block to 0 to remove transaction limits.

#### When do Anti Bot settings take effect?

Settings take effect immediately after the transaction is confirmed.

#### What happens when Active Duration expires?

Anti Bot restrictions are automatically lifted. You can set a new duration anytime to reactivate.
