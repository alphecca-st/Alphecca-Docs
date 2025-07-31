---
icon: rocket-launch
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

# Bundled Buy

**Buy tokens using multiple wallets in a single block to push price momentum and maximize gains.**

{% hint style="success" %}
#### [https://alphecca.io/bundle-buy](https://alphecca.io/bundle-buy)
{% endhint %}

## How to Use Bundled Buy?&#x20;

1. Open the **Bundled Buy** page.
2. **Enter the token mint address** you want to buy.
3. Import buying wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
4. Select wallets for bundled buy.\
   \- You can select up to **5 wallets.**
5. Enter the amount to buy.\
   \- You can manually enter the amount of SOL for each buying wallet.\
   \- Or use the **Amount** button to apply a fixed or total amount to all buying wallets at once.\
   \- Each buying wallet's SOL balance must be **at least** **Buying Amount + 0.005 SOL**, and among the selected wallets, the one with the highest SOL balance must be **at least** **Buying Amount + 0.005 SOL + Total Service Fees + Jito Tip**.
6. Select or Enter the Jito Tip\
   \- Jito Tip must be **at least 0.000001 SOL**
7. (Optional) Enter a specified address to receive purchased tokens:\
   \- Purchased tokens will be sent to this address.\
   \- This address must have an associated token ATA account.
8. **Click the "Bundled Buy" button** to proceed with the transaction.

{% hint style="info" %}
**NOTE**\
\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.\
\- Jito Tip and Service Fees are paid from the wallet with the highest Solana balance of the selected wallets.\
\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}

## What is the purpose of Bundled Buy?

Bundled Buy is a powerful tool designed to safely increase the token price by generating coordinated buy orders. It helps create strong and sustained upward price momentum while minimizing risks such as front-running, sandwich attacks, and price manipulation.

## What is a sandwich attack?

A sandwich attack is a malicious technique where an attacker performs front-running by inserting transactions immediately before and after a user's trade order—buying before and selling after—to manipulate the price and profit from the price difference. This usually occurs on decentralized exchanges (DEXs) and exploits the slippage in transaction prices.

## Can the Bundled Buy completely prevent sandwich attacks?

The Bundled Buy uses Jito technology to execute multiple buy orders **within the same block**, enabling it to **completely prevent** sandwich attacks.
