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

# Auto Freeze Accounts

**Freeze token accounts to block all token activity — maintain full control over your token.**

{% hint style="success" %}
#### [https://alphecca.io/auto-freeze](https://alphecca.io/auto-freeze)
{% endhint %}

## How to Use Auto Freeze Accounts?&#x20;

1. Click the Connect Wallet button in the top-right corner to connect.
2.  **Select Token**

    Select the token mint address from your wallet's token list.

    * **Green checkmark**: Indicates you have freeze authority for that token.
    * **Red X**: You don't have freeze authority for that token.
3.  **Filter Settings (Optional)**

    **Additional Filter Options:**

    * **Whitelist Registration (Optional)**: Click the Import button and enter the public keys of accounts you want to exclude from freezing. You can import multiple addresses at once by separating them with line breaks. Whitelisted addresses are automatically excluded from freeze targets.
    * **Minimum Balance Setting (Optional)**: You can set a filter to freeze only accounts with a token balance above a specific amount.

    **Note**: Both whitelist registration and minimum balance settings are **optional**. You can use them as needed or skip them.
4.  **Execute Auto Freeze**

    Click the **Start** button and approve the transaction in your wallet app.
5. Click the **Transaction Logs** tab to view bot logs. Here you can monitor transaction signatures and account statuses in real-time.

## Why can't I freeze certain tokens?

Only tokens where you hold the freeze authority can be frozen. The green checkmark next to the token selection indicates you have freeze authority for that token. If you see a red X, it means either the freeze authority has been revoked or is held by another wallet. You can only freeze accounts for tokens you created or where freeze authority was transferred to you.

## What happens after freezing accounts?

The selected token accounts become frozen and cannot transfer tokens until they are unfrozen by the freeze authority. Alphecca automatically identifies which accounts are freezable and filters out:

* Accounts with no Associated Token Account (ATA)
* Accounts with zero token balance
* Accounts already frozen

The freeze action is permanent until reversed and costs 0.001 SOL per account plus network transaction fees. Only accounts that can actually be frozen will be processed, ensuring efficient transaction execution.
