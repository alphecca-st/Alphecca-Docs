---
icon: circle-pause
---

# Pause Token (EVM)

This guide walks you through pausing token operations on EVM chains with Alphecca Tools.

{% hint style="info" %}
#### Tool Page

* Link : [Pause Token on Ethereum](https://alphecca.io/en/pause/ethereum)
* Link : [Pause Token on Binance Smart Chain](https://alphecca.io/en/pause/binance)
* Link : [Pause Token on Base](https://alphecca.io/en/pause/base)
* Link : [Pause Token on Polygon](https://alphecca.io/en/pause/polygon)
* Link : [Pause Token on Avalanche](https://alphecca.io/en/pause/avalanche)
* Link : [Pause Token on Monad](https://alphecca.io/en/pause/monad)
* Link : [Pause Token on Arbitrum](https://alphecca.io/en/pause/arbitrum)
* Link : [Pause Token on Optimism](https://alphecca.io/en/pause/optimism)
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

## Frequently Asked Questions

### What is token pause?

Token pause is a feature that temporarily halts all transfer activities of a token. When paused, all token movements including buying, selling, and wallet-to-wallet transfers are blocked.

### Who can pause a token?

Only the token owner can pause. The pausable feature must also be enabled when the token was created. Tokens with renounced ownership or disabled pause cannot be paused.

### What happens when paused?

All token transfers are blocked. Buying/selling on DEX is disabled, wallet-to-wallet transfers are disabled, and LP add/remove is disabled.

### When should I use pause?

Use it for emergencies or security issues. For example, when suspecting a hack, discovering contract vulnerabilities, or detecting abnormal large-scale selling, you can temporarily halt trading to minimize damage.

### Can I unpause?

Yes. The token owner can unpause at any time. Once unpaused, all token activities resume normally.

### How much does it cost?

Free. You only pay for gas fees.
