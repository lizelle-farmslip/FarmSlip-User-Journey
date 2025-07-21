# FarmSlip App User Journey Map

## User Journey Flowchart

```mermaid
flowchart TD
    A[Awareness] --> B[Website Landing]
    B --> C["Snap a slip → see it sorted in 5s" CTA]
    C --> D[Slip-Scan Demo]
    D --> E[Sign-Up Modal]
    E --> F[Persona Picker]
    
    F --> G1[A: Farm Admin Hero]
    F --> G2[B: Field Service Agent]
    F --> G3[C: Smallholder Farmer]
    F --> G4[D: Commercial Finance Team]
    F --> G5[E: Rural SME Owner]
    F --> G6[F: Consultant/Accountant]
    F --> G7[G: Fuel-Claim Employee]
    
    %% Farm Admin Hero Journey
    G1 --> H1[Onboarding: Farm setup & 1st slip scan]
    H1 --> I1[Activation: 5+ slips & daily 18:00 push 🔒]
    I1 --> J1[Value Reveal: Farm analytics cards]
    J1 --> K1[Upgrade Prompt: Advanced reporting limit 🔒]
    K1 --> L1[Retention: Weekly WhatsApp digest 🔒]
    L1 --> M1[Referral: +20 slips for farm expansion]
    
    %% Field Service Agent Journey
    G2 --> H2[Onboarding: Route setup & 1st slip scan]
    H2 --> I2[Activation: 5+ slips & location tracking 🔒]
    I2 --> J2[Value Reveal: Route optimization cards]
    J2 --> K2[Upgrade Prompt: Multi-client gated feature 🔒]
    K2 --> L2[Retention: Progress streaks & badges 🔒]
    L2 --> M2[Referral: +20 slips for team expansion]
    
    %% Smallholder Farmer Journey
    G3 --> H3[Onboarding: Simple farm profile & 1st slip]
    H3 --> I3[Activation: 5+ slips & expense tracking 🔒]
    I3 --> J3[Value Reveal: Profit margin insights]
    J3 --> K3[Upgrade Prompt: Export limits reached 🔒]
    K3 --> L3[Retention: Monthly savings reports 🔒]
    L3 --> M3[Referral: +20 slips for community growth]
    
    %% Commercial Finance Team Journey
    G4 --> H4[Onboarding: Team setup & 1st batch scan]
    H4 --> I4[Activation: 5+ team members & bulk processing 🔒]
    I4 --> J4[Value Reveal: Compliance dashboard cards]
    J4 --> K4[Upgrade Prompt: Advanced audit features 🔒]
    K4 --> L4[Retention: Weekly compliance digest 🔒]
    L4 --> M4[Referral: +20 slips per team member]
    
    %% Rural SME Owner Journey
    G5 --> H5[Onboarding: Business setup & 1st expense]
    H5 --> I5[Activation: 5+ categories & tax tracking 🔒]
    I5 --> J5[Value Reveal: Cash flow prediction cards]
    J5 --> K5[Upgrade Prompt: Multi-business limits 🔒]
    K5 --> L5[Retention: Monthly business insights 🔒]
    L5 --> M5[Referral: +20 slips for business network]
    
    %% Consultant/Accountant Journey
    G6 --> H6[Onboarding: Client portfolio & 1st review]
    H6 --> I6[Activation: 5+ clients & batch processing 🔒]
    I6 --> J6[Value Reveal: Client comparison analytics]
    J6 --> K6[Upgrade Prompt: White-label features 🔒]
    K6 --> L6[Retention: Client performance reports 🔒]
    L6 --> M6[Referral: +20 slips per new client]
    
    %% Fuel-Claim Employee Journey
    G7 --> H7[Onboarding: Claim setup & 1st fuel slip]
    H7 --> I7[Activation: 5+ claims & auto-categorization 🔒]
    I7 --> J7[Value Reveal: Mileage optimization cards]
    J7 --> K7[Upgrade Prompt: Historical data limits 🔒]
    K7 --> L7[Retention: Monthly savings tracking 🔒]
    L7 --> M7[Referral: +20 slips for team benefits]
    
    %% Sunken-cost elements notation
    I1 -.-> N1[🔒 Progress bar shows 80% complete]
    K1 -.-> N2[🔒 Blurred premium report preview]
    L1 -.-> N3[🔒 Streak insurance offer]
    M1 -.-> N4[🔒 Rolled-over slip credits]
```

## KPI Summary Table

```markdown
| Stage | Farm Admin Hero | Field Service Agent | Smallholder Farmer | Commercial Finance Team | Rural SME Owner | Consultant/Accountant | Fuel-Claim Employee |
|-------|----------------|--------------------|--------------------|------------------------|-----------------|----------------------|-------------------|
| **Onboarding (Day 0)** | 1st slip scanned with farm context | 1st slip scanned with location data | 1st expense slip categorized | 1st batch of slips processed | 1st business expense recorded | 1st client slip reviewed | 1st fuel receipt claimed |
| **Activation (Week 1)** | ≥5 slips + daily 18:00 farm summary push | ≥5 slips + route optimization enabled | ≥5 slips + expense categories setup | ≥5 team members active + bulk processing used | ≥5 different expense categories used | ≥5 clients onboarded + batch review workflow | ≥5 fuel claims + auto-categorization active |
| **Value Reveal** | Farm analytics dashboard engagement | Route efficiency improvements shown | Profit margin insights accessed | Compliance score improvements | Cash flow predictions viewed | Client comparison analytics used | Mileage savings calculations shown |
| **Upgrade Prompt** | Advanced reporting limit reached | Multi-client features requested | Export/sharing limits hit | Advanced audit features needed | Multi-business account limits | White-label branding requested | Historical data access limits |
| **Retention Loop** | Weekly WhatsApp farm digest opened | Progress streaks maintained | Monthly savings reports engagement | Weekly compliance digest review | Monthly business insights accessed | Client performance reports sent | Monthly fuel savings tracking |
| **Referral Ask** | +20 slips for farm team expansion | +20 slips for service team growth | +20 slips for farmer community | +20 slips per referred team member | +20 slips for business network | +20 slips per new client referral | +20 slips for employee benefits |
```

## Sunken-Cost Tactics Implementation

- **🔒 Progress Bar**: Shows completion percentage at key friction points
- **🔒 Blurred Report Preview**: Teases premium insights before upgrade
- **🔒 Streak Insurance**: Offers to protect achievement streaks
- **🔒 Rolled-over Slip Credits**: Carries unused processing credits forward