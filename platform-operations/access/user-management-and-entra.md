---
description: "User management and Microsoft Entra guidance across Aiden products."
icon: user-shield
---

# User management and Microsoft Entra

User and identity pages appear in multiple source spaces, including POS and WMS. GitBook should centralize the shared model and link product-specific instructions back to it.

## Access model

```mermaid
flowchart TD
    Entra[Microsoft Entra] --> Roles[Portal roles]
    Roles --> POS[Aiden POS]
    Roles --> WMS[Aiden WMS]
    Roles --> Bank[Bank Connectivity]
    Roles --> B1[B1ProSuite]
```

## Recommended content

- Identity provider prerequisites.
- Role mapping by product.
- Admin versus operator permissions.
- Deprovisioning and audit expectations.
- Product-specific login troubleshooting.

{% hint style="success" %}
Shared identity documentation is a simple way to reduce repeated content across product spaces while keeping product pages focused on workflows.
{% endhint %}
