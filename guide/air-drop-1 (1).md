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

## How to Use Batch Collection (Many to One)?&#x20;

1. Open the **Batch Collection (Many to One)** page.
2. **Enter the token mint address** you want to collect.
3. **Enter the receiving Address.**
4. Import sender wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
5. Enter the amount to collect\
   \- You can use the **Amount** button to apply a fixed or total amount to all sender wallets at once.
6. **Click the "Collect Tokens" button** to proceed with the transaction.

{% hint style="info" %}
NOTE\
\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.\
\- All Service Fees and Network Gas Fees are charged from the connected wallet.\
\- You will **not** be charged for failed transactions.
{% endhint %}

## How Much Does Batch Collection (Many to One) Cost?

The total cost, including the service fee, is calculated **per Address**:

* **Per Addresses:**\
  `Service Fee`&#x20;
*   **Per Transaction Batch:**\
    `Network Gas Fee`

    #### &#x20;\* Network Gas Fee

    * The fee is dynamically estimated by the wallet app and is typically **less than 0.0001 SOL** per transaction.
* **Maximum addresses per batch:**
  * **SOL Transfers:** up to **8** addresses
  * **SPL Token Transfers:** up to **5** addresses.
* **Example:**\
  &#x20; Collecting **SOL** from 100 wallets\
  &#x20;   → Requires **13 transactions**\
  &#x20;   → **Total Fees:** `13 × (Network Gas Fee) + 100 × (Service Fee)`\
  &#x20; Collecting **SPL-Token** from100 wallets\
  &#x20;   → Requires **20 transactions**\
  &#x20;   → **Total Fees:** `20 × (Network Gas Fee) + 100 × (Service Fee)`
