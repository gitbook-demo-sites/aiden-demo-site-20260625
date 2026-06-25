---
description: "Aiden Connect integration services explained as a customer journey."
icon: diagram-project
---

# Integration services

Aiden Connect helps customers keep applications using the same data across an application landscape. The demo positions integration services as a managed operating layer, not just a list of connectors.

## Integration lifecycle

```mermaid
flowchart TD
    Source[Source system] --> Transform[Transform and validate]
    Transform --> SAP[SAP Business One or SAP ByDesign]
    Transform --> Monitor[Integration monitor]
    Monitor --> Alert[Alert and remediate]
    Alert --> Improve[Update documentation and runbook]
```

## Example integration topics

- PDF invoice scanning to SAP ByDesign.
- Exchange rate information for SAP Business One.
- Exchange rate information for SAP ByDesign.
- Aiden Connect Peppol.
- HTTPS prerequisites.

{% hint style="success" %}
Aiden Connect is a strong place to show GitBook AI answering cross-system questions because the value comes from understanding dependencies across systems.
{% endhint %}
