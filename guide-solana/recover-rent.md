---
icon: clipboard-medical
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

# Reclaim ATA

**Reclaim ATA Rent 0.00203928 SOL by recovering rent from unused token accounts**

{% hint style="success" %}
#### [https://alphecca.io/recover-rent](https://alphecca.io/recover-rent)
{% endhint %}

## How to Use **Reclaim ATA**?&#x20;

1. Open the **Reclaim ATA** page.
2. Click the **Connect Wallet** button in the top-right corner to connect.
3. Click the **Refresh Button** to the right of the wallet address to load the token lists.
4. **Select the tokens** for which you want to close the ATA accounts.
5. Click the **Recover SOL button** and approve the transaction in your wallet app.

{% hint style="warning" %}
**NOTE**&#x20;

**Tokens that have been burned cannot be restored. Please double-check carefully before using this page**.
{% endhint %}

## What is the purpose of the Reclaim ATA page?

To hold tokens in any Solana wallet, an **ATA (Associated Token Account)** address for that token is required. Creating this ATA incurs a rent fee of 0.00203928 SOL. Even when the token balance reaches zero, the ATA account is not automatically deleted.

Alphecca’s Recover SOL feature allows you to close unused token ATA accounts and reclaim the **0.00203928 SOL** rent fee.

## What happens to tokens with a non-zero token balance?

Tokens with a non-zero balance will be completely **burned** before the ATA account is closed. Please carefully verify that the tokens are no longer needed before clicking the Recover SOL button.
