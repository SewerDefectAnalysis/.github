# Sewer Defect Analysis Framework
```mermaid
%%{init: {'flowchart': {'nodeSpacing': 40, 'rankSpacing': 50}}}%%
flowchart LR

    A[Database<br/>Creation]:::data --> B[Validation<br/>Rules]:::validation
    B --> D[Defect Distribution<br/>Analysis]:::analysis
    D --> E[Defect-Factor<br/>Correlation]:::analysisP2
    E --> F[Defect<br/>Prediction]:::prediction

    %% Optional branch BELOW
    subgraph optional_branch[ ]
        direction TB
        C[Optional Data Quality<br/>Assessment]:::optional
    end

    B -.-> C

    %% Click links
    click A "https://github.com/SewerDefectAnalysis/Database_Structure"
    click B "https://github.com/your-org/validation-repo"
    click C "https://github.com/your-org/quality-repo"
    click D "https://github.com/your-org/distribution-repo"
    click E "https://github.com/your-org/correlation-repo"
    click F "https://github.com/your-org/prediction-repo"

    %% Styles
    classDef data fill:#E8F0FE,stroke:#1A73E8,stroke-width:2px
    classDef validation fill:#E6F4EA,stroke:#188038,stroke-width:2px
    classDef analysis fill:#F3E8FD,stroke:#9334E6,stroke-width:2px
    classDef analysisP2 fill:#FDEBD0,stroke:#E67E22,stroke-width:2px
    classDef prediction fill:#FEF7E0,stroke:#F9AB00,stroke-width:2px
    classDef optional fill:#E6F4EA,stroke:#188038,stroke-width:2px,stroke-dasharray: 5 5
```
This organization contains the code and resources supporting multiple research studies on defect-level analysis of sewer systems.

## Papers and Repositories
### 1. Database Structure for Defect-Level Modelling

### 2. Validation Rules and Workflow

### 3. Defect Distribution Analysis
