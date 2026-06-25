---
description: "How docs.aiden.eu was translated into this demo."
icon: diagram-project
---

# Source Portal Model

The current Aiden portal runs on Scroll Viewport and Atlassian Confluence. The public homepage presents three main areas: Industry Solutions, Integration Platforms, and B1 ProSuite.

## Observed source spaces

| Source area | Source path | Destination in demo |
| --- | --- | --- |
| Aiden POS | `/aidenpos/` | Retail & Commerce Apps |
| Bank Connectivity | `/bankconnectivity/` | Finance & Integration |
| Aiden WMS | `/aidenwms/` | Retail & Commerce Apps |
| Aiden Templates for Magento | `/atfm/` | Retail & Commerce Apps |
| Aiden Connect | `/aip/` | Finance & Integration |
| B1ProSuite Platform | `/b1prosuiteplatform/` | Platform Operations |
| RetailPro | `/retailpro/` | Retail & Commerce Apps |
| WarehousePro | `/warehousepro/` | Retail & Commerce Apps |
| Proof of Delivery | `/pod/` | Retail & Commerce Apps |

## What changed

{% stepper %}
{% step %}
### The first click is consolidated

The demo uses three product areas instead of nine separate product tiles.
{% endstep %}

{% step %}
### Anchor pages are rewritten

Each space has English landing pages, route maps, and core workflows instead of a raw scrape.
{% endstep %}

{% step %}
### GitBook-native interaction is added

Cards, hints, steppers, tabs, diagrams, and AI prompts make the demo easier to navigate.
{% endstep %}
{% endstepper %}

## Assumptions

- Aiden wants to keep the current product taxonomy while reducing customer-facing fragmentation.
- The demo should be a representative first version, not a full migration of every Confluence page.
- Product teams are likely to remain owners of product-specific pages, while a central documentation owner maintains navigation and standards.
