---
icon: fire
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

# Burn LP Token

**Burn LP tokens to lock liquidity and build market trust.**

{% hint style="success" %}
#### [https://alphecca.io/burn-lp](https://alphecca.io/burn-lp)
{% endhint %}

## How to Burn LP Token

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select LP Token

Select the V2 LP token you want to burn from the dropdown. Your available LP tokens will be displayed.

{% hint style="info" %}
LP token burning is only supported for V2 pools. V3 positions are in NFT format and require separate management.
{% endhint %}

### Step 3:  Set Burn Amount

Enter the amount of LP tokens to burn. You can use the slider or percentage buttons (25%, 50%, 75%, 100%).

{% hint style="warning" %}
LP token burning is irreversible. The liquidity corresponding to burned LP tokens will be permanently locked and can no longer be withdrawn.
{% endhint %}

### Step 4: Set Fee Tier (V3 Only)

Select a fee tier: 0.01% / 0.05% / (0.25%, 0.30%) / 1.00%

{% hint style="info" %}
Lower fee tiers mean less cost for traders but smaller rewards for liquidity providers. The pool creator earns rewards proportional to this fee rate from every trade.
{% endhint %}

### Step 5: Burn LP Token

Click the 'Burn LP Token' button and approve the transaction in your wallet..

{% hint style="info" %}
**Required Transaction Approvals:**

* 1x LP Token Approve
* 1x LP Token Burn
{% endhint %}

{% hint style="info" %}
The token approval (Approve) transaction is only required once per LP token. After that, only 1 transaction is needed.
{% endhint %}

***

### Frequently Asked Questions

#### What is LP token burning?

LP token burning permanently removes LP tokens, making it impossible to withdraw the corresponding liquidity. Burned LP tokens are sent to the 0xdead address and locked forever.

#### Why burn LP tokens?

<table><thead><tr><th width="217"> Purpose</th><th>Description</th></tr></thead><tbody><tr><td>Rug Pull Prevention</td><td>Prove liquidity cannot be removed to build investor trust</td></tr><tr><td>Project Credibility</td><td>Demonstrate long-term commitment to the market</td></tr><tr><td>Token Value Protection</td><td>Ensure trading stability with permanently locked liquidity</td></tr></tbody></table>

#### Can I burn V3 NFT positions?

No. LP token burning is currently only supported for V2 pools. V3 positions exist as NFTs, each with unique price ranges and liquidity, requiring separate management methods.

#### Can I recover liquidity after burning?

No. LP token burning is completely irreversible. The liquidity corresponding to burned tokens is permanently locked in the pool and cannot be withdrawn by any means.

#### Can I burn only a portion?

Yes. You can burn only a portion of your LP tokens while keeping the rest. Use the slider or percentage buttons to select the amount to burn.<br>

#### What's the difference between burning and removing liquidity?

<table><thead><tr><th width="177"> Action</th><th>Result</th></tr></thead><tbody><tr><td>Remove Liquidity</td><td>Return LP tokens and receive back your deposited token pair</td></tr><tr><td>Burn LP Token</td><td>LP tokens are permanently destroyed and liquidity is locked forever in the pool</td></tr></tbody></table>
