---
icon: coin-front
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

# Create Token

**Launch your own Solana token instantly — no coding required.**

{% hint style="success" %}
#### [https://alphecca.io/create-token](https://alphecca.io/create-token)
{% endhint %}

## How to Create a Token

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Basic Information (Required)

| Field       | Description                              |
| ----------- | ---------------------------------------- |
| Image       | The image for the token (max 1.5 MB)     |
| Name        | The full name of your token              |
| Symbol      | The token's ticker symbol (abbreviation) |
| Description | A description of your token              |
| Supply      | The total number of tokens to be issued  |
| Decimals    | The decimal precision of your token      |

### Step 3: Social Links (Optional)

| Field    | Description           |
| -------- | --------------------- |
| Website  | Project website URL   |
| Discord  | Discord server invite |
| Twitter  | Twitter profile URL   |
| Telegram | Telegram group invite |

### Step 4: Revoke Authorities (Optional)

| Authority     | Description                                  |
| ------------- | -------------------------------------------- |
| Revoke Freeze | Remove the ability to freeze token accounts  |
| Revoke Mint   | Remove the ability to mint additional tokens |
| Revoke Update | Remove the ability to update token metadata  |

{% hint style="info" %}
For tokens intended to be listed on Raydium, it is generally recommended to revoke freeze and mint permissions.
{% endhint %}

{% hint style="warning" %}
If metadata update permission is revoked, the token's name and logo cannot be changed afterward.
{% endhint %}

### Step 5: Create Token

Click the 'Create Token' button and approve the transaction in your wallet.

***

### Frequently Asked Questions

#### How much does it cost to create a token?

In addition to the service fee, approximately 0.019 SOL in extra costs will be incurred. These cover token ATA creation fees, minting fees, metadata fees, and other related expenses.

#### Can I trade the token immediately after creation?

No. After creating the token, you need to create a liquidity pool to enable trading. Please use Alphecca's Create Liquidity Pool page to set this up.
