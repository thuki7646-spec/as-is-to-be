mermaid
flowchart TD
    A[Client] --> B[Website form]
    B --> C[Email]
    C --> D[Manager]
    D --> E[Manual input to Excel]
    D --> F[Call warehouse]
    F --> G{Stock available?}
    G -- YES --> H[Create invoice in Word]
    G -- NO --> I[Notify client]
    H --> J[Send invoice by email]
    J --> K[Accountant]
    K --> L[Check payment once per day]
