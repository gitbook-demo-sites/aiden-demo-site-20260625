---
description: "Hoe Proof of Delivery past in retail- en warehouseprocessen."
icon: truck
---

# Proof of Delivery-handoff

Proof of Delivery hoort in dezelfde klantreis als ordervastlegging, warehouse-uitvoering en exception handling. In GitBook kan dit worden gepositioneerd als de laatste operationele stap in plaats van als losse producttegel.

## Handoff-model

```mermaid
sequenceDiagram
    participant POS as Winkel of orderbron
    participant WMS as Warehouseflow
    participant POD as Proof of Delivery
    participant Support as Managed Services
    POS->>WMS: Reserveer of bereid goederen voor
    WMS->>POD: Maak delivery task aan
    POD->>POD: Leg status en bewijs vast
    POD->>Support: Escaleer uitzondering of wijzigingsverzoek
```

## Aanbevolen paginaset

- Lifecycle van delivery tasks.
- Workflow voor chauffeur of field user.
- Bewijsvastlegging en regels voor bijlagen.
- Afhandeling van mislukte levering of afwezige klant.
- Operationele rapportage en exception review.

{% hint style="info" %}
De huidige portal toont Proof of Delivery als eigen B1ProSuite-producttegel. De demo plaatst het in de retail-operatieflow zodat klantreizen makkelijker uit te leggen zijn.
{% endhint %}
