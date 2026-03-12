---
icon: trash-can-xmark
---

# Remove Liquidity Pool  (EVM)

This guide walks you through removing liquidity from a pool on EVM chains with Alphecca Tools.

{% hint style="info" %}
#### Tool Page

* Link : [Remove Liquidity Pool on Ethereum](https://alphecca.io/en/remove-lp/ethereum)
* Link : [Remove Liquidity Pool on Binance Smart Chain](https://alphecca.io/en/remove-lp/binance)
* Link : [Remove Liquidity Pool on Base](https://alphecca.io/en/remove-lp/base)
* Link : [Remove Liquidity Pool on Polygon](https://alphecca.io/en/remove-lp/polygon)
* Link : [Remove Liquidity Pool on Avalanche](https://alphecca.io/en/remove-lp/avalanche)
* Link : [Remove Liquidity Pool on Monad](https://alphecca.io/en/remove-lp/monad)
* Link : [Remove Liquidity Pool on Arbitrum](https://alphecca.io/en/remove-lp/arbitrum)
* Link : [Remove Liquidity Pool on Optimism](https://alphecca.io/en/remove-lp/optimism)
{% endhint %}

## How to Use Remove Liquidity

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select LP Token / NFT Position

Select the LP token you want to remove from the dropdown. Both V2 LP tokens and V3 NFT positions are displayed.

| Pool Type | LP Token Type                         |
| --------- | ------------------------------------- |
| V2 Pool   | Standard ERC-20 LP token              |
| V3 Pool   | NFT position (unique per price range) |

### Step 3: Set Remove Amount

Use the slider or percentage buttons (25%, 50%, 75%, 100%) to select how much liquidity to remove.

{% hint style="info" %}
The estimated assets to be received are displayed below the slider, calculated based on current pool reserves.
{% endhint %}

### Step 4: V3 Options (V3 Only)

For V3 positions, toggle 'With Fees' to collect accumulated trading fees along with your liquidity removal.

### Step 5: Remove Liquidity

Click the 'Remove Liquidity' button and approve the transaction in your wallet.

{% hint style="info" %}
**Required Transaction Approvals:**

* **V2 Pool:** 2 transactions
  * 1x LP Token Approve
  * 1x Remove Liquidity
* **V3 Pool:** 2 transactions
  * 1x NFT Position Approve
  * 1x Remove Liquidity
{% endhint %}

{% hint style="info" %}
The token approval (Approve) transaction is only required once per LP token/NFT position. After that, only 1 transaction is needed.
{% endhint %}

### Step 6: Check Transaction Logs

After transaction is confirmed, go to the 'Transaction Logs' tab to view your transaction hash. Click the explorer icon to verify directly on the block explorer.

***

## Frequently Asked Questions

### What is the purpose of Remove Liquidity?

Removing liquidity means withdrawing your share of tokens from the liquidity pool. When you redeem your LP tokens (V2) or close your position (V3), you receive back your contributed assets based on the current pool ratio.

### Can I remove partial liquidity?

Yes. You can remove any percentage of your liquidity while keeping the rest in the pool.

### Will I receive native tokens directly?

Yes. If your pool contains wrapped native tokens (WETH, WBNB, WPOL, etc.), Alphecca automatically unwraps them. You will receive native tokens (ETH, BNB, POL) directly to your wallet.

### What happens to my uncollected V3 fees if I remove 100% liquidity?

If '+ Fees' toggle is ON, all accumulated trading fees are collected along with your liquidity. If OFF, fees remain in the position - but since liquidity is removed, you'll need to collect them separately before the position is burned.

