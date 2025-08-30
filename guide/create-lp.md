---
icon: chart-simple
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

# Create Liquidity Pool

**Set up a liquidity pool to make your token tradable.**

{% hint style="success" %}
#### [https://alphecca.io/create-lp](https://alphecca.io/create-lp)
{% endhint %}

## How to Use Create Liquidity Pool?&#x20;

1. Click the **Connect Wallet** button in the top-right corner to connect.
2. Select the **token mint address** for the liquidity pool creation.
3. Input the **amount of tokens and Solana** to be added to the **initial liquidity pool**.\
   \- Your SOL balance must be greater than the sum of the Solana amount to add, Service Fees, and Raydium CPMM Fees + Network Gas Fees (approximately 0.19 SOL).
4. Click the **Create LP button** and approve the transaction in your wallet app.
5. When the transaction is completed, the **transaction signature** and **Pool ID** will be displayed at the **top right corner**.

## How can I check the token’s trading chart after the liquidity pool is created?

You can view the trading chart immediately after the pool creation on **DEX Tools**.\
Typically, you can check it at:\
`https://dexscreener.com/solana/{your_token_mint_address}`\
(Replace `{your_token_mint_address}` with your actual token mint address.)

## After creating the liquidity pool, an "Unknown Token" appeared in my wallet app. What is this?

This is the LP (Liquidity Provider) Token, which represents your share of the liquidity pool. When you add liquidity, you receive LP tokens as proof of your contribution. These tokens can be used later to withdraw your share of the pool or to participate in staking or farming programs, depending on the platform. The “Unknown Token” label appears because your wallet may not recognize the LP token metadata by default, but rest assured, it is a standard part of liquidity provision on decentralized exchanges.
