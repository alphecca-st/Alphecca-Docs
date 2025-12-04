---
icon: trash-can-xmark
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

# Remove Liquidity Pool

**Withdraw liquidity and remove your token’s LP.**

{% hint style="success" %}
#### [https://alphecca.io/remove-lp](https://alphecca.io/remove-lp)
{% endhint %}

## How to Use Remove Liquidity

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Pool Type

| Pool Type | Description                        |
| --------- | ---------------------------------- |
| V2 Pool   | Remove liquidity using LP tokens   |
| V3 Pool   | Remove liquidity from NFT position |

### Step 3: Select LP Token

Select your LP token (V2) or NFT position (V3) from the dropdown field. Alphecca automatically detects your available positions.

### Step 4: Set Amount

Enter the amount or percentage of liquidity to remove.

### Step 5: Fee Collection Option (V3 Only)

| Option                | Description                                   |
| --------------------- | --------------------------------------------- |
| Remove Only           | Remove liquidity without collecting fees      |
| Remove + Collect Fees | Remove liquidity and collect accumulated fees |

{% hint style="info" %}
V3 positions accumulate trading fees separately. Choose whether to collect them together when removing liquidity.
{% endhint %}

### Step 6: Remove Liquidity

Click the 'Remove Liquidity' button and approve the transaction in your wallet.

***

### Frequently Asked Questions

#### What is the purpose of Remove Liquidity?

Removing liquidity means withdrawing your share of tokens from the liquidity pool. When you redeem your LP tokens (V2) or close your position (V3), you receive back your contributed assets based on the current pool ratio.

#### Will I get back the same amount I deposited?

Not necessarily. The amount you receive depends on:

* Current pool ratio (may have changed due to trades)
* Impermanent loss (price divergence between paired tokens)
* Accumulated trading fees (added to your share)

#### Can I remove partial liquidity?

Yes. You can remove any percentage of your liquidity while keeping the rest in the pool.

#### How do I collect fees only without removing liquidity? (V3)

Use the Collect Fees page to claim accumulated trading fees while keeping your position active.
