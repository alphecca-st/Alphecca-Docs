---
icon: robot
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

# Volume Bot

**Automatically create token activity and maker addresses with optimized gas usage.**

{% hint style="success" %}
#### [https://alphecca.io/binance/volume-bot](https://alphecca.io/binance/volume-bot)
{% endhint %}

## How to Use Volume Bot

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Bot Type

<table><thead><tr><th width="171">Bot Type</th><th>Description</th></tr></thead><tbody><tr><td>Booster Bot</td><td>Naturally increases your token's makers and trading volume</td></tr><tr><td>Bumper Bot</td><td>Raises token price by investing into the liquidity pool</td></tr><tr><td>Advanced Bot<br>(Coming Soon)</td><td>Allows custom strategies including trades per maker, holding time, and more</td></tr></tbody></table>

### Step 3: Enter Token Address

Enter the token contract address you want to generate volume for. Available pools will be displayed on the right side. Select the pool you want to operate on.

### Step 4: Set Makers

Enter the number of maker wallets to execute trades during the bot cycle. More makers create more natural-looking trading activity.

### Step 5: Set Amount

<table><thead><tr><th width="187">Field</th><th>Description</th></tr></thead><tbody><tr><td>Booster Bot<br>(Volume to Generate)</td><td>Total volume to generate. Enter an appropriate amount considering current liquidity and number of makers.</td></tr><tr><td>Bumper Bott<br>(Liquidity to Add)</td><td>Total liquidity to invest. Remaining tokens will be sent to your wallet as each maker completes.</td></tr></tbody></table>

{% hint style="warning" %}
Using few makers with large volume may cause the bot to stop due to external MEV bots. We recommend that (Volume to Generate / Number of Makers) does not exceed 3% of the current liquidity value. Note that this is a general guideline and not a guaranteed threshold.

When generating large volume, we recommend using more makers.
{% endhint %}

### Step 6: Select Bot Speed

<table><thead><tr><th width="169">Speed</th><th>Description</th></tr></thead><tbody><tr><td>Slow</td><td>1 core - Lower resource usage, slower execution</td></tr><tr><td>Normal</td><td>2 cores - Balanced speed and efficiency</td></tr><tr><td>Fast</td><td>3 cores - Maximum speed, parallel execution</td></tr></tbody></table>

{% hint style="info" %}
**NOTE**

Bot speed varies depending on chain block time and network conditions.
{% endhint %}

### Step 7: Review Fee Details

Toggle "Fee Details" to view estimated costs:

* **Gas Fees**: Gas and swap fees used during the bot cycle
* **Refund Amount**: This amount is used to generate trading volume and will be returned to your connected wallet once the bot cycle completes.
* **Volume to Generate**: Total volume that the Bumper Bot will generate
* **Tokens to Refund**: Tokens swapped by Bumper Bot maker wallets during liquidity investment. These tokens will be sent to your connected wallet as each maker wallet completes.

### Step 8: Start Bot

Click the 'Start' button and approve the transaction in your wallet.

{% hint style="info" %}
**NOTE**

If your token meets the following conditions, maker wallets will be automatically whitelisted: token created on Alphecca + connected wallet is the token owner wallet + tax/antibot/antiwhale settings enabled + ownership retained.
{% endhint %}

{% hint style="warning" %}
Alphecca is not responsible for any losses, legal issues, or consequences arising from the use of this bot. Users are responsible for complying with the laws and regulations of their respective jurisdictions.
{% endhint %}

***

### Frequently Asked Questions

#### What is a Volume Bot?

A Volume Bot is a tool that increases your token's trading volume and maker count, making it appear actively traded. Key metrics for trending rankings on DEXTools, DEXScreener, and other platforms are trading volume and maker count. By utilizing a Volume Bot, you can effectively boost these metrics and enhance your token's visibility.

#### How does the bot work?

Alphecca automatically calculates your token's swap fee rate and determines the optimized cost required for the requested bot cycle. It then calculates swap fees, network gas fees, and the cost needed to generate trading volume, and receives payment through your wallet app. After the bot cycle completes, the remaining amount (excluding service fees) is automatically refunded to the wallet that made the request.

#### What's the difference between Volume Bot and regular trading?

Regular trading occurs from a single wallet, but Volume Bot generates distributed trades through multiple maker wallets. This creates more natural trading patterns and makes it appear as if trades are occurring from various wallet addresses.

#### Which DEX exchanges are supported?

<table><thead><tr><th width="130">Chain</th><th>Supported DEX</th></tr></thead><tbody><tr><td>Ethereum</td><td>UniSwap V2, UniSwap V3, <br>PancakeSwap V2, PancakeSwap V3,<br>SushiSwap V2</td></tr><tr><td>BSC</td><td>Four.Meme<br>UniSwap V2, UniSwap V3,<br>PancakeSwap V2, PancakeSwap V3,<br>SquadSwap V2, SquadSwap V3,</td></tr><tr><td>Base</td><td>UniSwap V2, UniSwap V3,<br>PancakeSwap V2, PancakeSwap V3,<br>Aerodrome,<br>QuickSwap V2</td></tr><tr><td>Polygon</td><td>UniSwap V2, UniSwap V3,<br>QuickSwap V2,<br>SushiSwap V2</td></tr><tr><td>Avalanche</td><td>UniSwap V2, UniSwap V3,<br>SushiSwap V2</td></tr><tr><td>Monad</td><td>UniSwap V2, UniSwap V3, <br>PancakeSwap V2, PancakeSwap V3,</td></tr><tr><td>Arbitrum</td><td>UniSwap V2, UniSwap V3, <br>PancakeSwap V2, PancakeSwap V3,<br>SushiSwap V2</td></tr><tr><td>Optimism</td><td>UniSwap V2, UniSwap V3,</td></tr></tbody></table>

#### How much does the Volume Bot cost?

Alphecca charges fees based on the number of Makers, regardless of volume or time. Service Fees are as follows:

<table><thead><tr><th width="130">Chain</th><th>Fee (per 100 Makers)</th></tr></thead><tbody><tr><td>Ethereum</td><td>0.0025 ETH</td></tr><tr><td>BSC</td><td>0.015 BNB</td></tr><tr><td>Base</td><td>0.0025 ETH</td></tr><tr><td>Polygon</td><td>20 POL</td></tr><tr><td>Avalanche</td><td>0.7 AVAX</td></tr><tr><td>Monad</td><td>400 MON</td></tr><tr><td>Arbitrum</td><td>0.0025 ETH</td></tr><tr><td>Optimism</td><td>0.0025 ETH</td></tr></tbody></table>
