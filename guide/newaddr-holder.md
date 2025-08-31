---
icon: users-between-lines
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

# New Address Buy (↑Holders)

**Auto-generate new wallets to instantly increase the number of token makers.**

{% hint style="success" %}
#### [https://alphecca.io/newaddr-holder](https://alphecca.io/newaddr-holder)
{% endhint %}

## How to Use **New Address Buy (↑Holders)**?&#x20;

1. Open the **New Address Buy (↑Holders)** page.
2. **Enter the token mint address** to run the holder bot on.\
   \- **SPL 2022 Program** Token Cannot be Processed.
3. Enter the private key of the wallet that will pay for the service fees, network gas fees and Jito tip.\
   \- The SOL balance of the payment wallet must be greater than\
   **maker count × (Buying Amount + Service Fees + Jito Tip + 0.00001 SOL) + 0.005 SOL.**
4. Select or enter the **number of holders** to generate.
5. Click the Generate Button.\
   \- The wallet's public and private key pair will be automatically downloaded.\
   \- **Keep this file safe — you will need it to collect the purchased tokens or reclaim ATA rent fees after the project ends.**
6. Enter the buying amount per holder\
   \- buying amount must be **at least 0.00001 SOL**
7. Select or Enter the Jito Tip\
   \- Jito Tip must be **at least 0.000001 SOL**
8. Click the **Start** button to activate the bot.
9. You can monitor the progress of the bot cycle through the **Bot Logs**.

{% hint style="info" %}
**NOTE**

\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.

\- If you **close** or **refresh** the page while the bot is running, the bot operation will stop.

\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}

## What is the purpose of the **New Address Buy (↑Holders)**?

**New Address Buy (↑Holders)** is used to rapidly increase the number of Holders in a short period. Since the number of Holders is a critical factor in DEX Tools’ popular token algorithm, this feature helps enhance the token’s visibility and credibility.

## Why use a new address instead of an existing wallet?

The reason for using a new address instead of an existing wallet is to prevent past labels or transaction history from being carried over to the new chart. This helps avoid artificial chart patterns (bubbles) and reduces suspicion from potential investors

## How does the bot work?

The bot operates as follows:

* **Transfer SOL**: The payment wallet sends the required SOL (for purchasing) to a newly generated wallet, along with the Jito tip and service fees.
* **Token Purchase**: The new wallet uses the received SOL to buy the target token.
* **Transfer Remaining SOL**: The new wallet sends any remaining SOL back to the payment wallet.
* **Bundled Execution**: These transactions are bundled into a single atomic unit and repeated according to the selected Holder count.

{% hint style="warning" %}
**NOTE : Keep the holder wallet list safe.**

\- Use Alphecca’s **Bundled Sell Page** or **Batch Collection Page** to manage the tokens purchased by these wallets.

\- After the project ends, close each wallet’s token ATA account through the **Batch Recover SOL Page** to recover **0.00203928 SOL** per wallet.
{% endhint %}
