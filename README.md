# LATAM Builders x SOVRA 
## The First Professional Directory for Web3 LATAM

[![AI Powered](https://img.shields.io/badge/AI-Powered-purple)](https://llama.meta.com)
[![Privacy](https://img.shields.io/badge/Privacy-First-orange)](https://ipfs.io)

## **Project Overview**

LATAM Builders is a revolutionary decentralized professional directory that connects top Web3 talent across Latin America with global opportunities. Built on BlockDAG Network for superior performance and cost-efficiency.

### **Overall Key Features**
- **LATAM Focus** - Specialized for Latin American market with expansion in mind 
- **AI Agent "BILDI"** - Automated talent matching
- **Innovative Data collection and reputation system** - Through API and proprietary development
- **Payment System Integration** - innovative approach to split the payment btw LB and data owner
- **Three-Layer Privacy** - Granular data protection  
- **Utility Token Integration** - Native token utility and staking

---

## 🏗️ **1. Complete System Architecture**

```mermaid
graph TD
    %% Frontend Layer
    A[User Interface] --> B[React + Next.js + ThirdWeb v5]
    B --> C[Wallet Connection Manager]
    C --> D[Profile Management Dashboard]
    
    %% API Gateway Layer
    E[LATAM Builders REST API] --> F[Authentication Middleware]
    E --> G[Rate Limiting Layer]
    E --> H[API Gateway Router]
    
    %% API Endpoints
    H --> I[Builders Search API]
    H --> J[Profiles Create API]
    H --> K[Payments Process API]
    H --> L[AI Matching API]
    H --> M[Analytics API]
    H --> N[Contracts Deploy API]
    
    %% AI Agent Layer
    O[BILDI AI Agent] --> P[Llama 3.2 LLM Engine]
    O --> Q[Telegram Bot Integration]
    O --> R[Smart Matching Algorithm]
    O --> S[Contract Automation Engine]
    
    %% Privacy Management
    T[Privacy Controller] --> U[Level 1: Public Data]
    T --> V[Level 2: Encrypted Access]
    T --> W[Level 3: Confidential Proofs]
    
    %% Blockchain Layer
    X --> Y[Profile Factory Contract]
    X --> Z[Individual Profile Contracts]
    X --> AA[Escrow Smart Contracts]
    X --> BB[Token Handler]
    X --> CC[Reputation Registry]
    
    %% Storage Infrastructure
    DD[Data Storage] --> EE[IPFS Distributed Network]
    DD --> FF[PostgreSQL Database]
    DD --> GG[Redis Cache Layer]
    DD --> HH[Backup Systems]
    
    %% External Integrations
    II[External APIs] --> JJ[GitHub API Integration]
    II --> KK[Market Data Feeds]
    II --> LL[Telegram Bot API]
    II --> MM[Email Notification Service]
    
    %% Data Flow Connections
    D --> T
    T --> X
    O --> X
    X --> DD
    
    %% Cross-layer Integration
    Q --> D
    R --> FF
    S --> Y
    U --> Z
    V --> EE
    W --> Z
    Y --> Z
    Z --> AA
    
    %% API Integration
    L --> O
    I --> FF
    J --> Y
    K --> BB
    M --> CC
    N --> S
    
    %% External Data Flow
    JJ --> O
    KK --> R
    LL --> Q
    MM --> D
    
    %% Performance Optimization
    Z --> FF
    EE --> GG
    BB --> AA
    
    style A fill:#e1f5fe
    style E fill:#e8f5e8
    style O fill:#fff3e0
    style T fill:#f3e5f5
    style X fill:#ffebee
    style DD fill:#e0f2f1
    style II fill:#fce4ec
```

---

## 🔐 **2. Privacy Architecture - Three-Layer System**

```mermaid
graph TD
    %% User Input
    A[👤 Builder Profile Creation] --> B[Data Classification]
    
    %% Data Classification
    B --> C[🌍 Public Information]
    B --> D[🔒 Semi-Private Data]  
    B --> E[🔐 Confidential Information]
    
    %% Level 1: Public Data (On-chain)
    C --> F[Public Profile Smart Contract]
    F --> G[Name, Skills]
    F --> H[Public Reputation Score]
    F --> I[Year first joined Web3]
    F --> I[Availability Status]
    
    %% Level 2: Encrypted Access (IPFS + Payment Gate)
    D --> K[🔒 Encrypted Data Package]
    K --> L[AES-256 Encryption]
    L --> M[IPFS Storage]
    M --> N[Payment Required]
    N --> O[Decryption Key Release]
    
    %% Level 2 Content
    O --> P[Contact Information]
    O --> Q[Social Media Profiles]
    O --> R[Detailed Work History]
    O --> S[Performance Metrics]
    
    %% Level 3: Confidential Proofs (Zero-Knowledge Style)
    E --> T[Cryptographic Commitments]
    T --> U[Hash-based Commitments]
    U --> V[Identity Verification]
    U --> W[Education Certificates]
    U --> X[Salary History]
    U --> Y[Client References]
    
    %% Verification Process
    V --> Z[Verification Request]
    Z --> AA[Generate Proof]
    AA --> BB[Verify Without Revealing]
    BB --> CC[Update Reputation]
    
    %% Smart Contract Integration
    F --> DD[Profile Contract]
    M --> EE[Access Control Contract]
    T --> FF[Verification Registry]
    
    %% Payment Flow
    N --> GG[Company Pays LB]
    GG --> HH[80% to Builder]
    GG --> II[20% to LB]
    
    %% Access Control
    EE --> JJ{Authorized Access?}
    JJ -->|Yes| O
    JJ -->|No| KK[Access Denied]
    
    %% Privacy Enforcement
    DD --> LL[🔒 Privacy Policy Enforcement]
    EE --> LL
    FF --> LL
    LL --> MM[Audit Trail]
    
    %% Data Protection
    LL --> NN[GDPR Compliance]
    LL --> OO[Right to be Forgotten]
    LL --> PP[Data Portability]
    
    style C fill:#e8f5e8
    style D fill:#fff3e0
    style E fill:#ffebee
    style F fill:#e1f5fe
    style K fill:#f3e5f5
    style T fill:#fce4ec
```

---

## 🤖 **3. BILDI AI Agent - Complete Workflow**

```mermaid
graph TD
    %% Company Input Phase
    A[🏢 Company Request] --> B[📱 Telegram Message with Requirements]
    
    %% AI Processing Engine
    B --> C[BILDI AI Agent]
    C --> D[Llama 3.2 Processing]
    D --> E[Natural Language Understanding]
    
    %% Information Extraction
    E --> F[Skills Required]
    E --> G[Team Size]
    E --> H[Project Duration]
    E --> I[Budget Amount]
    E --> J[Project Type]
    E --> K[Location Preference]
    
    %% Blockchain Query Phase
    F --> L[Query Network]
    G --> L
    H --> L
    I --> L
    J --> L
    K --> L
    
    %% Smart Contract Data Retrieval
    L --> M[📊 Read Profile Factory Contract]
    M --> N[📝 Fetch Individual Profiles]
    N --> O[🔒 Access Private Data with Payment]
    N --> P[⭐ Check Reputation Scores]
    N --> Q[📅 Verify Availability]
    N --> R[💰 Compare Rate Expectations]
    
    %% AI Matching Algorithm
    O --> S[Advanced Matching Engine]
    P --> S
    Q --> S
    R --> S
    
    S --> T[Calculate Compatibility Scores]
    T --> U[Apply Weighting Factors]
    
    %% Top Candidates Selection
    U --> V[Maria Gonzalez - Score 96]
    U --> W[Carlos Mendoza - Score 93]
    U --> X[Ana Rodriguez - Score 90]
    U --> Y[4️Roberto Silva - Score 87]
    
    %% Smart Contract Deployment
    V --> Z[Auto-Deploy Escrow Contract]
    W --> Z
    X --> Z
    
    %% Escrow Configuration
    Z --> AA[Lock 5000 tokens]
    Z --> BB[Set Milestone Conditions]
    Z --> CC[Configure Dispute Resolution]
    Z --> DD[Enable Auto-payments]
    Z --> EE[Setup Performance Tracking]
    
    %% Notification System
    AA --> FF[📲 Send Telegram Notifications]
    V --> FF
    W --> FF
    X --> FF
    
    %% Notification Content
    FF --> GG[📄 Project Details]
    FF --> HH[💰 Payment Information]
    FF --> II[⛓️ Smart Contract Address]
    FF --> JJ[✅ Accept Project Button]
    FF --> KK[📊 Team Composition]
    
    %% Builder Response Handling
    JJ --> LL{Builder Response}
    LL -->|Accept| MM[🤝 Join Project Team]
    LL -->|Decline| NN[🔄 Offer to Next Candidate]
    LL -->|Counter-offer| OO[💬 Negotiate Terms]
    
    %% Team Formation
    MM --> PP[👥 Check Team Status]
    PP --> QQ{Team Complete?}
    QQ -->|No| NN
    QQ -->|Yes| RR[🎉 Team Assembled]
    
    %% Project Execution Phase
    RR --> SS[📈 BILDI Monitors Progress]
    SS --> TT[✅ Track Milestone Completion]
    TT --> UU[🔍 Validate Deliverables]
    UU --> VV[💸 Auto-release Payments]
    VV --> WW[📊 Update Reputation Scores]
    
    %% Feedback & Learning Loop
    WW --> XX[📝 Collect Project Feedback]
    XX --> YY[🔄 Improve AI Matching]
    YY --> S
    
    %% External Integrations
    ZZ[📡 GitHub API] --> Q
    AAA[💹 Market Data] --> I
    BBB[📧 Email Service] --> FF
    CCC[📊 Analytics] --> XX
    
    %% Smart Contract Events
    AA --> DDD[emit EscrowCreated]
    VV --> EEE[emit PaymentReleased]
    WW --> FFF[emit ReputationUpdated]
    MM --> GGG[emit TeamMemberJoined]
    
    %% Error Handling
    LL -->|Timeout| HHH[⏰ Escalate to Human]
    UU -->|Dispute| III[⚖️ Activate Arbitration]
    VV -->|Payment Fail| JJJ[🚨 Alert and Retry]
    
    style C fill:#e8f5e8
    style S fill:#e1f5fe
    style Z fill:#fff3e0
    style FF fill:#f3e5f5
    style SS fill:#ffebee
```

---

## 🌐 **4. REST API Architecture**

```mermaid
graph TD
    %% API Gateway
    A[🌐 API Gateway] --> B[🔐 Authentication Layer]
    B --> C[Rate Limiting]
    C --> D[Request Analytics]
    D --> E[Load Balancer]
    
    %% Authentication Methods
    B --> F[JWT Tokens]
    B --> G[Wallet Signature]
    B --> H[OAuth 2.0]
    B --> I[API Keys]
    
    %% Core API Endpoints
    E --> J[Builders API]
    E --> K[Companies API]
    E --> L[AI Matching API]
    E --> M[Payments API]
    E --> N[Analytics API]
    E --> O[Contracts API]
    
    %% Builders API Endpoints
    J --> P[Get Builders List]
    J --> Q[Create Builder Profile]
    J --> R[Update Builder Info]
    J --> S[Get Builder Profile]
    J --> T[Verify Builder]
    J --> U[Search Builders]
    
    %% Companies API Endpoints
    K --> V[Get Companies List]
    K --> W[Register Company]
    K --> X[Create Company Project]
    K --> Y[Get Hired Builders]
    K --> Z[Submit Company Feedback]
    
    %% AI Matching API
    L --> AA[AI Match Request]
    L --> BB[Get AI Recommendations]
    L --> CC[Submit AI Feedback]
    L --> DD[Get AI Analytics]
    L --> EE[Train AI Model]
    
    %% Payments API
    M --> FF[Process Payment]
    M --> GG[Get Payment Status]
    M --> HH[Create Escrow]
    M --> II[Release Payment]
    M --> JJ[Get Payment History]
    
    %% Analytics API
    N --> KK[Builders Analytics]
    N --> LL[Projects Analytics]
    N --> MM[Revenue Analytics]
    N --> NN[Reputation Analytics]
    N --> OO[Market Analytics]
    
    %% Contracts API
    O --> PP[Deploy Smart Contract]
    O --> QQ[Get Contract Info]
    O --> RR[Interact with Contract]
    O --> SS[Get Contract Events]
    O --> TT[Verify Contract]
    
    %% Backend Services
    P --> UU[🗄️ PostgreSQL Database]
    AA --> VV[AI Engine Service]
    FF --> WW[Node]
    KK --> XX[Analytics Engine]
    PP --> YY[Contract Factory]
    
    %% External Integrations
    VV --> ZZ[Llama 3.2 API]
    WW --> AAA[Network]
    XX --> BBB[Data Visualization]
    U --> CCC[Elasticsearch]
    
    %% Response Formats
    UU --> DDD[JSON Response]
    VV --> EEE[AI Match Results]
    WW --> FFF[Transaction Data]
    XX --> GGG[Analytics Dashboard]
    
    %% Error Handling
    D --> HHH[Error Logging]
    HHH --> III[Alert System]
    HHH --> JJJ[Error Analytics]
    
    %% Caching Layer
    UU --> KKK[⚡ Redis Cache]
    CCC --> KKK
    BBB --> KKK
    
    %% Security Features
    C --> LLL[DDoS Protection]
    C --> MMM[Data Encryption]
    C --> NNN[Audit Logging]
    
    style A fill:#e1f5fe
    style J fill:#e8f5e8
    style L fill:#fff3e0
    style M fill:#f3e5f5
    style N fill:#ffebee
    style O fill:#e0f2f1
```

---

##  **5. Economics & Token Flow**

```mermaid
graph TD
    %% Token Sources
    A --> B[Companies Purchase Token]
    A --> C[Builders Earn Token]
    A --> D[Platform Operations]
    
    %% Company Payment Flow
    B --> E[Pay for Private Access]
    B --> F[Fund Project Escrows]
    B --> G[Premium Features]
    B --> H[Priority Matching]
    
    %% Builder Earning Flow
    E --> I[Builder receives 80 percent]
    F --> J[Project completion payments]
    G --> K[Feature access rewards]
    H --> L[Boost visibility]
    
    %% Platform Revenue
    E --> M[Platform receives 20 percent]
    J --> N[5 percent platform fee]
    G --> O[Subscription revenue]
    H --> P[Service fees]
    
    %% Token Utility Mechanisms
    Q[Utility Token] --> R[Payment Medium]
    Q --> S[Staking for Reputation]
    Q --> T[Governance Voting]
    Q --> U[AI Agent Operations]
    Q --> V[Security Deposits]
    
    %% Staking System
    S --> W[Builder stakes for credibility]
    S --> X[Higher stake equals higher trust]
    S --> Y[Slash for poor performance]
    S --> Z[Rewards for good performance]
    
    %% Governance Features
    T --> AA[Vote on platform features]
    T --> BB[Fee structure decisions]
    T --> CC[Dispute resolution]
    T --> DD[Protocol upgrades]
    
    %% AI Operations Costs
    U --> EE[BILDI matching computations]
    U --> FF[Smart contract deployments]
    U --> GG[Automated operations]
    U --> HH[ML model training]
    
    %% Security and Trust
    V --> II[Project escrow deposits]
    V --> JJ[Dispute arbitration bonds]
    V --> KK[Anti-spam measures]
    V --> LL[Identity verification stakes]
    
    %% Cost Comparison Analysis
    MM[Advantages] --> NN[0.001 USD per transaction]
    MM --> OO[24 USD per month for 1000 builders]
    MM --> PP[97 percent cheaper than competitors]
    MM --> QQ[10000 plus TPS capacity]
    
    %% Revenue Streams
    RR[Platform Revenue] --> SS[🔐 Private data access fees]
    RR --> TT[Project platform fees]
    RR --> UU[Premium subscriptions]
    RR --> VV[Enterprise API access]
    RR --> WW[Analytics and insights]
    
    %% Token Economics Flow
    SS --> XX[Token buyback program]
    TT --> XX
    UU --> XX
    VV --> XX
    WW --> XX
    
    %% Value Appreciation Mechanisms
    XX --> YY[Token burn mechanism]
    XX --> ZZ[Liquidity provision]
    XX --> AAA[Staker rewards distribution]
    
    %% Network Effects
    BBB[Network Growth] --> CCC[ More builders equals more value]
    BBB --> DDD[More companies equals higher demand]
    BBB --> EEE[Better AI equals better matches]
    BBB --> FFF[Higher token velocity]
    
    %% Sustainability Model
    GGG[Sustainable Economics] --> HHH[Self-funding through fees]
    GGG --> III[Data-driven fee optimization]
    GGG --> JJJ[Performance-based rewards]
    GGG --> KKK[Continuous value creation]
    
    style A fill:#e8f5e8
    style Q fill:#fff3e0
    style MM fill:#e1f5fe
    style RR fill:#f3e5f5
    style BBB fill:#ffebee
    style GGG fill:#e0f2f1
```

---

##  **Quick Start**

### **Prerequisites**
- Node.js 18+
- Yarn or npm
- EVM compatible wallet
- PostgreSQL 14+
- Redis 6+

---

## 🛠️ **Development Roadmap**

### **Phase 1: Foundation (Months 1)**
- Frontend (Directory v2):
--> Directory V2.0 – part 1:
--------> UX/UI redesign (multi-language ready)
--------> Wallet connect integration.
--------> Security baseline (auth flows, session handling).
--------> Built-in survey for onboarding builders.
--------> Basic analytics (dashboards for admins).

Backend & Infra (API v1 + Factory Smart Contracts MVP):
--> API v1 (core infra): DB setup, wallet authentication, basic conversation endpoints, Telegram integration.
--> Factory Smart Contract (MVP): 
--------> Profile creation (3 roles: builders, company, PM); 
--------> Link profiles to wallet IDs; 
--------> Basic identity verification via API (not on-chain yet); 
--------> Placeholder for 3 layers of privacy (design + stub functions).
--> Payment infra (skeleton only):
--------> Escrow contract stub.
--------> Split payments skeleton defined (not audited, not production-ready).
--------> On/Off ramp integration design (API hooks).
--> Data Collection v1: store initial survey responses in DB.

**Phase 1: Foundation (Months 2)**
- Frontend (Directory):
--> Directory V2.0 - part 2:
-----> full UX/UI refinements,
-----> multi-language support.
-----> Wallet connect stabilization + enhanced security.
-----> Built-in survey live and connected to DB.
-----> Onboarding of 300–500 verified builders (with light verification/KYC-lite if possible). 
-----> Mobile app development kickoff: MVP screens, login/wallet connect, referral program.
-----> Advanced analytics dashboard for admins.

- Backend & Infra
--> API v2:
----->Expansion to other communication channels.
-----> Integration with BILDI AI Agent v1.0.
-----> Basic performance analytics endpoints.
--> BILDI AI Agent v1.0:
-----> Works with initial survey DB (Data Collection v1).
-----> Notifications & Telegram integration.
--> Factory Smart Contract:   
-----> Extend testing of escrow
-----> Split payments (from M1 skeleton) with simulated flows (no audit yet).


### **Phase 1: Foundation (Months 3)**
- Implementation test & adjustments of privacy layers
- BILDI AI agent v2.0 - AI Engineering: Vector database for embeddings; Smart contract automation; Real-time learning system; Multi-channel communication; Predictive analytics engine
- Data collection system V2.0 and Reputation system architecture confirmation

- Frontend (Directory):
--> Implementation tests & adjustments of privacy layers in the directory (3 levels of data visibility).
--> UI updates for data privacy controls (builder can manage what’s public, semi-private, or confidential).
--> Early builder feedback loop → refinements from first 300–500 onboarded users.

- Backend & Infra:
--> BILDI AI Agent v2.0 (AI Engineering):
-----> Vector database for embeddings (builder profiles + activity).
-----> Smart contract automation for selected flows (e.g., reputation checkpoints, payments).
-----> Multi-channel communication (expand beyond Telegram).
-----> Predictive analytics engine (early recommendations on builder–company matches).
-----> Design and prepare real-time learning system (architecture, data pipelines)
--> Data Collection System v2.0:
-----> Add scraping modules (on-chain + off-chain).
-----> Integrate push-notification quick questions and responses directly into DB (with API/BILDI sync to ensure up-to-date data).
-----> Keep history for longitudinal tracking of builders.
--> Reputation System (architecture confirmation):
-----> Define formula combining on-chain activity, off-chain contributions, and social validation.
-----> Set design for weekly updates of Reputation Score.

### **Phase 2: Enhancement (Months 4)**
- Frontend (Directory 3.0):
--> Launch first B2B features:
-----> Company dashboards
-----> Advanced search & filtering for builders
-----> Bulk data access (buy/export builder datasets).
-----> UI for Reputation Score display (visual badge, levels).

- Backend & Infra:
--> Data Collection System v2.0 (implementation):
-----> Full integration of scraping (on-chain + off-chain) into DB.
--> Reputation System (implementation):
-----> Deploy scoring engine based on architecture confirmed in M3.
-----> Automate weekly updates of reputation scores.
--> BILDI AI Agent v2.0:
-----> Implement real-time learning system (feedback loop active in production).
--> Security:
-----> Internal Security Vulnerability Assessment: mart contracts, audit of escrow, split, and profile contracts.

### **Phase 3: Enhancement (Months 5)**
- Frontend (Directory):
--> B2B features:
-----> Premium data products: (e.g., ecosystem reports, custom queries)  
--> UX refinements from builder/company feedback.
--> Insights & benchmarks (ecosystem metrics, comparisons, trends).

- Backend & Infra:
--> BILDI AI Agent v2.0: implement real-time learning loop (feedback → recommendations).
--> Infrastructure optimization: DB indexing, caching, load balancing.
--> Security:
-----> API stress testing → verify scaling under heavy load.
-----> Internal security vulnerability assessment.
-----> Implement internal audit feedback & final adjustments across smart contracts, API, and infra.

### **Phase 3: Enhancement (Months 6-7)**
- Frontend (Directory):
--> Bug fixing and polishing user experience.
--> Performance optimization for large-scale directory searches and dashboards.
--> Security:
-----> Usability improvements based on audit findings.
-----> Final polish for B2B flows and dashboards.

- Backend & Infra:
--> Audit readiness adjustments (documentation, test coverage).
--> Monitoring & observability setup (logs, tracing, alerts).
--> External audit kickoff (infra + penetration testing global).
-----> External audit results → implement fixes across smart contracts, API, infra.
-->Scalability & stability testing under real-world conditions (simulate thousands of builders/requests).
-----> Final optimization for scale launch.

---

## **API Documentation**

### **Core Endpoints**

```bash
# Builders API
GET    /api/v1/builders              # List all builders
POST   /api/v1/builders/create       # Create new builder profile
PUT    /api/v1/builders/{id}         # Update builder profile
GET    /api/v1/builders/{id}/profile # Get specific builder
GET    /api/v1/builders/search       # Search builders

# Companies API  
POST   /api/v1/companies/register    # Register company
POST   /api/v1/companies/{id}/projects # Create project
GET    /api/v1/companies/{id}/hired  # Get hired builders

# AI Matching
POST   /api/v1/ai/match              # Get AI recommendations
POST   /api/v1/ai/feedback           # Submit feedback

# Payments
POST   /api/v1/payments/process      # Process payment
POST   /api/v1/payments/escrow       # Create escrow
POST   /api/v1/payments/release      # Release payment

# Smart Contracts
POST   /api/v1/contracts/deploy      # Deploy new contract
GET    /api/v1/contracts/{address}   # Get contract info
POST   /api/v1/contracts/interact    # Interact with contract
```

---

## 📜 **Smart Contracts**

### **Deployed Contracts**

```solidity
// Profile Factory Contract
contract ProfileFactory {
    address public constant PROFILE_FACTORY = 0x...;
    address public constant ESCROW_FACTORY = 0x...;
    address public constant REPUTATION_REGISTRY = 0x...;
    address public constant TOKEN = 0x...;
}
```

---

## **Security**

### **Security Measures**
- Smart contract audits by leading firms
- Multi-signature wallet controls
- Rate limiting and DDoS protection
- Encrypted data storage
- Regular security assessments

## **Community**

### **Join the LATAM Builders Community**
- [Website](https://latambuilders.xyz)

### **Partners & Supporters**
- **BlockDAG Network** - Partners 
- **Meta Llama** - AI Technology
- **LATAM Web3 Communities** - Ecosystem Partners

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 **Acknowledgments**

Special thanks to:
- BlockDAG Network team for the support, mentorship, and finantial support 
- LATAM Web3 community for continuous feedback
- All beta testers and early adopters
- Open source contributors

---

**Made with ❤️ by the LATAM Builders team**

*Building with love for the Web3 community*
