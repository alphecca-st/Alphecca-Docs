---
icon: circle-plus
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

# Add Liquidity Pool

**Add liquidity to existing Raydium CPMM pools to receive LP tokens and earn trading fees.**

{% hint style="success" %}
#### [https://alphecca.io/add-lp/binance](https://alphecca.io/add-lp/binance)
{% endhint %}

## How to Use Add Liquidity

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Pool Type

| Pool Type | Description                                          |
| --------- | ---------------------------------------------------- |
| V2 Pool   | Classic constant product AMM (x \* y = k)            |
| V3 Pool   | Concentrated liquidity for higher capital efficiency |

### Step 3: Select Token Pair

Select the token and quote token pair for the existing liquidity pool you want to add to.

### Step 4: Set Amount

Enter the amount of tokens to add. The required quote token amount will be automatically calculated based on current pool ratio.

{% hint style="warning" %}
Your wallet balance must be greater than the sum of tokens to add, service fees, and network gas fees.
{% endhint %}

### Step 5: Add Liquidity

Click the 'Add Liquidity' button and approve the transaction in your wallet.

***

### Frequently Asked Questions

#### Why is the quote token amount automatically calculated?

When adding liquidity to an existing pool, you must maintain the current pool ratio to avoid price impact. The system automatically calculates the required amount based on current pool reserves, ensuring your liquidity is added without affecting the token price.

#### What happens to my LP tokens after adding liquidity?

After successfully adding liquidity, you'll receive LP tokens proportional to your contribution. These tokens represent your share of the pool and entitle you to a portion of trading fees.

| Pool Type | LP Token Format                                      |
| --------- | ---------------------------------------------------- |
| V2 Pool   | Additional tokens added to existing LP balance       |
| V3 Pool   | New NFT position created for each liquidity addition |

{% hint style="info" %}
V3 pools create a new NFT for each position, even when adding to the same price range. You can manage multiple positions separately.
{% endhint %}

#### Can I add liquidity to any pool?

Yes. You can add liquidity to any existing pool that your token is paired with, as long as you have sufficient balance of both tokens.
