---
icon: file-pen
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

# Update Metadata

**Modify token metadata such as name, symbol, and icon.**

{% hint style="success" %}
#### [https://alphecca.io/update-metadata](https://alphecca.io/update-metadata)
{% endhint %}

## How to Use Update Metadata?&#x20;

1. Click the **Connect Wallet** button in the top-right corner to connect.
2. Select the **token** whose metadata you want to update.
3. Upload a new **token image** (required).
4. Enter the updated **token name, symbol, and description** (all required).
5. Optionally, add **social media links** using the toggle switch.
6. Click the **Update Metadata** button and approve the transaction in your wallet app.
7. When the transaction is completed, the **transaction signature** will be displayed at the **top right corner**.

## Why can't I update metadata for some tokens?

You can only update metadata if you have update authority and the metadata is still mutable. The green checkmark indicates you can update. A red X means either the update authority has been revoked, belongs to another wallet, or the metadata is already immutable.

## How long does it take for metadata changes to appear?

Metadata updates are immediate on-chain, but it may take 5-30 minutes for changes to reflect on DEX screeners, wallets, and other platforms due to caching. Some platforms may require manual refresh or take up to 24 hours to update their cached data.
