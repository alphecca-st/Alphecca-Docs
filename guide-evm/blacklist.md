---
icon: ban
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

# Blacklist Management

Block all token activities by adding malicious wallets to the blacklist.

{% hint style="success" %}
#### [https://alphecca.io/blacklist/binance](https://alphecca.io/blacklist/binance)
{% endhint %}

## How to Manage Blacklist

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Token Address

Select the token contract address you want to configure Anti Whale settings for.

{% hint style="info" %}
Only the token owner can manage the blacklist. Tokens with renounced ownership or disabled blacklist cannot be managed.
{% endhint %}

### Step 3: Check Current Blacklist

The current list of blacklisted addresses is displayed. Click the 'Remove' button for addresses you want to remove.

### Step 4: Add Addresses

Enter the wallet address to add to the blacklist and click the 'Add' button. You can add multiple addresses at once.

### Step 5: Apply Changes

Click the 'Apply' button and approve the transaction in your wallet. Additions and removals are processed simultaneously in one transaction.

{% hint style="warning" %}
Blacklisted wallets are blocked from all token activities including buying, selling, and transfers.
{% endhint %}

***

### Frequently Asked Questions

#### What is blacklist?

Blacklist is a feature that blocks token activities for specific wallet addresses. Wallets on the blacklist cannot buy, sell, or transfer the token.

#### Who can manage the blacklist?

Only the token owner can manage it. The blacklist feature must also be enabled when the token was created. Tokens with renounced ownership or disabled blacklist cannot be managed.

#### When should I use the blacklist?

Use it to block malicious wallets, prevent hacking damage, or isolate scam addresses. For example, you can block wallets when detecting bot attacks, abnormal trading patterns, or stolen fund movement attempts.

#### Can I add or remove multiple addresses at once?

Yes. Specify addresses to add and remove, then click the 'Apply' button to process them simultaneously in one transaction.

#### Can I trade immediately after being removed from the blacklist?

Yes. Once removed from the blacklist, the wallet can immediately perform all token activities.

#### Is there a fee for blacklist registration?

Free. You only pay for gas fees.
