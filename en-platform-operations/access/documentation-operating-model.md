---
description: "A suggested operating model for Aiden documentation ownership in GitBook."
icon: people-arrows
---

# Documentation operating model

Aiden's current Confluence model likely reflects product ownership. GitBook can keep that ownership while adding clearer review, publishing, and analytics workflows.

## Suggested governance

- Product owners own accuracy for POS, WMS, Bank Connectivity, Aiden Connect, and B1ProSuite areas.
- A central documentation owner governs navigation, naming, style, redirects, and duplicate-content reduction.
- Support owns recurring issue feedback and article improvement requests.
- Implementation partners can receive adaptive or gated deeper setup pages when needed.

## Publishing flow

```mermaid
sequenceDiagram
    participant Author as Product author
    participant Reviewer as Reviewer
    participant GitBook as GitBook
    participant Support as Support
    Author->>GitBook: Draft page or change request
    GitBook->>Reviewer: Request review
    Reviewer-->>GitBook: Approve or request changes
    Support->>GitBook: Add feedback from recurring tickets
    GitBook-->>Author: Publish and track impact
```

{% hint style="info" %}
This page is useful in the sales demo because it moves the conversation beyond migration and into how Aiden can run documentation as a system.
{% endhint %}
