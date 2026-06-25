---
description: "Hoe docs.aiden.eu is vertaald naar deze demo."
icon: diagram-project
---

# Model van de huidige portal

De huidige Aiden-portal draait op Scroll Viewport en Atlassian Confluence. De publieke homepage presenteert drie hoofdgebieden: Industry Solutions, Integration Platforms en B1 ProSuite.

## Geobserveerde bronspaces

| Brongedeelte | Bronpad | Bestemming in demo |
| --- | --- | --- |
| Aiden POS | `/aidenpos/` | Brancheoplossingen |
| Bank Connectivity | `/bankconnectivity/` | Integratieplatformen |
| Aiden WMS | `/aidenwms/` | Brancheoplossingen |
| Aiden Templates for Magento | `/atfm/` | Brancheoplossingen |
| Aiden Connect | `/aip/` | Integratieplatformen |
| B1ProSuite Platform | `/b1prosuiteplatform/` | B1ProSuite |
| RetailPro | `/retailpro/` | Brancheoplossingen |
| WarehousePro | `/warehousepro/` | Brancheoplossingen |
| Proof of Delivery | `/pod/` | Brancheoplossingen |

## Wat is veranderd

{% stepper %}
{% step %}
### De eerste klik is geconsolideerd

De demo gebruikt drie productgebieden in plaats van negen losse producttegels.
{% endstep %}

{% step %}
### Anchor pages zijn herschreven

Elke space heeft Nederlandse landingspagina's, routekaarten en kernworkflows in plaats van een ruwe scrape.
{% endstep %}

{% step %}
### GitBook-native interactie is toegevoegd

Cards, hints, steppers, tabs, diagrammen en AI-prompts maken de demo beter navigeerbaar.
{% endstep %}
{% endstepper %}

## Aannames

- Aiden wil de huidige producttaxonomie behouden, maar klantgerichte fragmentatie verminderen.
- De demo moet een representatieve eerste versie zijn, geen volledige migratie van elke Confluence-pagina.
- Productteams blijven waarschijnlijk eigenaar van productspecifieke pagina's, terwijl een centrale documentatie-eigenaar navigatie en standaarden bewaakt.
