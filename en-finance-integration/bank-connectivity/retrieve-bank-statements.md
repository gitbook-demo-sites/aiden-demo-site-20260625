---
description: "How bank statement retrieval fits into the finance operating flow."
icon: file-invoice-dollar
---

# Retrieve bank statements

Bank statement retrieval is the recurring operational moment where connectivity, authentication, and SAP data handling come together.

## Retrieval flow

```mermaid
sequenceDiagram
    participant User as Finance user
    participant Aiden as Bank Connectivity
    participant Bank as Bank
    participant SAP as SAP Business One
    User->>Aiden: Request statement retrieval
    Aiden->>Bank: Retrieve authorized statement data
    Bank-->>Aiden: Return available statements
    Aiden->>SAP: Prepare posting or export
    SAP-->>User: Reconciliation-ready data
```

## Operational checks

- Connection is active and not expired.
- The target bank account belongs to the right organization.
- Statement period and currency match finance expectations.
- Notifications are reviewed for authentication or retrieval exceptions.
