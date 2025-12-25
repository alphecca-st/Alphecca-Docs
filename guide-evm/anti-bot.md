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

Limit transactions per block to defend against sniping bots and sandwich attacks.

{% hint style="success" %}
#### [https://alphecca.io/anti-bot/binance](https://alphecca.io/anti-bot/binance)
{% endhint %}

## How to Use Anti Bot Settings

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Token Address

Select the token contract address you want to configure Anti Bot settings for.

{% hint style="warning" %}
This feature is only available for tokens created through Alphecca. Only the token creator can modify settings.
{% endhint %}

### Step 3: Configure Anti Bot Settings

<table><thead><tr><th width="230">Field</th><th>Description</th></tr></thead><tbody><tr><td>Max Tx Per Block</td><td>Maximum transactions per wallet per block <br>(0 = no limit)</td></tr><tr><td>Active Duration</td><td>How long this feature stays active (hours) <br>(0 = permanent)</td></tr></tbody></table>

{% hint style="info" %}
Anti Bot limits transaction frequency per block, effectively defending against sandwich attacks and preventing bots from exploiting trades.
{% endhint %}

{% hint style="info" %}
Anti-Bot works correctly regardless of whether swap aggregators (wallet apps, 1inch, etc.) are used.
{% endhint %}

### Step 4: Save Settings

Click the 'Set Anti-Bot' button and approve the transaction in your wallet.

{% hint style="info" %}
A one-time fee is charged only during initial setup. After that, all changes are completely free.
{% endhint %}

***

### Frequently Asked Questions

#### How much does it cost to change Anti-Bot settings?

A one-time fee is charged only during initial setup. After that, all changes are completely free.

#### Can I disable Anti-Bot after enabling it?

Yes. Set Max Tx Per Block to 0 to remove transaction limits.

#### When do Anti-Bot settings take effect?

Settings take effect immediately after the transaction is confirmed.

#### What happens when Active Duration expires?

Anti-Bot restrictions are automatically lifted. You can set a new duration anytime to reactivate.
