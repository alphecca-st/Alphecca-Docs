---
icon: circle-pause
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

# Pause Token

Pause all token activities including buying, selling, and transfers.

{% hint style="success" %}
#### [https://alphecca.io/pause/binance](https://alphecca.io/pause/binance)
{% endhint %}

## How to Pause Token

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Token Address

Select the token you want to pause from the dropdown. Only Alphecca-created tokens with pause enabled will be displayed.

{% hint style="info" %}
Only the token owner can pause. Tokens with renounced ownership or disabled pause cannot be paused
{% endhint %}

### Step 3: Check Current Status

The current pause status of the token is displayed. 'Active' means normal trading is possible, 'Paused' means all transfers are blocked.

### Step 4: Pause or Unpause

Click the 'Pause Token' or 'Unpause Token' button depending on the current status and approve the transaction in your wallet.

{% hint style="warning" %}
When paused, all token activities including buying, selling, and transfers are blocked. Use only for emergencies or security issues.
{% endhint %}

***

### Frequently Asked Questions

#### What is token pause?

Token pause is a feature that temporarily halts all transfer activities of a token. When paused, all token movements including buying, selling, and wallet-to-wallet transfers are blocked.

#### Who can pause a token?

Only the token owner can pause. The pausable feature must also be enabled when the token was created. Tokens with renounced ownership or disabled pause cannot be paused.

#### What happens when paused?

All token transfers are blocked. Buying/selling on DEX is disabled, wallet-to-wallet transfers are disabled, and LP add/remove is disabled.

#### When should I use pause?

Use it for emergencies or security issues. For example, when suspecting a hack, discovering contract vulnerabilities, or detecting abnormal large-scale selling, you can temporarily halt trading to minimize damage.

#### Can I unpause?

Yes. The token owner can unpause at any time. Once unpaused, all token activities resume normally.

#### How much does it cost?

Free. You only pay for gas fees.
