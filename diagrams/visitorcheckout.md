# Executive Workflow

```mermaid
flowchart TD

    A[Visitor Status = Checked In]

    A --> B[Receptionist Selects Checkout]

    B --> C[Confirm Checkout]

    C --> D[Status = Checked Out]

    D --> E[Visitor Removed From Active Visitors]
```