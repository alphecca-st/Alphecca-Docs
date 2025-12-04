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

### Step 3: Select Position

| Pool Type | Selection Method                             |
| --------- | -------------------------------------------- |
| V2 Pool   | Select LP token from your wallet             |
| V3 Pool   | Select NFT position from your positions list |

### Step 4: Set Amount

Enter the amount or percentage of liquidity to remove.

### Step 5: Collect Fees (V3 Only)

{% hint style="info" %}
V3 positions accumulate trading fees separately. You can collect fees without removing liquidity, or collect them together when removing.
{% endhint %}

| Option            | Description                                       |
| ----------------- | ------------------------------------------------- |
| Collect Fees Only | Claim accumulated fees without removing liquidity |
| Remove + Collect  | Remove liquidity and collect fees together        |

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

#### What happens to uncollected fees in V3?

Uncollected fees remain in your position until you claim them. You can collect fees anytime without removing your liquidity.

#### Can I remove partial liquidity?

Yes. You can remove any percentage of your liquidity while keeping the rest in the pool.
