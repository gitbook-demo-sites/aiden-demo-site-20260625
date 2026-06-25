---
description: "Aidens huidige Confluence-model weerspiegelt waarschijnlijk producteigenaarschap. GitBook kan dat behouden en daar review-, publicatie- en analytics-workflows aan toevoegen."
icon: people-arrows
---

# Documentatie operating model

Aidens huidige Confluence-model weerspiegelt waarschijnlijk producteigenaarschap. GitBook kan dat behouden en daar review-, publicatie- en analytics-workflows aan toevoegen.

## Voorgestelde governance

- Product owners zijn verantwoordelijk voor accuratesse per productgebied.
- Een centrale documentatie-eigenaar bewaakt navigatie, naamgeving, redirects en duplicatie.
- Support levert feedback vanuit terugkerende tickets.
- Implementatiepartners kunnen later adaptieve of afgeschermde setup-pagina's krijgen.

```mermaid
sequenceDiagram
    participant Author as Productauteur
    participant Reviewer as Reviewer
    participant GitBook as GitBook
    participant Support as Support
    Author->>GitBook: Maakt pagina of wijzigingsverzoek
    GitBook->>Reviewer: Vraagt review
    Reviewer-->>GitBook: Keurt goed of vraagt aanpassing
    Support->>GitBook: Voegt feedback uit tickets toe
```
