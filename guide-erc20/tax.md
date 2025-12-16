---
icon: sack-dollar
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

# Tax Settings

Automatically collect fees on buy, sell, and transfer. Taxes are sent to your designated wallet.

{% hint style="success" %}
#### [https://alphecca.io/tax/binance](https://alphecca.io/tax/binance)
{% endhint %}

## How to Use Tax Settings

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Token Address

Select the token contract address you want to configure tax settings for.

{% hint style="warning" %}
This feature is only available for tokens created through Alphecca. Only the token creator can modify settings.
{% endhint %}

### Step 3: Configure Tax Rates

| Field               | Description                                   |
| ------------------- | --------------------------------------------- |
| Buy Fee             | Fee applied when buying (%)                   |
| Sell Fee            | Fee applied when selling (%)                  |
| Transfer Fee        | Fee applied on wallet-to-wallet transfers (%) |
| Fee Receiver Wallet | Wallet address to receive collected fees      |

{% hint style="info" %}
Buy/Sell fees are based on liquidity pool transactions. When using Alphecca's Create Liquidity Pool page, the pool address is automatically registered to the token contract and Buy/Sell fees are applied.
{% endhint %}

{% hint style="warning" %}
Most token swaps go through swap aggregators (wallet apps, 1inch, etc.), which results in 'Transfer + Buy/Sell fees' being applied. Please consider this when setting fee rates. To prevent double taxation, we recommend whitelisting swap aggregators or setting the transfer fee to 0.
{% endhint %}

### Step 4: Save Settings

Click the 'Set Tax' button and approve the transaction in your wallet.

{% hint style="info" %}
A one-time fee is charged only during initial setup. After that, all changes are completely free.
{% endhint %}

***

### Frequently Asked Questions

#### What is Tax Settings?

Tax Settings allows you to automatically collect fees whenever your token is traded or transferred on-chain. Collected fees are sent directly to your designated wallet.

**Example:** If the transfer fee is set to 1% and User A sends 1,000 tokens to User B, 10 tokens (1%) are automatically collected to the fee receiver wallet.

#### How much does it cost to change tax settings?

A one-time fee is charged only during initial setup. After that, all changes are completely free.

#### Can I disable tax after enabling it?

Yes. Set all tax rates to 0% to effectively disable taxation. The feature remains enabled but no fees will be collected.

#### When do tax settings take effect?

Tax settings take effect immediately after the transaction is confirmed. All subsequent trades will apply the new rates.

#### Why isn't my Buy/Sell Tax working?

Buy/Sell Tax only applies to trades through liquidity pools. Make sure you have created a liquidity pool through Alphecca's Create Liquidity Pool page for the tax to take effect.
