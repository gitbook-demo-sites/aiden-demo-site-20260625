---
description: "Representatieve Aiden POS-operatiepagina gebaseerd op de bronportal."
icon: cash-register
---

# Aiden POS-operaties

Aiden POS-documentatie moet winkelteams een taakgericht pad geven door dagelijkse checkoutprocessen, met admin- en hardwaresetup dichtbij.

## Kernflow transactie

```mermaid
flowchart LR
    Login[Login] --> Customer[Selecteer klant]
    Customer --> Item[Selecteer of scan artikel]
    Item --> Review[Controleer hoofdscherm]
    Review --> Pause{Pauzeren nodig?}
    Pause -- Ja --> Resume[Hervat transactie]
    Pause -- Nee --> Finish[Rond verkoop af]
    Resume --> Finish
    Finish --> Payment[Betaling, cadeaubon, kas of bijlage]
```

## Wat hier hoort te staan

- Login- en sessiegedrag.
- Klantselectie en wijzigen van klantcontext.
- Artikelen selecteren via handmatige keuze of barcode scanner.
- Hoofdscherm, totalen, kortingen en transactiestatus begrijpen.
- Transacties pauzeren en hervatten.
- Afronden met betaling, cadeaubon, kasprocedure, bijlage of signature pad.

{% hint style="success" %}
Dit is een sterke GitBook AI-demopagina, omdat veelvoorkomende POS-taken in een beantwoordbare flow bij elkaar staan.
{% endhint %}
