---
icon: octagon-xmark
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

# Unfreeze Account

**Unfreeze token accounts to block all token activity — maintain full control over your token.**

{% hint style="success" %}
#### [https://alphecca.io/unfreeze](https://alphecca.io/unfreeze)
{% endhint %}

## How to Use Unfreeze Token Accounts?&#x20;

1. Click the **Connect Wallet** button in the top-right corner to connect.&#x20;
2. Select the **token mint address** from your wallet's token list.
   * The green checkmark indicates you have freeze authority for that token.
   * If you see a red X, you don't have freeze authority for that token.
3. **Import wallet addresses** by clicking the Import button and entering the public keys of accounts you want to freeze.
   * You can import multiple addresses at once by separating them with line breaks.
4. **Select accounts to unfreeze** using the checkboxes or the dropdown menu options:
   * Select All - selects all imported accounts
   * Select Unfreezable - automatically selects only accounts that can be frozen
   * Deselect - clears all selections
5. Click the **Unfreeze Accounts** button and approve the transaction in your wallet app.
6. When transactions are completed, the **transaction signatures** will be displayed and account statuses will update to "Unfreeze Success".

## Why can't I freeze certain tokens?

Only tokens where you hold the freeze authority can be frozen. The green checkmark next to the token selection indicates you have freeze authority for that token. If you see a red X, it means either the freeze authority has been revoked or is held by another wallet. You can only freeze accounts for tokens you created or where freeze authority was transferred to you.

## What happens after freezing accounts?

The selected token accounts become frozen and cannot transfer tokens until they are unfrozen by the freeze authority. Alphecca automatically identifies which accounts are freezable and filters out:

* Accounts with no Associated Token Account (ATA)
* Accounts with zero token balance
* Accounts already frozen

The freeze action is permanent until reversed and costs 0.001 SOL per account plus network transaction fees. Only accounts that can actually be frozen will be processed, ensuring efficient transaction execution.
