---
description: "How Proof of Delivery fits into the retail and warehouse journey."
icon: truck
---

# Proof of Delivery handoff

Proof of Delivery belongs in the same customer journey as order capture, warehouse execution, and exception handling. In GitBook, it can be positioned as the final operational mile instead of a disconnected product tile.

## Handoff model

```mermaid
sequenceDiagram
    participant POS as Store or order source
    participant WMS as Warehouse flow
    participant POD as Proof of Delivery
    participant Support as Managed Services
    POS->>WMS: Reserve or prepare goods
    WMS->>POD: Create delivery task
    POD->>POD: Capture delivery status and evidence
    POD->>Support: Escalate exception or change request
```

## Recommended page set

- Delivery task lifecycle.
- Driver or field-user workflow.
- Evidence capture and attachment rules.
- Failed delivery or customer-unavailable handling.
- Operational reporting and exception review.

{% hint style="info" %}
The current portal exposes Proof of Delivery as its own B1ProSuite product tile. The demo nests it in the retail operating flow so customer journeys are easier to explain.
{% endhint %}
