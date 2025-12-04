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
#### [https://alphecca.io/create-lp/binance](https://alphecca.io/create-lp/binance)
{% endhint %}

## How to Use Create Liquidity Pool

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Pool Type

| Pool Type | Description                                          |
| --------- | ---------------------------------------------------- |
| V2 Pool   | Classic constant product AMM (x \* y = k)            |
| V3 Pool   | Concentrated liquidity for higher capital efficiency |

{% hint style="info" %}
V3 pools allow you to concentrate liquidity within specific price ranges, potentially earning more fees with less capital.
{% endhint %}

### Step 3: Select Token Pair

| Field       | Description                               |
| ----------- | ----------------------------------------- |
| Base Token  | Your token to be listed                   |
| Quote Token | The pairing token (ETH, USDC, USDT, etc.) |

{% hint style="success" %}
Multiple quote token options available. Choose the best pairing for your token's target market.
{% endhint %}

### Step 4: Set Fee Tier (V3 Only)

| Fee Tier      | Best For              |
| ------------- | --------------------- |
| 0.01%         | Stablecoin pairs      |
| 0.05%         | Correlated pairs      |
| 0.25% / 0.30% | Most pairs            |
| 1.00%         | Exotic/volatile pairs |

### Step 5: Set Initial Liquidity

Enter the amount of tokens and quote tokens to add to the initial liquidity pool.

{% hint style="warning" %}
Your wallet balance must be greater than the sum of tokens to add, service fees, and network gas fees.
{% endhint %}

### Step 6: Create Pool

Click the 'Create LP' button and approve the transaction in your wallet.

***

### Frequently Asked Questions

#### Why create a liquidity pool?

A liquidity pool enables trading for your token. Without it, holders cannot buy or sell on decentralized exchanges. Creating a pool instantly lists your token and opens it to the entire DeFi ecosystem.

#### Which pool type should I choose?

| Pool Type | Pros                              | Cons                       |
| --------- | --------------------------------- | -------------------------- |
| V2 Pool   | Simple, set-and-forget            | Lower capital efficiency   |
| V3 Pool   | Higher fee earnings, less capital | Requires active management |

#### How can I check the trading chart after creation?

You can view the trading chart immediately on DEX Screener: `https://dexscreener.com/{chain}/{your_token_address}`

#### What is the LP Token in my wallet?

The LP (Liquidity Provider) Token represents your share of the liquidity pool. It proves your contribution and can be used to withdraw your liquidity or participate in staking/farming programs.

| Pool Type | LP Token Format                                    |
| --------- | -------------------------------------------------- |
| V2 Pool   | Standard ERC-20 token                              |
| V3 Pool   | NFT (each position is unique based on price range) |

#### Can I add more liquidity later?

Yes. You can add or remove liquidity anytime through the Manage Liquidity page.
