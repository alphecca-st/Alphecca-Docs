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

    Click the **Start** button. The bot will automatically monitor and freeze accounts that meet the conditions.
5. Click the **Transaction Logs** tab to view bot logs. Here you can monitor transaction signatures and account statuses in real-time.

## How does Auto Freeze work?

**Auto Freeze** monitors the blockchain in real-time and automatically freezes new token holder accounts that meet your specified conditions. All accounts are **automatically** targeted for freezing except those on the whitelist and those that don't meet the minimum balance requirement.

## Why is account freezing needed?

Token account freezing is useful in the following situations:

* **Token Distribution Management**: Restrict token movement until a specific point during airdrops or token distribution events to ensure fair distribution.
* **Vesting Schedule Management**: Enforce vesting periods for team tokens or investor tokens to comply with agreed-upon lockup periods.
* **Project Stability Maintenance**: Temporarily prevent token transfers during critical updates or migration periods to ensure safe transitions.
* **Compliance Requirements**: Meet regulatory requirements by implementing necessary transfer restrictions for specific token holders.
