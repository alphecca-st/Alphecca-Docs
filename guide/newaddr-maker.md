---
icon: users-line
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

# New Address Buy (↑Makers)

**Auto-generate new wallets to instantly increase the number of token makers.**

{% hint style="success" %}
#### [https://alphecca.io/newaddr-maker](https://alphecca.io/newaddr-maker)
{% endhint %}

## How to Use **New Address Buy (↑Makers)**?&#x20;

1. Open the **New Address Buy (↑Makers)** page.
2. **Enter the token mint address** to run the maker bot on.
3. Enter the private key of the wallet that will pay for the service fees, network gas fees and Jito tip.\
   \- The SOL balance of the payment wallet must be greater than\
   **maker count × (Buying Amount + Service Fees + Jito Tip + 0.00001 SOL) + 0.005 SOL.**
4. Select or enter the **number of makers** to generate.
5. Enter the buying amount per maker\
   \- buying amount must be **at least 0.00001 SOL**
6. Select or Enter the Jito Tip\
   \- Jito Tip must be **at least 0.000001 SOL**
7. Click the **Start** button to activate the bot.
8. You can monitor the progress of the bot cycle through the **Bot Logs**.

{% hint style="info" %}
**NOTE**

\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.

\- If you **close** or **refresh** the page while the bot is running, the bot operation will stop.

\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}

## What is the purpose of the **New Address Buy (↑Makers)**?

**New Address Buy (↑Makers)** is used to rapidly increase the number of Makers in a short period. Since the number of Makers is a critical factor in DEX Tools’ popular token algorithm, this feature helps enhance the token’s visibility and credibility.

## Why use a new address instead of an existing wallet?

The reason for using a new address instead of an existing wallet is to prevent past labels or transaction history from being carried over to the new chart. This helps avoid artificial chart patterns (bubbles) and reduces suspicion from potential investors

## How does the bot work?

The bot operates as follows:

* **Transfer SOL**: The payment wallet sends the required SOL (for purchasing) to a newly generated wallet, along with the Jito tip and service fees.
* **Token Purchase**: The new wallet uses the received SOL to buy the target token.
* **Token Transfer**: All purchased tokens are immediately transferred back to the payment wallet.
* **Close and Transfer Remaining SOL**: The new wallet closes its token ATA (Associated Token Account) and sends any remaining SOL back to the payment wallet.
* **Bundled Execution**: These transactions are bundled into a single atomic unit and repeated according to the selected Maker count.
