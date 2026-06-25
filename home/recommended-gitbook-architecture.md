---
description: "Suggested GitBook structure for Aiden's current documentation portal."
icon: sitemap
---

# Recommended GitBook architecture

Aiden's source portal is organized by product spaces. That makes sense internally, but it asks customers to understand the whole portfolio before finding the right task. The demo keeps product ownership intact while presenting fewer, clearer top-level routes.

<table data-view="cards">
  <thead><tr><th width="42"></th><th></th><th></th></tr></thead>
  <tbody>
    <tr><td><i class="fa-store" style="color:#0E8F72;"></i></td><td><strong>Retail and Commerce Apps</strong></td><td>One space for Aiden POS, RetailPro, WMS, WarehousePro, Proof of Delivery, and Magento commerce guidance.</td></tr>
    <tr><td><i class="fa-building-columns" style="color:#0E8F72;"></i></td><td><strong>Finance and Integration</strong></td><td>One space for Bank Connectivity, Aiden Connect, payments, SAP integration patterns, and monitored data flows.</td></tr>
    <tr><td><i class="fa-gears" style="color:#0E8F72;"></i></td><td><strong>Platform Operations</strong></td><td>One space for B1ProSuite, identity, releases, support, and operational governance.</td></tr>
  </tbody>
</table>

## Why this structure works

{% hint style="info" %}
The goal is not to hide Aiden's product breadth. It is to make the first click easier and then preserve product-level detail inside each space.
{% endhint %}

- Customers can start with their operating goal: run retail, connect finance systems, or administer the platform.
- Product teams still get clear ownership because pages can be grouped under product-specific sections inside each space.
- GitBook AI has a cleaner graph for answering cross-product questions like POS to bank reconciliation, warehouse to delivery handoff, or SAP identity setup.
- Future adaptive content can show implementation partners deeper technical setup while showing customer admins simpler workflow pages.

## Suggested ownership model

```mermaid
flowchart TD
    DocsHub[Aiden Documentation Hub] --> Retail[Retail and Commerce Apps]
    DocsHub --> Finance[Finance and Integration]
    DocsHub --> Platform[Platform Operations]
    Retail --> POS[Aiden POS]
    Retail --> WMS[Aiden WMS and WarehousePro]
    Finance --> Bank[Bank Connectivity]
    Finance --> Connect[Aiden Connect]
    Platform --> B1[B1ProSuite]
    Platform --> Support[Support and releases]
```
