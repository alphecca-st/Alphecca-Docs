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
#### [https://alphecca.io/token-creator/binance](https://alphecca.io/token-creator/binance)
{% endhint %}



## How to Create a Token

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner.

### Step 2: Basic Information (Required)

| Field    | Description                              |
| -------- | ---------------------------------------- |
| Name     | The full name of your token              |
| Symbol   | The token's ticker symbol (abbreviation) |
| Decimals | The decimal precision of your token      |
| Supply   | The total number of tokens to be issued  |

### Step 3: Advanced Options

#### Tax Settings

Configure transaction fees that are sent to a designated wallet.

| Field        | Description                    |
| ------------ | ------------------------------ |
| Buy Tax      | Fee applied when buying (%)    |
| Sell Tax     | Fee applied when selling (%)   |
| Transfer Tax | Fee applied on transfers (%)   |
| Tax Wallet   | Wallet address to receive fees |

{% hint style="info" %}
Buy/Sell Tax requires creating a liquidity pool through Alphecca's Create Liquidity Pool page.&#x20;
{% endhint %}

{% hint style="info" %}
Can be modified for free anytime via Tax Settings page.
{% endhint %}

#### Anti Bot Settings

Prevent bot activities by limiting transaction frequency.

| Field            | Description                                                |
| ---------------- | ---------------------------------------------------------- |
| Max Tx Per Block | Maximum transactions per wallet per block (0 = no limit)   |
| Active Duration  | How long this feature stays active (hours) (0 = permanent) |

{% hint style="info" %}
Can be modified for free anytime via Anti Bot Settings page.
{% endhint %}

#### Anti Whale Settings

Prevent large holders from manipulating the market.

| Field             | Description                                                |
| ----------------- | ---------------------------------------------------------- |
| Max Buy Amount    | Maximum tokens per buy transaction (0 = no limit)          |
| Max Sell Amount   | Maximum tokens per sell transaction (0 = no limit)         |
| Max Wallet Amount | Maximum tokens a wallet can hold (0 = no limit)            |
| Buy Cooldown      | Minimum time between buys (minutes)  (0 = no limit)        |
| Sell Cooldown     | Minimum time between sells (minutes)  (0 = no limit)       |
| Active Duration   | How long this feature stays active (days)  (0 = permanent) |

{% hint style="info" %}
Buy/Sell limits are based on liquidity pool transactions. You must create a liquidity pool through Alphecca's Create Liquidity Pool page for these limits to take effect.
{% endhint %}

{% hint style="info" %}
Can be modified for free anytime via Anti Whale Settings page.
{% endhint %}

#### Built-in Features

| Feature     | Description                                     |
| ----------- | ----------------------------------------------- |
| Blacklist   | Block specific wallet addresses from trading    |
| Mintable    | Allow minting additional tokens after creation  |
| Pausable    | Enable pausing all token transfers              |
| Auto Verify | Automatically verify contract on block explorer |

{% hint style="warning" %}
Tokens created with these features disabled cannot use them later.
{% endhint %}

### Step 4: Create Token

Click the 'Create Token' button and approve the transaction in your wallet.

### Step 5: Check Transaction Logs

After transaction is confirmed, go to the 'Transaction Logs' tab to view your token contract address and transaction hash. Click the explorer icon to verify directly on the block explorer.

### Frequently Asked Questions

#### What kind of token does Alphecca create?

Alphecca creates standard ERC-20 tokens that are fully compatible with all decentralized exchanges (DEXs), wallets, and DeFi protocols. Your token can be traded on Uniswap, PancakeSwap, SushiSwap, and any other ERC-20 compatible platform.

#### Can I trade the token immediately after creation?

No. After creating the token, you need to create a liquidity pool to enable trading. Please use Alphecca's Create Liquidity Pool page to set this up.

#### What is Tax System?

Tax Settings allows you to automatically collect fees whenever your token is traded or transferred on-chain. Collected fees are sent directly to your designated wallet.

**Example:** If the transfer fee is set to 1% and User A sends 1,000 tokens to User B, 10 tokens (1%) are automatically collected to the fee receiver wallet.

#### What are the benefits of Anti-Bot?

Anti-Bot limits the number of transactions per wallet per block, effectively defending against sandwich attacks and preventing bots from exploiting your trades.

#### What are the benefits of Anti-Whale?

Anti-Whale protects your community by preventing large-scale market manipulation:

* **Max Buy/Sell Limit:** Limits how many tokens can be bought or sold in a single transaction
* **Wallet Limit:** Limits how many tokens a single wallet can hold
* **Buy/Sell Cooldown:** Sets minimum waiting time between transactions

These restrictions help maintain price stability and create a fair trading environment for all holders.

#### Can I modify Tax / Anti-Bot / Anti-Whale settings after creation?

Yes. A one-time fee of 0.006 ETH is charged only during initial setup. After that, all changes are completely free through their respective settings pages.

#### Do I need to verify the contract manually?

If you enable Auto Verify, the contract will be automatically verified on the block explorer. Otherwise, you can verify it manually through the block explorer's verification page.

#### I can't see my created token in my wallet app.

ERC-20 tokens are not automatically detected by wallet apps. You need to manually import the token by entering the token contract address through the 'Import Token' feature in your wallet. Alternatively, you can view all tokens held by your wallet by entering your wallet address on the chain's block explorer.
