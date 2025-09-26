---
icon: lock
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

# Revoke Authority

**Revoke token creator authorities to secure token trustworthiness. Revokable authorities include mint authority, freeze authority, and update authority.**

{% hint style="success" %}
#### [https://alphecca.io/revoke-authority](https://alphecca.io/revoke-authority)
{% endhint %}

## How to Use Revoke Authority?&#x20;

1. Click the **Connect Wallet** button in the top-right corner to connect.
2. Select the **authority type** you want to revoke: Freeze, Mint, or Update.
3. Select the **token** for which you want to revoke authority.
4. Review the warning - this action is **permanent and cannot be undone**.
5. Click the **Revoke Authority** button and approve the transaction in your wallet app.
6. When the transaction is completed, the **transaction signature** will be displayed at the **top right corner**.

## What does each authority type mean?

* **Freeze Authority**: Ability to freeze token accounts, preventing transfers
* **Mint Authority**: Ability to create new tokens and increase supply
* **Update Authority**: Ability to modify token metadata (name, symbol, image)

Revoking these authorities makes your token more decentralized and trustworthy, but you lose control permanently.

## Can I get these authorities back after revoking?

No, revoking authorities is permanent and irreversible. Once revoked, no one (including you) can ever mint new tokens, freeze accounts, or update metadata. Make sure your token is fully configured before revoking authorities.
