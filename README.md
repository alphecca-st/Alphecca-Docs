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

Launch your own ERC-20 token instantly — no coding required.

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

| Field       | Description                     |
| ----------- | ------------------------------- |
| Description | Brief description of your token |
| Website     | Official website URL            |
| Twitter     | Twitter/X profile URL           |
| Telegram    | Telegram group URL              |

{% hint style="info" %}
Source code preview is displayed on the right side.
{% endhint %}

{% hint style="info" %}
This information is displayed first when viewing your token on block explorers (Etherscan, Basescan, etc.).
{% endhint %}

### Step 3: Advanced Options

#### Tax Settings

Configure transaction fees that are sent to a designated wallet.

| Field               | Description                    |
| ------------------- | ------------------------------ |
| Buy Fee             | Fee applied when buying (%)    |
| Sell Fee            | Fee applied when selling (%)   |
| Transfer Fee        | Fee applied on transfers (%)   |
| Fee Receiver Wallet | Wallet address to receive fees |

{% hint style="info" %}
Buy/Sell fees are based on liquidity pool transactions. When using Alphecca's Create Liquidity Pool page, the pool address is automatically registered to the token contract and Buy/Sell fees are applied.
{% endhint %}

{% hint style="info" %}
Can be modified for free anytime via Tax Settings page.
{% endhint %}

{% hint style="warning" %}
Most token swaps go through swap aggregators (wallet apps, 1inch, etc.), which results in 'Transfer + Buy/Sell fees' being applied. Please consider this when setting fee rates. To prevent double taxation, set the transfer fee to 0.
{% endhint %}

#### Anti Bot Settings

Prevent bot activities by limiting transaction frequency.

| Field                      | Description                                                           |
| -------------------------- | --------------------------------------------------------------------- |
| Max Transactions Per Block | <p>Maximum transactions per wallet per block <br>(0 = no limit)</p>   |
| Active Duration            | <p>How long this feature stays active (hours) <br>(0 = permanent)</p> |

{% hint style="info" %}
The creator wallet is automatically whitelisted.
{% endhint %}

{% hint style="info" %}
Can be modified for free anytime via Anti Bot Settings page.
{% endhint %}

{% hint style="info" %}
Anti-Bot works correctly regardless of whether swap aggregators (wallet apps, 1inch, etc.) are used.
{% endhint %}

#### Anti Whale Settings

Prevent large holders from manipulating the market.

| Field             | Description                                                           |
| ----------------- | --------------------------------------------------------------------- |
| Max Buy Amount    | <p>Maximum tokens per buy transaction <br>(0 = no limit)</p>          |
| Max Sell Amount   | <p>Maximum tokens per sell transaction <br>(0 = no limit)</p>         |
| Max Wallet Amount | <p>Maximum tokens a wallet can hold <br>(0 = no limit)</p>            |
| Buy Cooldown      | <p>Minimum time between buys (minutes)  <br>(0 = no limit)</p>        |
| Sell Cooldown     | <p>Minimum time between sells (minutes)  <br>(0 = no limit)</p>       |
| Active Duration   | <p>How long this feature stays active (days)  <br>(0 = permanent)</p> |

{% hint style="info" %}
Buy/Sell limits and cooldowns are based on liquidity pool transactions. When using Alphecca's Create Liquidity Pool page, the pool address is automatically registered to the token contract and Buy/Sell limits and cooldowns are applied.
{% endhint %}

{% hint style="info" %}
The creator wallet is automatically whitelisted.
{% endhint %}

{% hint style="info" %}
Can be modified for free anytime via Anti-Whale Settings page.
{% endhint %}

{% hint style="info" %}
Buy/Sell limits and cooldowns work correctly regardless of whether swap aggregators (wallet apps, 1inch, etc.) are used.
{% endhint %}

#### Built-in Features

| Feature     | Description                                     |
| ----------- | ----------------------------------------------- |
| Blacklist   | Block specific wallet addresses from trading    |
| Mintable    | Allow minting additional tokens after creation  |
| Pausable    | Enable pausing all token transfers              |
| Auto Verify | Automatically verify contract on block explorer |

{% hint style="warning" %}
Blacklist, Mint, and Pause features cannot be enabled later if disabled during token creation.
{% endhint %}

### Step 4: Create Token

Click the 'Create Token' button and approve the transaction in your wallet.<br>

1. **Deploying Contract:** Your token is being deployed to the blockchain
2. **Contract Deployed:** Deployment complete. Your token address will be displayed
3. **Verifying:** The contract is being verified on the block explorer
4. **Verified:** Verification complete

{% hint style="warning" %}
Closing the modal during verification may cause verification to fail. If this happens, you can verify manually on the 'Verify Token' page.
{% endhint %}

### Step 5: Check Transaction Logs

After transaction is confirmed, go to the 'Transaction Logs' tab to view your token contract address and transaction hash. Click the explorer icon to verify directly on the block explorer.

### Frequently Asked Questions

#### What kind of token does Alphecca create?

Alphecca creates standard ERC-20 tokens that are fully compatible with all decentralized exchanges (DEXs), wallets, and DeFi protocols. Your token can be traded on Uniswap, PancakeSwap, SushiSwap, and any other ERC-20 compatible platform.

#### Can I trade the token immediately after creation?

No. After creating the token, you need to create a liquidity pool to enable trading. Please use Alphecca's Create Liquidity Pool page to set this up.

#### What is Custom Metadata?

Standard ERC-20 tokens do not embed metadata such as images, descriptions, or social links in the contract. Alphecca permanently records this metadata as comments in the contract source code. Anyone can verify your token's official information through the verified source code on block explorers.

#### What is Tax Settings?

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

Yes. A one-time fee is charged only during initial setup. After that, all changes are completely free through their respective settings pages.

#### How is contract verification handled?

All tokens created on Alphecca are automatically verified on block explorers.

#### I can't see my created token in my wallet app.

ERC-20 tokens are not automatically detected by wallet apps. You need to manually import the token by entering the token contract address through the 'Import Token' feature in your wallet. Alternatively, you can view all tokens held by your wallet by entering your wallet address on the chain's block explorer.
