# Executive Workflow

```mermaid
flowchart TD
    A[Open Reception Application] --> B[Login Screen]

    B --> C{Login Method}

    C --> D[Email and Password]
    C --> E[Microsoft 365 Login]

    D --> F{Valid Credentials?}
    E --> F

    F -->|No| G[Show Error]
    G --> B

    F -->|Yes| H[Desk Setup Popup]

    H --> I[Enter Desk ID]
    H --> J[Select Floor]

    I --> K[Save Changes]
    J --> K

    K --> L[Reception Dashboard]

    L --> M[View Visitor Count]
    L --> N[View Active Visitors]
```