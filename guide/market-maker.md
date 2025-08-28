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

# Maker and Volume Bot

**Automatically create token activity and maker addresses with optimized gas usage.**

{% hint style="success" %}
#### [https://alphecca.io/market-maker](https://alphecca.io/bundle-sell-buy)
{% endhint %}

## How to Use Maker and Volume Bot?&#x20;

1. Open the **Maker and Volume Bot** page.
2. Select Bot type.
3. **Enter the token mint address** to run the bot on.\
   \- **SPL 2022 Program** Token Cannot be Processed.
4. Input the **number of makers** to generate.\
   \- Maximum: 9,000 makers
5. Choose Selling Amount.
6.  For **Boost Bot:**

    * Enter the **volume to generate** during the bot cycle.
    * The volume cannot exceed **Maker × 1 SOL**.

    For **Bump Bot:**

    * Enter the amount of **SOL to inject into liquidity** during the bot cycle.
    * The SOL amount cannot exceed **Maker × 0.03 SOL**.
7. Select or enter the priority fee.\
   \- The entered priority fee will be applied to swap transactions.
8. Click the **Start** button to activate the bot.
9. You can monitor the progress of the bot cycle through the **Bot Logs**.

{% hint style="info" %}
**NOTE**

\- If liquidity is removed during the bot cycle, the bot may stop operating. In this case, any remaining SOL will be sent back to the paying wallet within 60 minutes.

\- The bot will continue running even if you close or refresh the page.
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
