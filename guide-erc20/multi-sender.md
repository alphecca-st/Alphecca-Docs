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

# Multi Sender

**Distribute your tokens to multiple addresses quickly and easily.**

{% hint style="success" %}
#### [https://alphecca.io/multi-sender/binance](https://alphecca.io/multi-sender/binance)
{% endhint %}

## How to Use Multi Sender

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Token Address

Select the token you want to send. Choose native token or search for your token.

### Step 3: Select Sender Wallet

| Option           | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| Connected Wallet | Use your connected wallet extension (e.g. Phantom, MetaMask) |
| Other Wallet     | Manually enter your private key                              |

{% hint style="info" %}
Alphecca does not store your private keys. They are used solely for local signing on your device.
{% endhint %}

### Step 4: Import Recipients

| Method       | Description                                                    |
| ------------ | -------------------------------------------------------------- |
| File Upload  | Upload a `.csv`, `.txt`, or `.json` file with wallet addresses |
| Manual Input | Paste a list of addresses directly into the input field        |

### Step 5: Set Amounts

| Option        | Description                                   |
| ------------- | --------------------------------------------- |
| Manual Input  | Enter amount for each recipient individually  |
| Fixed Amount  | Apply the same amount to all recipients       |
| Random Amount | Apply random amounts within a specified range |

### Step 6: Send Tokens

Click the 'Send Tokens' button and approve the transaction in your wallet.

{% hint style="info" %}
**Transaction Approvals Required:**

* **Native Token (ETH, BNB, POL, etc.):** 1 transaction
  * 1x Multi Send
* **ERC-20 Token:** 2 transactions
  * 1x Token Approve
  * 1x Multi Send
{% endhint %}

***

### Frequently Asked Questions

#### What is Multi Sender?

Multi Sender allows you to send tokens to multiple wallets in a single transaction. It's useful for airdrops, team token distribution, and community reward payouts.

#### How many wallets can I send to at once?

You can send to up to 500 wallets in a single transaction. If you need to send to more wallets, it will automatically be split into multiple transactions.

#### What tokens can I send?

You can send native tokens (ETH, BNB, AVAX, etc.) and all ERC-20 tokens.

#### How do I enter the recipient address list?

There are two methods:

* **File Upload:** Upload a .csv, .txt, or .json file
* **Manual Input:** Paste the address list directly into the input field

#### What are the amount setting options?

* **Manual Input:** Enter amount for each recipient individually
* **Fixed Amount:** Apply the same amount to all recipients
* **Random Amount:** Apply random amounts within a specified range

#### Do I need to approve before sending ERC-20 tokens?

Yes. To send ERC-20 tokens, you must first approve the Multi Sender contract to use your tokens. Transfer is possible after the approval transaction.

#### How is the service fee calculated?

The service fee is calculated based on the number of addresses you're sending to. The fee is paid in native tokens.

#### What happens if the transaction fails?

If the transaction fails, no service fee is charged.

Need help? Contact support<br>
