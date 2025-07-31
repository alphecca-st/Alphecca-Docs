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

Sell from multiple wallets in one block to secure profits and protect against sandwich attacks.

{% hint style="success" %}
#### [https://alphecca.io/market-maker](https://alphecca.io/bundle-sell-buy)
{% endhint %}

## How to Use Maker and Volume Bot?&#x20;

1. Select Bot type.
2. **Enter the token mint address** to run the bot on.
3. Input the **number of makers** to create.\
   \- Maximum: 9,000 makers
4. Choose Selling Amount.
5.  For **Boost Bot:**

    * Enter the volume to generate during the bot cycle.
    * The volume cannot exceed **Maker × 1**.

    For **Bump Bot:**

    * Enter the amount of SOL to inject into liquidity during the bot cycle.
    * The SOL amount cannot exceed **Maker × 0.03**.
6. Click the **Start** button to activate the bot.

## How Does the Bot Work?

Alphecca automatically calculates the token’s swap fee rate and determines the optimized cost required for the requested bot cycle. It calculates the swap fees, network gas fees, and the SOL needed to generate volume, then collects payment from the client through the wallet app.

After that, the server automatically executes a sequence of buy, sell, and close actions for each maker. Once the entire bot cycle is complete, the SOL used for volume generation is returned to the paying wallet, and the bot cycle ends.

{% hint style="info" %}
NOTE\
\- If liquidity is removed during the bot cycle, the bot may stop operating. In this case, any remaining SOL will be sent back to the paying wallet within 60 minutes.\
\- The bot will continue running even if you close or refresh the page.
{% endhint %}
