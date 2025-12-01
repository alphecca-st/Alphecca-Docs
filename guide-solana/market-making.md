---
icon: chart-line-up-down
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

# Market Making

**Set your bot parameters and design the price chart exactly the way you envision.**

{% hint style="success" %}
#### [https://alphecca.io/market-making](https://alphecca.io/market-making)
{% endhint %}

## How to Use Maker Making?&#x20;

1. Open the **Market Making** page.
2. **Enter the token mint address** to run the bot on.
3. Import operational wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
4.  Select a **bot type** and input **parameters** to run:<br>

    **Pull Up**: The bot automatically buys tokens to push the price upward.

    * **Single Transaction Volume (SOL):** The amount of SOL to buy per transaction. If _Random_ is selected, a value will be chosen between the minimum and maximum.
    * **Task Execution Interval (seconds):** The delay between transactions, in seconds. If _Random_ is selected, the interval is randomly chosen between the minimum and maximum. It must be at least **1**, and for higher success rates, a setting of **5 seconds or more** is recommended.
    * **Slippage Setting (%):** Choose the slippage tolerance (%) for swap transactions. _AUTO_ is recommended for higher success rates.
    * **Jito MEV Tip (SOL):** This priority fee is paid to Jito to protect against front-running. If transaction success is low, you may set it to _ZERO_ to send normal transactions instead.
    * _**(Optional) Termination Conditions** — The bot will stop automatically if any of the following are met:_
      * **Target Price Change (%):** If the price rises above the specified % from the initial price. _For example, if you enter 30, the bot will automatically stop once the price increases by 30% from the starting point._
      * **Running Duration (minutes):** The bot stops after the specified time has elapsed.
      * **Total Maximum Transaction Amount (SOL):** The bot stops once the total accumulated buy volume exceeds this limit.<br>

    **Drop**: The bot automatically sells tokens to push the price downward.

    * **Single Transaction Volume (Token):** The amount of tokens to sell per transaction. If _Random_ is selected, a value will be chosen between the minimum and maximum.
    * **Task Execution Interval (seconds):** The delay between transactions, in seconds. If _Random_ is selected, the interval is randomly chosen between the minimum and maximum. It must be at least **1**, and for higher success rates, a setting of **5 seconds or more** is recommended.
    * **Slippage Setting (%):** Choose the slippage tolerance (%) for swap transactions. _AUTO_ is recommended for higher success rates.
    * **Jito MEV Tip (SOL):** This priority fee is paid to Jito to protect against front-running. If transaction success is low, you may set it to _ZERO_ to send normal transactions instead.
    * _**(Optional) Termination Conditions** — The bot will stop automatically if any of the following are met:_
      * **Target Price Change (%):** If the price falls below the specified % from the initial price. _For example, if you enter 30, the bot will automatically stop once the price decreases by 30% from the starting point._
      * **Running Duration (minutes):** The bot stops after the specified time has elapsed.
      * **Total Maximum Transaction Amount (Token):** The bot stops once the total accumulated sell volume exceeds this limit.\
        <br>

    **Traffic**: If the bot does not hold enough tokens to sell, it will buy. If tokens are available, the bot will randomly buy or sell with a 50% probability.

    * **Single Transaction Volume (Token):** The amount of tokens to sell per transaction. If _Random_ is selected, a value will be chosen between the minimum and maximum. If the wallet balance is less than this amount, the bot will purchase this amount of tokens.
    * **Task Execution Interval (seconds):** The delay between transactions, in seconds. If _Random_ is selected, the interval is randomly chosen between the minimum and maximum. It must be at least **1**, and for higher success rates, a setting of **5 seconds or more** is recommended.
    * **Slippage Setting (%):** Choose the slippage tolerance (%) for swap transactions. _AUTO_ is recommended for higher success rates.
    * **Jito MEV Tip (SOL):** This priority fee is paid to Jito to protect against front-running. If transaction success is low, you may set it to _ZERO_ to send normal transactions instead.
    * _**(Optional) Termination Condition**s — The bot will stop automatically if any of the following are met:_
      * **Running Duration (minutes):** The bot stops after the specified time has elapsed.
      * **Total Maximum Transaction Amount (SOL):** The bot stops once the total accumulated transaction volume exceeds this limit.
5. Select the wallets you want to operate and click the **Start** button. The bot will begin running.
6. You can monitor the bot’s activity in the **Transactions Log** section and control it using the **PAUSE** and **STOP** buttons.

{% hint style="info" %}
**NOTE**

\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.

\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}

## Recommendation

Run the **Pull Up** and **Drop** bots simultaneously with **different execution intervals and trade ratios** to create a more **dynamic** and **natural-looking chart**.
