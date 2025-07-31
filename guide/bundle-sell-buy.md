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

# Sell and Bundled Buy

Sell from multiple wallets in one block to secure profits and protect against sandwich attacks.

{% hint style="success" %}
#### [https://alphecca.io/bundle-sell-buy](https://alphecca.io/bundle-sell-buy)
{% endhint %}

## How to Use Bundled Sell?&#x20;

1. Open the **Sell and Bundled Buy** page.
2. **Enter the token mint address** you want to sell and bundled buy.
3. Enter the selling wallet private key.
4. Choose Selling Amount.
5. Import buying wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
6. Select wallets for bundled buy.\
   \- You can select up to **4 wallets.**
7. Enter the amount to buy.\
   \- You can manually enter the amount of SOL for each buying wallet.\
   \- Or use the **Amount** button to apply a fixed or total amount to all buying wallets at once.\
   \- Each buying wallet's SOL balance must be **at least** **Buying Amount + 0.005 SOL**, and among the selected wallets, the one with the highest SOL balance must be **at least** **Buying Amount + 0.005 SOL + Service Fees + Jito Tip**.
8. Select or Enter the Jito Tip\
   \- Jito Tip must be **at least 0.000001 SOL**
9. **Click the "Bundled Sell and Buy" button** to proceed with the transaction.

{% hint style="info" %}
NOTE\
\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.\
\- Jito Tip and Service Fees are paid from the wallet with the highest Solana balance of the selected wallets.\
\- You will **not** be charged for failed transactions.
{% endhint %}
