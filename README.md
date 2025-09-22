# ARquitecture-for-SOVRA

graph TD
    %% Frontend Layer
    A[👤 User Interface] --> B[React + Next.js + ThirdWeb v5]
    B --> C[Wallet Connection]
    C --> D[Profile Management UI]
    
    %% AI Agent Layer
    E[🤖 BILDI AI Agent] --> F[Llama 3 LLM]
    E --> G[Telegram Bot API]
    E --> H[Matching Algorithm]
    E --> I[Smart Contract Automation]
    
    %% Privacy Layers
    J[🔐 Privacy Management] --> K[Level 1: Public Data]
    J --> L[Level 2: Encrypted Data]
    J --> M[Level 3: Confidential Commitments]
    
    %% BlockDAG Layer
    N[⛓️ BlockDAG Blockchain] --> O[Profile Factory Contract]
    N --> P[Individual Profile Contracts]
    N --> Q[Escrow Contracts]
    N --> R[BDAG Token Payments]
    
    %% Storage Layer
    S[💾 Data Storage] --> T[IPFS Network]
    S --> U[PostgreSQL Database]
    S --> V[Redis Cache]
    
    %% Connections between layers
    D --> J
    J --> N
    E --> N
    N --> S
    
    %% Cross-layer connections
    G --> D
    H --> U
    I --> O
    K --> P
    L --> T
    M --> P
    O --> P
    P --> Q
    
    %% External integrations
    W[GitHub API] --> E
    X[Company Telegram] --> G
    Y[Builder Notifications] --> G
    
    %% Data flows
    P --> U
    T --> V
    R --> Q
    
    style A fill:#e1f5fe
    style E fill:#e8f5e8
    style J fill:#f3e5f5
    style N fill:#fff3e0
    style S fill:#ffebee
