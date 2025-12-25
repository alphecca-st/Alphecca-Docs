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
#### [https://alphecca.io/market-maker](https://alphecca.io/market-maker)
{% endhint %}

## How to Use Volume Bot

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Bot Type

<table><thead><tr><th width="171">Bot Type</th><th>Description</th></tr></thead><tbody><tr><td>Booster Bot</td><td>Naturally increases your token's makers and trading volume</td></tr><tr><td>Bumper Bot</td><td>Raises token price by investing into the liquidity pool</td></tr><tr><td>Advanced Bot<br>(Coming Soon)</td><td>Allows custom strategies including trades per maker, holding time, and more</td></tr></tbody></table>

### Step 3: Enter Token Address

Enter the token contract address you want to generate volume for.

### Step 4: Set Makers

Enter the number of maker wallets to execute trades during the bot cycle. More makers create more natural-looking trading activity.

### Step 5: Set Amount

<table><thead><tr><th width="117">Bot Type</th><th width="176">Field</th><th>Description</th></tr></thead><tbody><tr><td>Booster Bot</td><td>Volume to Generate</td><td>Total volume to generate. Enter an appropriate amount considering current liquidity and number of makers.</td></tr><tr><td>Bumper Bot</td><td>Liquidity to Add</td><td>Total liquidity to invest. Remaining tokens will be sent to your wallet as each maker completes.</td></tr></tbody></table>

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

Estimated time may vary depending on network conditions. Your wallet balance must be greater than the total amount plus gas fees.
{% endhint %}

## How Does the Bot Work?

Alphecca automatically calculates the token’s swap fee rate and determines the optimized cost needed for the requested bot cycle. It then calculates the swap fees, network gas fees, and the SOL required to generate volume, and **collects payment from the user directly through the wallet app.**

* **Total Swap Fees**:\
  &#x20;`(Volume to Generate) × (Swap Fees Rate)` \
  \- Typical swap fees are 0.25% for Raydium and 1% for Pump.fun.
* **Total Network Gas Fees:**\
  &#x20;`(Maker to Generate) × (0.000005 SOL + Priority Fees) × 4` \
  \- A small amount of additional fees may apply for transfer transactions and some failed transactions.

Afterwards, the server automatically executes buy, sell, and close operations for each maker. Once the entire bot cycle finishes, the SOL used for volume generation is returned to the paying wallet, and the bot cycle ends.

{% hint style="info" %}
**NOTE**

\- For Bump bots, the tokens swapped with SOL are sent to the paying wallet for each maker to support price movement.
{% endhint %}

## Can I Use the Bot with Zero Priority Fee?

Yes — Alphecca is optimized to run bots reliably even with a zero priority fee. However, during periods of high congestion on the Solana network, transaction delays may occur, ranging from a few minutes to over an hour.

While such delays are not common, if you prefer smooth and uninterrupted bot operation, we recommend setting a priority fee of at least **0.00001 SOL**.

## Recommendation

This bot is designed for cost-efficient operations. For maximum impact, use it together with other features. For example, running the bot alongside **Multi Swap Page** or the **Market Making Page** can create a more organic and **natural-looking chart**.
