---
icon: landmark-magnifying-glass
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

# Batch Pump Reclaim PDA

Check the Pump PDAs of multiple wallets and easily reclaim the rent fees.

{% hint style="success" %}
#### [https://alphecca.io/batch-pump-recover-rent](https://alphecca.io/batch-pump-recover-rent)
{% endhint %}

## How to Use Batch **Recover SOL**?&#x20;

1. Open the **Batch Pump Relaim Rent** page.
2. Import reclaim wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
3. Select **Pump PDA**:\
   \- **Total**: Closes both Pump.Fun PDA and PumpSwap PDA.\
   \- **Pump.Fun**: Closes Pump.Fun PDA.\
   \- **Pump.Swap**: Closes Pump.Swap PDA.
4. Select wallets for reclaim.
5. (Optional) Enter Reclaim SOL to Specified Address.\
   \- This collects rent fees into a single wallet.
6. (Optional) Enter Pay Gas Fee.\
   \- This is the wallet that will pay the network gas fees.
7. **Click the "Recover Rent" button** to proceed with the transactions.

{% hint style="info" %}
**NOTE**

\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.

\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}

## What is the purpose of the Batch Recover SOL page?

As of August 2025, due to changes in Pump.Fun policy, when a wallet purchases Pump.Fun (Pump AMM) tokens, a one-time PDA rent fee of **0.0018444 SOL** is charged. This applies separately to both the Pump.Fun program and the Pump.Swap program. This rent fee cannot be refunded directly through Pump.Fun — each wallet owner must close the account themselves to reclaim it. Alphecca’s Reclaim Pump PDA page helps you easily check the Pump PDAs in your wallet and reclaim the rent fee without any coding.

## Can I reclaim rent fees even if the wallet's SOL balance is zero?

Yes, you can. Enable the **Pay Gas Fee** option and enter the private key of the wallet that will pay the Network Gas Fees.
