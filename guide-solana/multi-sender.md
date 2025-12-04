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
#### [https://alphecca.io/multi-sender](https://alphecca.io/multi-sender)
{% endhint %}

## How to Use Multi Sender

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Enter Token Address

Enter the token mint address you want to send. Leave empty for native SOL transfers.

### Step 3: Select Sender Wallet

| Option           | Description                                        |
| ---------------- | -------------------------------------------------- |
| Connected Wallet | Use your connected wallet extension (e.g. Phantom) |
| Other Wallet     | Manually enter your private key                    |

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

***

### Frequently Asked Questions

#### Why use Multi Sender?

Multi Sender allows you to distribute tokens to hundreds of wallets in just a few clicks. Perfect for airdrops, community rewards, team token distribution, and marketing campaigns.

#### How much does Multi Sender cost?

| Transfer Type      | Max Addresses per Batch |
| ------------------ | ----------------------- |
| SOL Transfer       | Up to 18 addresses      |
| SPL Token Transfer | Up to 8 addresses       |

Cost per batch: `Network Gas Fee + Service Fee`

**Example:**

* Sending SOL to 100 wallets → 6 batches → `6 × (Gas + Service Fee)`
* Sending SPL Token to 100 wallets → 13 batches → `13 × (Gas + Service Fee)`

#### What happens if a transaction fails?

No costs (service fee or gas fees) will be charged for failed transactions.
