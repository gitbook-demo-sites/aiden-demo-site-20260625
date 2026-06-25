---
description: "Representative Aiden POS operations page based on the source portal topics."
icon: cash-register
---

# Aiden POS operations

Aiden POS documentation should give store teams a task-first path through everyday checkout work while keeping admin and hardware setup close by.

## Core transaction flow

```mermaid
flowchart LR
    Login[Login] --> Customer[Select customer]
    Customer --> Item[Select or scan item]
    Item --> Review[Review main screen]
    Review --> Pause{Need to pause?}
    Pause -- Yes --> Resume[Resume transaction]
    Pause -- No --> Finish[Finish sale]
    Resume --> Finish
    Finish --> Payment[Payment, gift card, cash, or attachment]
```

## What should live here

- Login and session behavior.
- Selecting a customer and changing customer context.
- Selecting an item manually or through barcode scanner support.
- Understanding the main screen, totals, discounts, and transaction state.
- Pausing and resuming a transaction.
- Finishing a transaction with payment, gift card, cash procedure, attachment, or signature pad.

{% hint style="success" %}
This is a strong GitBook AI demo page because it gathers the common point-of-sale tasks into one answerable flow instead of scattering them across many small pages.
{% endhint %}
