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
#### [https://alphecca.io/add-lp](https://alphecca.io/add-lp)
{% endhint %}

## How to Use Add Liquidity Pool?&#x20;

1. Click the **Connect Wallet** button in the top-right corner to connect.
2. Select the **token mint address** from your wallet's token list.
3. Input the **amount of tokens and Solana** to add to the existing liquidity pool.
   * The pool will automatically calculate the required ratio based on current pool reserves.
   * Your SOL balance must be greater than the SOL amount to add + 0.0521 SOL (ATA rent + service fee).
4. Click the **Add Liquidity** button and approve the transaction in your wallet app.
5. When the transaction is completed, the **transaction signature** will be displayed at the **top right corner**.

## Why is the SOL amount automatically calculated when I enter my token amount?

When adding liquidity to an existing pool, you must maintain the current pool ratio to avoid price impact. The system automatically calculates the required SOL amount based on the token amount you enter and the current pool reserves. This ensures your liquidity is added at the correct ratio without affecting the token price.

## What happens to my LP tokens after adding liquidity?

After successfully adding liquidity, you'll receive additional LP (Liquidity Provider) tokens proportional to your contribution. These tokens represent your increased share of the pool and entitle you to a larger portion of trading fees. You can view your LP token balance in your wallet, and use them later to remove liquidity or participate in yield farming programs if available.
