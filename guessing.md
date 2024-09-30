```mermaid
flowchart TD
    A[Start Game] --> B[Guess a # Btw 1 and 10]
    B --> C[Enters Input]
    C --> D[invalid input]
    C --> E[valid input]
    D --> B
    E --> F[Too High]
    E --> G[Too Low]
    F --> C
    G --> C
    E -->  H[Correct]
    H--> I[YOU WIN!]
    I --> J[END]
```