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

# Batch Reclaim ATA

**Burn tokens and close multiple wallets in one click to reclaim SOL rent efficiently.**

{% hint style="success" %}
#### [https://alphecca.io/batch-recover-rent](https://alphecca.io/batch-recover-rent)
{% endhint %}

## How to Use Batch **Reclaim ATA**?&#x20;

1. Open the **Batch Reclaim ATA** page.
2. Import reclaim wallet **private keys**.\
   \- You can upload a `.csv`, `.txt`, or `.json` file with a single column of private keys.\
   \- Or simply paste a list of private keys directly into the input field.
3. Select **TOTAL ACCOUNTS** or **IDLE ACCOUNTS**.\
   \- **TOTAL ACCOUNTS:** Burn all tokens in the accounts and then close them.\
   \- **IDLE ACCOUNTS:** Close only the accounts with a zero balance.
4. Select wallets for reclaim.
5. (Optional) Enter Reclaim SOL to Specified Address.\
   \- This collects rent fees into a single wallet.
6. (Optional) Enter Pay Gas Fee.\
   \- This is the wallet that will pay the network gas fees.
7. **Click the "Recover Rent" button** to proceed with the transactions.

{% hint style="info" %}
**NOTE**\
\- Alphecca does **not** store your private keys; they are used solely for local signing on your device.\
\- In the case of failed transactions, **no costs** (Service Fee, Network Gas Fees) will be charged.
{% endhint %}

{% hint style="warning" %}
**NOTE** \
**Tokens that have been burned cannot be restored. Please double-check carefully before using this page**.
{% endhint %}

## What is the purpose of the Batch **Reclaim ATA** page?

To hold tokens in any Solana wallet, an **ATA (Associated Token Account)** address for that token is required. Creating this ATA incurs a rent fee of **0.00203928 SOL**. Even when the token balance reaches zero, the ATA account is not automatically deleted.

Alphecca’s **Batch Recover SOL** feature allows you to close unused token ATA accounts across multiple wallets at once with a single click, enabling you to efficiently reclaim the **0.00203928 SOL** rent fees from all selected accounts.

## What happens to tokens with a non-zero token balance?

Tokens with a non-zero balance will be completely **burned** before the ATA account is closed. Please carefully verify that the tokens are no longer needed before clicking the Recover SOL button.

## Can I reclaim rent fees even if the wallet's SOL balance is zero?

Yes, you can. Enable the **Pay Gas Fee** option and enter the private key of the wallet that will pay the Network Gas Fees.
