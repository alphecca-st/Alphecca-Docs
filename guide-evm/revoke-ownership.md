---
icon: hexagon-xmark
---

# Revoke Ownership (EVM)

This guide walks you through revoking contract ownership on EVM chains with Alphecca Tools.

{% hint style="info" %}
#### Tool Page

* Link : [Revoke Ownership on Ethereum](https://alphecca.io/en/revoke-ownership/ethereum)
* Link : [Revoke Ownership on Binance Smart Chain](https://alphecca.io/en/revoke-ownership/binance)
* Link : [Revoke Ownership on Base](https://alphecca.io/en/revoke-ownership/base)
* Link : [Revoke Ownership on Polygon](https://alphecca.io/en/revoke-ownership/polygon)
* Link : [Revoke Ownership on Avalanche](https://alphecca.io/en/revoke-ownership/avalanche)
* Link : [Revoke Ownership on Monad](https://alphecca.io/en/revoke-ownership/monad)
* Link : [Revoke Ownership on Arbitrum](https://alphecca.io/en/revoke-ownership/arbitrum)
* Link : [Revoke Ownership on Optimism](https://alphecca.io/en/revoke-ownership/optimism)
{% endhint %}

## How to Use Revoke Ownership

### Step 1: Connect Wallet

Click the Connect Wallet button in the top-right corner to connect.

### Step 2: Select Token Address

Select the token contract address you want to revoke ownership for.

{% hint style="warning" %}
This feature is only available for tokens created through Alphecca. Only the token owner can renounce ownership.
{% endhint %}

### Step 3: Confirm Renounce

Review the warning message and confirm that you understand the consequences.

{% hint style="danger" %}
This action is irreversible. Once ownership is revoked, you will permanently lose the ability to modify token settings including Tax, Anti Bot, Anti Whale, Blacklist, Mint, and Pause functions.
{% endhint %}

### Step 4: Revoke Ownership

Click the 'Revoke Ownership' button and approve the transaction in your wallet.

***

### Frequently Asked Questions

#### Why revoke ownership?

Revoking ownership signals to your community that the token is fully decentralized and cannot be manipulated by the creator. This builds trust and confidence among holders.

#### Can I recover ownership after revoking?

No. Revoking  ownership is permanent and irreversible. The token will have no owner forever.

#### What functions become unavailable after revoking?

| Function     | Status After Renounce |
| ------------ | --------------------- |
| Tax Settings | Locked forever        |
| Anti Bot     | Locked forever        |
| Anti Whale   | Locked forever        |
| Blacklist    | Locked forever        |
| Mint         | Disabled forever      |
| Pause        | Disabled forever      |

#### Should I configure all settings before revoking?

Yes. Make sure all Tax, Anti Bot, and Anti Whale settings are finalized before revoking. You will not be able to change them afterward.
