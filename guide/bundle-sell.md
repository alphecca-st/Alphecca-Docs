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

# Bundled Sell

**Sell from multiple wallets in one block to secure profits and protect against sandwich attacks.**

{% hint style="success" %}
#### [https://alphecca.io/bundle-sell](https://alphecca.io/bundle-sell)
{% endhint %}

## How to Use Bundled Sell?&#x20;

1. Open the **Bundled Sell** page.
2. **Enter the token mint address** you want to buy.
3. Import selling wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
4. Select wallets for bundled sell.\
   \- You can select up to **29 wallets.**
5. Select the amount to sell.\
   \- You can use the **Amount** button to apply amount to all selling wallets at once.\
   \- Among the selected wallets, the one with the highest SOL balance must be **at least** **0.003 SOL + Total Service Fees + Jito Tip**.
6. Select or Enter the Jito Tip\
   \- Jito Tip must be **at least 0.000001 SOL**
7. **Click the "Bundled Sell" button** to proceed with the transaction.

{% hint style="info" %}
**NOTE**\
\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.\
\- Jito Tip, All Transaction Gas Fees and Service Fees are paid from the wallet with the highest Solana balance of the selected wallets.\
\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}

## What is the purpose of Bundled Sell?

Bundled Sell is designed to execute multiple token sell orders together in a single batch. This helps efficiently manage token liquidity, reduce transaction costs, and maintain orderly market activity by preventing large, sudden sell-offs. Additionally, it helps protect against sandwich attacks by minimizing exposure to front-running tactics during the selling process.

## What is a sandwich attack?

A sandwich attack is a malicious technique where an attacker performs front-running by inserting transactions immediately before and after a user's trade order—buying before and selling after—to manipulate the price and profit from the price difference. This usually occurs on decentralized exchanges (DEXs) and exploits the slippage in transaction prices.

## Can the Bundled Sell completely prevent sandwich attacks?

The Bundled Sell uses Jito technology to execute multiple sell orders **within the same block**, enabling it to **completely prevent** sandwich attacks.
