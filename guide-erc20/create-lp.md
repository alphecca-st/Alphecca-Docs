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

Create a liquidity pool to make your token tradable.

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

| Field      | Description                               |
| ---------- | ----------------------------------------- |
| Token      | Your token to be listed                   |
| Base Token | The pairing token (ETH, USDC, USDT, etc.) |

{% hint style="success" %}
Multiple base token options available. Choose the best pairing for your token's target market.
{% endhint %}

### Step 4: Set Fee Tier (V3 Only)

Select a fee tier: 0.01% / 0.05% / (0.25%, 0.30%) / 1.00%

{% hint style="info" %}
Lower fee tiers mean less cost for traders but smaller rewards for liquidity providers. The pool creator earns rewards proportional to this fee rate from every trade.
{% endhint %}

### Step 5: Set Initial Liquidity

Enter the amount of tokens and base tokens to add to the initial liquidity pool.

{% hint style="warning" %}
Your wallet balance must be greater than the sum of base tokens to add, service fees, and network gas fees.
{% endhint %}

### Step 6: Create Pool

Click the 'Create LP' button and approve the transaction in your wallet.

{% hint style="info" %}
**Transaction Approvals Required:**

* **Native Token (ETH, BNB, POL):** 2 transactions
  * 1x Token Approve
  * 1x Create Liquidity Pool
* **Stablecoin (USDC, USDT, etc.):** 3 transactions
  * 1x Token Approve
  * 1x Base Token Approve
  * 1x Create Liquidity Pool
{% endhint %}

{% hint style="info" %}
The token approval (Approve) transaction is only required once per token. After that, only 1 transaction is needed.
{% endhint %}

### Step 7: Check Transaction Logs

After transaction is confirmed, go to the 'Transaction Logs' tab to view transaction hash. Click the explorer icon to verify directly on the block explorer.

***

### Frequently Asked Questions

#### Why create a liquidity pool?

A liquidity pool enables trading for your token. Without it, holders cannot buy or sell on decentralized exchanges. Creating a pool instantly lists your token and opens it to the entire DeFi ecosystem.

#### Which DEXs are supported?

Alphecca supports major DEXs on each chain including Uniswap, PancakeSwap, Aerodrome, and more. Both V2 and V3 pools are available.

#### Which pool type should I choose?

| Pool Type | Description                                                                       |
| --------- | --------------------------------------------------------------------------------- |
| V2 Pool   | Liquidity distributed across entire price range. Fee rewards auto-compounded.     |
| V3 Pool   | Liquidity concentrated in specific price range. Fee rewards withdrawable anytime. |

#### How can I check the trading chart after creation?

You can view the trading chart on DEX Screener: https://dexscreener.com/{chain}/{your\_token\_address}

#### What is the LP Token in my wallet?

LP (Liquidity Provider) Token represents your share of the liquidity pool. It can be used to withdraw your liquidity or participate in staking/farming programs.

| Pool Type | LP Token Type                                      |
| --------- | -------------------------------------------------- |
| V2 Pool   | Standard ERC-20 token                              |
| V3 Pool   | NFT (each position is unique based on price range) |

#### Can I add more liquidity later?

Yes. You can add or remove liquidity anytime through the Manage Liquidity page.

#### Can I create multiple liquidity pools with one token?

Yes. You can create liquidity pools on multiple DEXs (Uniswap, SushiSwap, PancakeSwap, etc.) with a single token. Additionally, you can create separate pools with different pairs (ETH, USDT, USDC, etc.) on the same DEX.
