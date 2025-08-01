---
icon: paper-plane-top
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

# Multi Sender (One to Many)

**Distribute your tokens to multiple addresses quickly and easily.**

{% hint style="success" %}
#### [https://alphecca.io/multi-sender](https://alphecca.io/multi-sender)
{% endhint %}

## How to Use Multi Sender (One to Many)?&#x20;

1. Open the Multi Sender (One to Many) page.
2. **Enter the token mint address** you want to send.
3. Select the wallet you’ll use to send tokens.\
   \- If you're using a wallet extension like Phantom, choose **Connected Wallet** and click the **Connect Wallet** button in the top-right corner to connect.\
   \- If you'd rather input your private key manually, choose **Other Wallet** and enter your key directly.
4. Import recipient wallet addresses.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of wallet addresses.\
   \- Or simply paste a list of addresses directly into the input field.
5. Enter the amount to send\
   \- You can manually input the amount for each recipient wallet.\
   \- Or use the **Amount** button to apply a fixed or random amount to all recipients at once.
6. **Click the "Send Tokens" button** to proceed with the transaction.

{% hint style="info" %}
**NOTE**\
\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.\
\- All Service Fees and Network Gas Fees are charged from the sender wallets.\
\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}

## How Much Does Multi Sender (One to Many) Cost?

The total cost, including the service fee, is calculated **per transaction batch**:

*   **Per Transaction Batch:**\
    `Network Gas Fee + Service Fee`&#x20;

    #### &#x20;\* Network Gas Fee

    * **Connected Wallets** (e.g. via wallet apps like Phantom):\
      The fee is dynamically estimated by the wallet app and is typically **less than 0.0001 SOL** per transaction.
    * **Other Wallets** (manual private key input):\
      A fixed fee of **0.000005 SOL** is applied per transaction, with **no priority fee**.
* **Maximum addresses per batch:**
  * **SOL Transfers:** up to **18** addresses
  * **SPL Token Transfers:** up to **8** addresses.
* **Example:**\
  &#x20; Sending **SOL** to 100 wallets\
  &#x20;   → Requires **6 transactions**\
  &#x20;   → **Total Fees:** `6 × (Network Gas Fee + Service Fee)`\
  &#x20; Sending **SPL-Token** to 100 wallets\
  &#x20;   → Requires **13 transactions**\
  &#x20;   → **Total Fees:** `13 × (Network Gas Fee + Service Fee)`
