---
description: "How the current docs.aiden.eu portal was translated into this demo."
icon: diagram-project
---

# Source portal model

The current Aiden portal is powered by Scroll Viewport and Atlassian Confluence. The public homepage presents three broad buckets: Industry Solutions, Integration Platforms, and B1 ProSuite.

## Source spaces observed

| Source area | Source path | Demo destination |
| --- | --- | --- |
| Aiden POS | `/aidenpos/` | Retail and Commerce Apps |
| Bank Connectivity | `/bankconnectivity/` | Finance and Integration |
| Aiden WMS | `/aidenwms/` | Retail and Commerce Apps |
| Aiden Templates for Magento | `/atfm/` | Retail and Commerce Apps |
| Aiden Connect | `/aip/` | Finance and Integration |
| B1ProSuite Platform | `/b1prosuiteplatform/` | Platform Operations |
| RetailPro | `/retailpro/` | Retail and Commerce Apps |
| WarehousePro | `/warehousepro/` | Retail and Commerce Apps |
| Proof of Delivery | `/pod/` | Retail and Commerce Apps |

## What changed

{% stepper %}
{% step %}
### Consolidated the first click

The demo uses three top-level product routes instead of nine product tiles.
{% endstep %}

{% step %}
### Rebuilt anchor pages

Each space has authored landing pages, route cards, and core workflows rather than a raw page scrape.
{% endstep %}

{% step %}
### Added GitBook-native interaction

Cards, hints, steppers, tabs, diagrams, and AI prompts make the demo easier to navigate and better suited for assistant answers.
{% endstep %}
{% endstepper %}

## Assumptions

- Aiden wants to preserve the current product taxonomy but reduce customer-facing fragmentation.
- The demo should show a representative first draft, not a full migration of every Confluence article.
- Product teams would likely continue owning product-specific pages while a central documentation owner governs navigation and shared standards.
