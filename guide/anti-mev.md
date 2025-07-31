---
icon: shield-check
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

# Anti-MEV Volume Bot

Boost trading volume rapidly and securely to increase visibility, avoid sandwich attacks, and drive traction.

{% hint style="success" %}
#### [https://alphecca.io/anti-mev](https://alphecca.io/anti-mev)
{% endhint %}

## How to Use Anti-MEV Volume Bot?&#x20;

* **Connected Wallet**

1. Open the **Anti-MEV Volume Bot** page.
2. Select Connected Wallet.
3. **Enter the token mint address** perform volume brushing on.
4. Import sender wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
5. Enter the buying amount\
   \- buying amount must be **at least 0.0000001 SOL**
6. Select or Enter the Jito Tip\
   \- Jito Tip must be **at least 0.000001 SOL**
7. Click the **Start** button and approve the transaction in your wallet app.

* **Other Wallet**

1. Open the **Anti-MEV Volume Bot** page.
2. Select Other Wallet.
3. **Enter the token mint address** perform volume brushing on.
4. Import sender wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
5. Select wallets for volume brush.
6. Select or enter the volume brushing count.
7. Enter the buying amount\
   \- buying amount must be **at least 0.0000001 SOL**
8. Enter the delay\
   \- delay must be **at least 1 second**
9. Select or Enter the Jito Tip\
   \- Jito Tip must be **at least 0.000001 SOL**
10. Click the **Start** button to activate the bot.
11. You can monitor the progress of the bot cycle through the **Bot Logs**.

{% hint style="info" %}
NOTE\
\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.\
\- If a selected wallet's balance falls below **0.005 SOL + Buying Amount + Jito Tip**, its transaction will fail.\
\- You will **not** be charged for failed transactions.
{% endhint %}

## What is the purpose of the Anti MEV Volume Bot?

The Anti MEV Volume Bot is used to safely generate a large volume of trades within a short period. By leveraging Jito technology, it executes buy and sell orders within the same block, effectively preventing sandwich attacks.

## What is a sandwich attack?

A sandwich attack is a malicious technique where an attacker performs front-running by inserting transactions immediately before and after a user's trade order—buying before and selling after—to manipulate the price and profit from the price difference. This usually occurs on decentralized exchanges (DEXs) and exploits the slippage in transaction prices.

## Can the Anti-MEV Volume Bot completely prevent sandwich attacks?

The Anti-MEV Volume Bot uses Jito technology to execute buy and sell orders **within the same block**, enabling it to **completely prevent** sandwich attacks.
