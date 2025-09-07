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

# Bundle Buy

**Buy tokens using multiple wallets in a single block to push price momentum and maximize gains.**

{% hint style="success" %}
#### [https://alphecca.io/bundle-buy](https://alphecca.io/bundle-buy)
{% endhint %}

## How to Use Bundle Buy?&#x20;

1. Open the **Bundle Buy** page.
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
**NOTE**

\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.

\- Jito Tip and Service Fees are paid from the **Connected wallet**.

\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}

## What is the purpose of Bundle Launch?

The purpose of Bundle Launch is to enable sniping at the lowest possible price by executing the 'first' purchase simultaneously with token creation. Using the atomicity of Jito bundle technology ensures that no other sniper bots can intervene in the process.

Distributing purchases across multiple wallets provides the following advantages:

**Holder Distribution Effects**

* Holder concentration appears dispersed on analysis tools like DEXTools and DexScreener
* Lower single-wallet concentration reduces perceived dumping risk
* Creates natural holder distribution that enhances investor confidence

**Market Perception Improvement**

* Increased initial trading volume and holder count creates perception of an active token
* Higher likelihood of attracting genuine investor interest rather than just bots
* Establishes healthier chart formation during migration from Pump.fun to Raydium

**Risk Management**

* Different exit timing strategies possible for each wallet
* Protection of overall position even if some wallets are exposed
* Optimal gas fee efficiency through appropriate amount allocation per wallet

The core concept is securing optimal entry points through technical advantage (bundling) combined with strategic distribution.

**Note:** This information is provided for educational purposes about DeFi mechanisms. Users should be aware of the risks involved in cryptocurrency trading and consider the regulatory and ethical implications of their trading strategies.

