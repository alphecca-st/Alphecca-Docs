---
icon: merge
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

# Batch Collection (Many to One)

Easily collect tokens from multiple wallets and send them to your main wallet with a single click.

{% hint style="success" %}
#### [https://alphecca.io/multi-collector](https://alphecca.io/multi-collector)
{% endhint %}

## How to Use Batch Collection (Many to One)&#x20;

1. Open the Batch Collection (Many to One) page.
2. Select the wallet you’ll use to send tokens.\
   \- If you're using a wallet extension like Phantom, choose **Connected Wallet** and click the **Connect Wallet** button in the top-right corner to connect.\
   \- If you'd rather input your private key manually, choose **Other Wallet** and enter your key directly.
3. **Enter the token mint address** you want to collect.
4. Import recipient wallet addresses.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of wallet addresses.\
   \- Or simply paste a list of addresses directly into the input field.
5. Enter the amount to send\
   \- You can manually input the amount for each recipient wallet.\
   \- Or use the **Amount** button to apply a fixed or random amount to all recipients at once.
6. **Click the "Send Tokens" button** to proceed with the transaction.

## How Much Does Multi Sender (One to Many) Cost?

The total cost, including the service fee, is calculated **per transaction batch**:

* **Per Batch:**\
  `Network Gas Fee (0.000005 SOL) + Service Fee`
* **Maximum addresses per batch:**
  * **SOL Transfers:** up to **18** addresses
  * **SPL Token Transfers:** up to **8** addresses.
* **Example:**\
  &#x20; Sending **SOL** to 100 wallets\
  &#x20;   → Requires **6 transactions**\
  &#x20;   → **Total Fees:** `6 × (Network Gas Fee + Service Fee)`\
  &#x20;Sending **SPL-Token** to 100 wallets\
  &#x20;   → Requires **13 transactions**\
  &#x20;   → **Total Fees:** `13 × (Network Gas Fee + Service Fee)`

{% hint style="info" %}
NOTE\
\-  A service fee is charged per transaction. You will **not** be charged for failed transactions.\
&#x20;\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.
{% endhint %}
