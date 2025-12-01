---
icon: right-left
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

# Multi Swap

Swap SPL tokens quickly, cheaply, and easily.

{% hint style="success" %}
#### [https://alphecca.io/multi-swap](https://alphecca.io/multi-swap)
{% endhint %}

## How to Use Multi Swap?&#x20;

1. Open the **Multi Swap** page.
2. **Enter the token mint address** to swap.
3. Import operational wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
4. Select a **swap type** and input **parameters** to run:
   * **Task Execution Interval (seconds):** The delay between transactions, in seconds. If _Random_ is selected, the interval is randomly chosen between the minimum and maximum. It must be at least **1**, and for higher success rates, a setting of **5 seconds or more** is recommended.
   * **Slippage Setting (%):** Choose the slippage tolerance (%) for swap transactions. _AUTO_ is recommended for higher success rates.
   * **Jito MEV Tip (SOL):** This priority fee is paid to Jito to protect against front-running. If transaction success is low, you may set it to _ZERO_ to send normal transactions instead.
5. Click the **Amount** button in the wallet list. Then, enter the amount to **Swap**. You can input it manually or apply it in bulk.
   * **MAX:** The maximum tradable amount per wallet. For _Buy_, this is `solbalance - (0.008 + service fee) SOL`; for _Token_, it is the total balance.
   * **FIXED:** The same value is applied to all wallets.
   * **RANDOM:** A random value between the specified minimum and maximum is applied to each wallet.
   * **RANDOM%:** A random percentage of the balance, between the specified minimum and maximum, is applied to each wallet.
6. Select the wallets you want to operate and click the **Multi Swap** button. The transactions will start.
7. You can monitor the bot’s activity in the **Transactions Log** section and control it using the **PAUSE** and **STOP** buttons.

{% hint style="info" %}
**NOTE**

\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.

\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}
