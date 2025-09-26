```mermaid
graph TD
    A[Start: User provides sector] --> B{Parallel Analysis};
    B --> C[AlphaResearchAgent: <br>Generates qualitative thesis];
    B --> D[QuantAgent: <br>Generates quantitative signal];
    C --> E{CIOAgent: <br>Synthesizes inputs and decides trade};
    D --> E;
    E --> F{RiskManagementAgent: <br>Performs VaR and concentration checks};
    F --> G{Trade Approved?};
    G -- Yes --> H[ExecutionAgent: <br>Simulates trade execution];
    G -- No --> I[End: Trade Vetoed];
    H --> J[End: Trade Executed];
```
